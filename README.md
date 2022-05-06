
# # Problem Description
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe a term deposit (variable y).

<h2> :floppy_disk: Project Files Description</h2>

<p>This repository includes 1 colab notebook (.ipynb) file and 1 pdf file of project presentation. </p>
<h4>About Files:</h4>
<ul>
<li><b>NYC Taxi Trip Time Prediction Capstone Project.ipynb</b> - This file includes Features description, exploratory data Analysis, feature engineering, feature scaling and implemented algorithms for eg. <b>KNN, Random Forest and LGBM.</b></li> 
 <li><b>NYC_PPT</b> -  This is a power point presentation file of a project. It includes various visualaized plots of EDA using <b>Seaborn and Matplotlib</b>. The result chart of various implemented algorithms.</li>
  

![------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Summary</h2>
<p align="justify">The Bank data contains 45211 records and 17 columns. It contains 7 numerical (int) and 10 Categorical (object) datatypes columns. After initial data exploration, we didn’t find any duplicated records and missing values in any column. The target variable has highly imbalanced distribution. This was our main challenge. In classification problems we need to keep in mind that only Accuracy score doesn’t give true picture about classification. Accuracy score usually
gives higher weightage to the majority class. Some features contained many categorical values and those values merged and new feature added to the dataset. Some numerical feature values converted into range of values for model building and interpretability. Using SMOTE the given target variable balanced for model. In this project we have implemented different algorithms KNN, Random Forest Classifier and LightGBM. LightGBM with duration feature got 0.41 precision and 0.81 Recall score. For a real world prediction, the duration feature dropped and LightGBM without duration feature got 0.46 precision and 0.39 Recall score. Te AuC score obtaines is 0.76 on test data<b/></p>

![------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Saurabh Funde  | Avid Reader | Data Science enthusiast |

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saurabhfunde/)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@saurabh.f)

 <h2>Contributors:</h2>
  <li><p>Akanksha Agarwal</p>
      <p>Github: https://github.com/agarwal-akanksha</p>
  <li><p>GaneshKumar Patel</p>
      <p>Github: https://github.com/GaneshkumarPatel</p>
  <li><p>Yaman Saini</p>
      <p>Github: https://github.com/yaman9675</p>
  <li><p>Sanjay Kumar</p>
      <p>Github: https://github.com/sanjaymkr</p>
   

![------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2>Algorithm References:</h2>
<ul>
  <li><p>KNN</p>
      <p>Link: https://towardsdatascience.com/an-intuitive-guide-to-knn-with-implementation-fc100bf29a6f</p>
  </li>
  <li><p>LGBM</p>
      <p>Link: https://towardsdatascience.com/how-to-beat-the-heck-out-of-xgboost-with-lightgbm-comprehensive-tutorial-5eba52195997</p>
  </li>
  <li><p>Random Forest</p>
      <p>Link: https://www.analyticsvidhya.com/blog/2021/10/an-introduction-to-random-forest-algorithm-for-beginners/</p>
  </li>
</ul>
 
 <h2>Data Source</h2>
  <li><p>Kaggle</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
