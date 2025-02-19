# recommend-proposal

### Multi-strategy Fusion Recommendation

| **Strategy Type**       | **Applicable Scenarios**          | **Implementation Method**                                   |
|-------------------------|----------------------------------|-----------------------------------------------------------|
| Content-based Recommendation | Cold start for new users         | Depending on the market target category/sub-category, matching courses with course target audience          |
| Collaborative Filtering  | Users with distinct group traits | Use users' transactions/cart/searches/completion to draw user avatar, we can build embeddings and use ai models for us to get recommendations from our embeddings    |
| Knowledge Graph Recommendation | Recommendations for courses added to package | Build learning paths, we can use apriori algorithm to get frequent itemsets across all combinations https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/ |
| Real-time Recommendation | Users with explicit search queries in the current session | Implement instant keyword matching using Elasticsearch (migrate from algolia)     |
