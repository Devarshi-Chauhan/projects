# Classification using Decision Tree
<li>The dataset contains information from teachers' project applications to DonorsChoose.org including teacher attributes, school attributes, and the project proposals including application essays.</li>
- Download data from: https://www.kaggle.com/c/donorschoose-application-screening/data
- Download Glovmodel from: https://nlp.stanford.edu/projects/glove/

# Moels
- [Decision Tree]()
- [Gradient Boosted Decision Tree]()
<li>The goal of the competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school.</li>
<li> Data is first divided into numerical, catagorical and text features and processed accordingly. TFIDF and TFIDF-W2V vectorizers were uded to handle text features(Glove model is used). Catagorical features were processed threw onehot encoding, but for GBDT Response encoding is used. Numerical features were standardized befor processing.</li>
