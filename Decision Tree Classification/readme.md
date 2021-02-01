# Classification using Decision Tree
<li>The dataset contains information from teachers' project applications to DonorsChoose.org including teacher attributes, school attributes, and the project proposals including application essays.</li>
<li>- Download data from: https://www.kaggle.com/c/donorschoose-application-screening/data</li>
<li>- Download Glovmodel from: https://nlp.stanford.edu/projects/glove/</li>

# Models
- [Decision Tree](https://github.com/Devarshi-Chauhan/projects/blob/master/Decision%20Tree%20Classification/Decision%20Tree.ipynb)
- [Gradient Boosted Decision Tree]()
<li>The goal of the competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school.</li>
<li> Data is first divided into numerical, catagorical and text features and processed accordingly. TFIDF and TFIDF-W2V vectorizers were used to handle text features(Glove model is used). Categorical features were processed threw onehot encoding, but for GBDT Response encoding is used. Numerical features were standardized before processing.</li>
