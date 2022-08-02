# Naive-Bayes-Implementation-Assignemnt
**About the assignemnt:** The first part was to plot the mean images of each class and the confusion matrix of the classifier, of the MNIST dataet- MNIST dataset - dataset of handwritten digits containing grayscale image data with fixed-shapes.
The Seccond part and the imporant one is to implemnt the Naive Bayes model (instead of using Skit-learn built-in model) in order to predict the digit in a given image. 



**Classifing Text Documents using Multinomial Naive Bayes - Main Parts:**
1. Implement Naive Bayes Model using the class NaiveBayes that contains the following methods:
fit: This functions "trains" the model by calculating the conditional probability and the priors. 
predict_log_proba: this method returns "docs" - a list. each entry in the list represents a document and each document has 20 cells contain the log probability for each label/
predict: this method accepts a document and predicts the probability for the label.

2. Load "fetch_20newsgroup dataset" - this dataset comprises around 18000 newsgroups `posts on 20 topics split in two subsets: one for training (or development) 
and the other one for testing (or for performance evaluation).

3. Apply the implemented model on the data 

4. Model Evaluation - compare the accuracy over the test data. 

5. Compare to tf-idfVectorizer prepocessing 

6. Plot Learning curve - check overfitting

7. Optimize performance - Hyper parameters, Tuning
