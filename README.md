# ML-practice
Self practice based on <a href="https://www.books.com.tw/products/0010859473">this book</a>

<div>
<p>1.0 Supervised Learning</p>
<div>
  <p><a href="https://github.com/sunnyskydream/ML-practice/blob/main/1_1_Supervised_Learning_Multiple_Linear_Regression.ipynb">1.1 Multiple Linear Regression</a> 
   <ul>
      <li>from sklearn.linear_model import LinearRegression</li>
      <li>with regularization: Lasso, Ridge_from sklearn.linear_model import Ridge</li>
      <li>from sklearn.neighbors import KNeighborsRegressor</li>
      <li>data manipulation:auto.isin(['?']).sum(), auto = auto.assign(price = pd.to_numeric(auto.price))</li>
   <ul/>
  </p>
</div>
<div>
  <p><a href="https://github.com/sunnyskydream/ML-practice/blob/main/1_2_Supervised_Learning_Logistic_Regression.ipynb">1.2 Logistic Regression</a> 
    <ul>
      <li>from sklearn.linear_model import LogisticRegression</li>
      <li>data manipulation:adult['fin_flg'] = adult['flg-50K'].map(lambda x:1 if x == ' >50K' else 0)</li>
      <li>normalization: from sklearn.preprocessing import StandardScaler </li>
       <ul/>
  </p>
</div>
<div>
  <p><a href="https://github.com/sunnyskydream/ML-practice/blob/main/1_3_Supervised_Learning_k_NN(k_nearest_neighbors).ipynb">1.3 k-Nearest Neighbors (kNN)</a>
    <ul>
      <li>from sklearn.datasets import load_breast_cancer</li>
      <li>from sklearn.neighbors import KNeighborsClassifier</li>
    </ul>
  </p>
</div>
<div>
  <p><a href="https://github.com/sunnyskydream/ML-practice/blob/main/1_4_Supervised_Learning_Decision_Tree.ipynb">1.4. Decision Tree</a><br/><p/>
     <ul>
      <li>one-hot encoding/pd.get_dummies(mushroom[['gill-color']])</li>
      <li>flag target 0/1: mushroom_dummy['flg'] = mushroom['classes'].map(lambda x:1 if x =='p' else 0)</li>
      <li>entropy, information gain</li>
      <li>from sklearn.tree import DecisionTreeClassifier</li>
      <li>import graphviz, pydotplus, tree</li>
     </ul>
  </p>
</div>
   <p><a href="https://github.com/sunnyskydream/ML-practice/blob/main/1_5_Supervised_Learning_Support_Vector_Machine_(SVM).ipynb">1.5. Support Vector Machine (SVM)</a>
    <ul>
      <li>from sklearn.svm import LinearSVC</li>
      </ul>
   </p>
      
<p>2.0 Unsupervised Learning<br/><p/>
<p><a href="https://github.com/sunnyskydream/ML-practice/blob/main/2_1_B_Unsupervised_Learning_Cluster_Analysis_(k_means).ipynb">2.1 Cluster Analysis (k-means)</a> 
    <ul>
      <li>from sklearn.datasets import make_blobs</li>
      <li>from sklearn.cluster import KMeans</li>
      <li>normalization: from sklearn.preprocessing import StandardScaler</li>
      <li>distance error / silhouette_avg</li>
      <li>cluster vs. feature heatmap</li>
     <ul/>
<p/> </div>
<div>
<p> <a href="https://github.com/sunnyskydream/ML-practice/blob/main/2_2_Unsupervised%20Learning_Principal_Component_Analysis.ipynb">2.2 Principal Component Analysis</a><br/>
  <ul>
    <li>from sklearn.decomposition import PCA</li>
  </ul>
  </p> 
<p><strong>Recommendation System</strong><br/>
  item-item: association rule<br/>
  user-user: similarity distance- cosine, euclidean,manhattan/Jaccard similarity)=> K-means, KNN<br/>
  user-item: Matrix Facorization: Singular Value Decomposition (SVD)
  <a href="[https://github.com/sunnyskydream/ML-practice/blob/main/2_3_Unsupervised_Basket_Analysis.ipynb](https://static.googleusercontent.com/media/research.google.com/zh-TW//pubs/archive/45530.pdf)">deep learning</a>
<a href="https://github.com/sunnyskydream/ML-practice/blob/main/2_3_Unsupervised_Basket_Analysis.ipynb">2.3 Basket Analysis (Association Rule)</a><br/> 
      2.3.1 Content Based Filtering<br/>
      <a href="https://ithelp.ithome.com.tw/articles/10219511">2.3.2 Collaborative Filtering</a><br/>
      <blockquote>a. Memory-Based: User-User Similarity, Item-Item Similarity<br/>  
        b. Model-Based:k-Nearest Neighbors(KNN), Matrix Facorization: Singular Value Decomposition (SVD)</blockquote>
       <a href="https://ithelp.ithome.com.tw/articles/10220962">2.3.3 Hybrid</a>
</p> 
<p>3.0 <a href="https://xijunlee.github.io/2017/06/03/%E9%9B%86%E6%88%90%E5%AD%A6%E4%B9%A0%E6%80%BB%E7%BB%93/">Ensemble: Bagging, Boosting, Stacking</a><br/><p/>
<a href="https://github.com/vsmolyakov/experiments_with_python/blob/master/chp01/ensemble_methods.ipynb">other reference</a><br/>
<p>3.1 Bagging: Random Forest<br/><p/>
<p>3.2 Booosting: AdaBoost (adaptive Boosting), GBDT (Gradient Boosting Decision Tree), XGBoost<p/></div>
  
