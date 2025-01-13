# **Locally Linear Embedding (LLE)**

This repository explores **Locally Linear Embedding (LLE)** as a powerful unsupervised learning technique for dimensionality reduction. It focuses on implementation, parameter tuning, comparisons with other techniques, and introduces a hybrid of Isomap and LLE, termed **IsoLEE**.

### **Notebook Highlights**
- **LLE Implementation**: Built from scratch with parameter flexibility.
- **Parameter Tuning**: Includes hierarchical methods and reconstruction error analysis.
- **Comparison**: Visual analysis against PCA, t-SNE, UMAP, and scikit-learn's LLE.
- **Fusion**: Integration of Isomap and LLE (IsoLEE).

### **Examples**
1. **Swiss Roll Dataset**  
   - Visualizes "unrolling" of the Swiss roll using LLE, IsoLEE, PCA, t-SNE, and UMAP.  
   - Compares smoothness and neighborhood preservation of embeddings.

2. **MNIST Dataset**  
   - Embeds high-dimensional handwritten digits into 2D.  
   - Annotates representative points and outliers for interpretability.

3. **Iris Dataset**  
   - Tests IsoLEE and LLE with varying neighborhood definitions.  
   - Visualizes clusters of species in reduced space.

4. **Semantic Word Embeddings**  
   - Applies LLE to pre-trained Word2Vec embeddings.  
   - Visualizes semantic relationships among words in a reduced 2D space.  

### **Usage**
The notebook offers examples and reusable functions, making it suitable for exploring LLE and its applications in dimensionality reduction and data visualization tasks.
