# Machine-Learning-in-Business-Sprint-10
OilyGiant mining company - Pick the region with the highest total profit for the selected oil wells.

# Project description
**You work for the OilyGiant mining company. Your task is to find the best place for a new well.**

You have data on oil samples from three regions. Parameters of each oil well in the region are already known. **Build a model that will help to pick the region with the highest profit margin.** Analyze potential profit and risks using the Bootstrapping technique.

1)	Collect the oil well parameters in the selected region: oil quality and volume of reserves;
2)	**Build a model for predicting the volume of reserves** in the new wells;
3)	**Pick the top 200 oil wells** with the highest estimated values;
4)	**Pick the region with the highest total profit** for the selected oil wells.


# Assumptions:

• **Only linear regression is suitable for model** training (the rest are not sufficiently predictable).

• When exploring the region, a **study of 500 points is carried with picking the best 200 points for the profit calculation.**

• The **budget** for development of 200 oil wells is **100 USD million.**

• One barrel of raw materials brings 4.5 USD of revenue The revenue from one unit of product is 4,500 dollars (volume of reserves is in thousand barrels).

• After the risk evaluation, keep **only the regions with the risk of losses lower than 2.5%.** From the ones that fit the criteria, the region with the highest average 
profit should be selected.

# Data: 

id — unique oil well identifier

f0, f1, f2 — three features of points (their specific meaning is unimportant, but the features themselves are significant)

product — volume of reserves in the oil well (thousand barrels).



