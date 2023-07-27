# sklearn-classification
Various examples of machine learning classification code made with SKLearn in Google Colab. Made during an Alura course.
<br><br>

## Dog and pig classification
LinearSVC model for classification between dogs and pigs based on the array of their features, them being: having long fur, short legs and barking.
<br><br>

## Buying prediction
LinearSVC model made to predict if a product is going to be bought based on the previous website pages the user visited.
<br><br>
This time we used Pandas and an online database to train and test the model, learning to split the train and test data with the native train_test_split function of SKLearn, finalizing with the use of the stratify property to have a consistent ratio of 2:1 of negative and positive results in both test and train labels.
<br><br>

## Project finishing prediction
LinearSVC and SVC model to predict if a project of x hours and price is going to get finished by a developer.
<br><br>
Trained with an online database. The two models were tested and had their decision boundary plotted, perfecting the SVC model with preprocessing.

### Technologies used:
- Pandas
- Seaborn
- NumPy
- MatPlotLib
<br><br>

## Car selling prediction
LinearSVC, SVC and Decision Tree comparison of a model that predicts if a car will be sold, based on its age, price and km per year.
<br><br>
The online database was loaded and formatted for best use. This time the baseline algorythm was not done manually, now being applied with the DummyClassifier function from SKLearn, while also plotting the decision tree in a graph to visualize it fully.

### Technologies used:
- Pandas
- NumPy
- Graphviz
