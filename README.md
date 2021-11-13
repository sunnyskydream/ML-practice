# ML-practice
Self practice based on <a href="https://www.books.com.tw/products/0010859473">this book</a>

<div>
<p>1.0 Supervised Learning</p>
<div>
  <p>1.1 Multiple Linear Regression 
   <ul>
      <li>from sklearn.linear_model import LinearRegression</li>
      <li>with regularization: Lasso, Ridge_from sklearn.linear_model import Ridge</li>
      <li>from sklearn.neighbors import KNeighborsRegressor</li>
      <li>data manipulation:auto.isin(['?']).sum(), auto = auto.assign(price = pd.to_numeric(auto.price))</li>
   <ul/>
  </p>
</div>
<div>
  <p>1.2 Logistic Regression
    <ul>
      <li>from sklearn.linear_model import LogisticRegression</li>
      <li>data manipulation:adult['fin_flg'] = adult['flg-50K'].map(lambda x:1 if x == ' >50K' else 0)</li>
      <li>normalization: from sklearn.preprocessing import </li>
       <ul/>
  </p>
</div>
<div>
  <p>1.3 k-Nearest Neighbors (kNN)
    <ul>
      <li>from sklearn.datasets import load_breast_cancer</li>
      <li>from sklearn.neighbors import KNeighborsClassifier</li>
    </ul>
  </p>
</div>
<p>1.4. Decision Tree<br/><p/>
   <p>1.5. Support Vector Machine (SVM)
    <ul>
      <li>from sklearn.svm import LinearSVC</li>
      </ul>
   </p>
      
<p>2.0 Unsupervised Learning<br/><p/>
<p>2.1 Cluster Analysis (k-means) 
    <ul>
      <li>from sklearn.datasets import make_blobs</li>
      <li>from sklearn.cluster import KMeans</li>
      <li>normalization: from sklearn.preprocessing import StandardScaler</li>
      <li>distance error / silhouette_avg</li>
      <li>cluster vs. feature heatmap</li>
     <ul/>
<p/> </div>
<div>
<p> 2.2 Principal Component Analysis<br/>
  <ul>
    <li>from sklearn.decomposition import PCA</li>
  </ul>
  </p> 
<p>2.3 Basket Analysis (Association Rule, application in Recommendation System)<br/> 
      2.3.1 Content Based Filtering<br/>
      2.3.2 Collaborative Filtering <br/>
      <blockquote>a. Memory-Based: User-User Similarity, Item-Item Similarity<br/>  
        b. Model-Based:k-Nearest Neighbors(KNN), Matrix Facorization: Singular Value Decomposition (SVD)</blockquote><br/>
<p>3.0 <a href="https://xijunlee.github.io/2017/06/03/%E9%9B%86%E6%88%90%E5%AD%A6%E4%B9%A0%E6%80%BB%E7%BB%93/">Ensemble: Bagging, Boosting, Stacking</a><br/><p/>
<p>3.1 Bagging: Random Forest<br/><p/>
<p>3.2 Booosting: AdaBoost (adaptive Boosting), GBDT (Gradient Boosting Decision Tree), XGBoost<p/></div>
  
