# 基礎建模& evaluation

## Decision tree regression
需透過預剪枝、後剪枝，來避免決策樹overfitting。

1. max_depth: 決策樹的最大深度。
2. min_samples_split: 每個節點分裂所需的最小數量。
3. min_samples_leaf: 每個節點所需包含得最少樣本數。
4. max_feature: 節點分裂時，所需考慮的feature數量。
