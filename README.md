# 🍲 Food Networks Project

## ES:404 Networks and Complex Systems

This project explores multiple food-related networks to uncover structural insights and patterns in recipes and ingredients using network science techniques. We build and analyze four different networks to understand co-occurrence, similarity, and centrality across the culinary domain.

## 🧰 Libraries Used


- **NumPy**: For numerical operations and data manipulation.  
- **Pandas**: For loading and processing tabular data.  
- **Seaborn & Matplotlib**: For statistical data visualization.  
- **NetworkX**: To construct and analyze networks (graphs).  
- **cuGraph** *(optional)*: For GPU-accelerated graph computations.  
- **Powerlaw**: For fitting and analyzing power-law distributions.  
- **SciPy**: For sparse matrix operations and eigenvalue computations.  
- **Community (python-louvain)**: For community detection using the Louvain method.  
- **Centralities (custom module)**: Custom or external module for computing various centralities.  
- **Collections & Itertools**: For efficient data handling and iteration.  
> NetworkX is used for initial prototyping and visualization, while cuGraph is used to speed up heavy computations using GPU.

---

## 📂 Networks Studied

1. **Ingredient Co-Occurrence Network**  
   - Nodes: Ingredients  
   - Edges: Two ingredients that appear in the same recipe  
   - Goal: Identify clusters of ingredients and central ingredients across recipes

2. **Recipe-Recipe Similarity Network**  
   - Nodes: Recipes  
   - Edges: Similarity between recipes based on shared ingredients  
   - Goal: Detect groups of similar recipes and understand common structures

3. **User-Recipe Bipartite Network** *(Not included in final analysis)*  
   - Nodes: Users and Recipes  
   - Edges: A user has interacted with/saved/cooked a recipe

4. **Recipe-Ingredient Bipartite Network** *(Not included in final analysis)*  
   - Nodes: Recipes and Ingredients  
   - Edges: A recipe contains an ingredient

> 🔍 Note: Only the first two networks are analyzed in this report. The bipartite networks were not used in the final analysis.

---

## 📊 Methods Used

- Graph construction using NetworkX
- GPU-accelerated algorithms using cuGraph
- Centrality analysis (degree, closeness, betweenness)
- Clustering coefficient computation
- Community detection using the Louvain algorithm
- Network visualization with Matplotlib and NetworkX

---

## 📦 Dataset

The dataset used in this project comes from a Kaggle competition. You can download it from the following link:

[Kaggle Dataset Link]([https://www.kaggle.com/your-dataset-link](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions))


