**Highest Value Findings and Conclusions:**
___________

Finding # 1
Rural locations are FoodMarts (tier 3)
- meat and seafood are 71 % of niche spending in tier 3.

niche products = data['Starchy Foods', 'Breakfast', 'Meat', 'Seafood']
(niche products were decided on as they are the lowest selling items by % accross all stores)

- These products are also significantly cheaper than at Tier 1 and 2 stores. this means customers are shopping for bulk and value here, not that they are willing to spend more.

If SuperKart is opening a new store in a rural area, it should be a Food Mart. People in rural areas are accustomed to driving, so if they wish to go to a large store in the city they can.
__________
2, Sugar Content Optimization

Regular sugar items sell $29 more per unit than low sugar
But low sugar dominates volume (55% of revenue)
Action: Balance mix - stock low sugar for volume, regular for margins
__________
3, Tier drives pricing strategy.

Store Performance Hierarchy

OUT004 (Medium, Tier 2) = 56% of all sales despite mid-pricing
OUT002 (Small, Tier 3) = lowest performance but essential rural coverage
Action: Replicate OUT004's volume model for expansion
_______
4, Product Strategy - Weight & Price Drive Sales

Weight is THE strongest predictor (coefficient 209 vs MRP at 19)

Every 1kg increase → +$209 revenue
Every $1 MRP increase → +$19 revenue
Action: Prioritize heavier, premium-priced items in inventory mix
___________
5, OUT004's success is volume-based, not format-based
_____________
6, Only 4 stores = can't generalize store characteristics
____________
7, Disclaimer: This can not predict for new store. That was not part of the assignment anyways but to predict for a new store I would need to:

- Collect multi-quarter data before expanding
- Keep Store_Id or store features in the model
- Use tree-based model (handles multicollinearity)
- Then input: "Rural + Food Mart + Small" → model predicts sales
even then it's still difficult to predict because they only have 4 stores. conclusions for a new store would likely be basic like; plant foodmarts in rural areas
  
