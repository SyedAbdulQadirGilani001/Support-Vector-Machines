### Loading Libraries

To start using SVM, we need to load necessary libraries. Think of libraries like toolboxes. We import pandas for data handling, numpy for calculations, and matplotlib/seaborn for visualization. For SVM, we import SVC (Support Vector Classifier) from scikit-learn.


#### Preparing Data

Next, we load our dataset. In this case, it's the famous Iris flower dataset. We split the data into features (X) and target (y), which is the type of Iris flower. We drop the 'species' column to create X and use 'species' as y.


##### Training SVM Model

Now, we split our data into training and testing sets (80% for training and 20% for testing). We create an SVM model with a radial basis function kernel and train it using our training data. This is where the magic happens - SVM finds the best hyperplane to separate our data.


###### Making Predictions

After training, we use our model to predict the type of Iris flower for our test data. We compare these predictions with actual values to evaluate our model's performance. We use a confusion matrix and classification report to see how well our model did.


###### Evaluating Performance

Finally, we visualize our confusion matrix as a heatmap to better understand our model's performance. We check accuracy, precision, and recall to see if our SVM model is reliable. If it is, we can use it to classify new, unseen data!
