Aditya Thalluri
Sharat Tangella
Manideep Potluri
CS 429/529
Project 3

In this project we are implementing the Logistic Regression, Random Forest, SVM, XGBoost and CNN classifiers on various Audio Data Representations such as MFCC, STFT, PCA and Spectrograms.

We used the FMA dataset for this project.

Code for the project is available as the single jupyter notebook AudioCategorization.ipynb.

Unzip the dataset and move the notebook into the same folder containing Datasets train, test and csv files train.csv, test_idx.csv. Notebook expects those folders and csv files to be in the same directory.

Open the AudioCategorization Jupyter Notebook and Run All Cells in the Cell Tab.

For each Data Representation, we get two csv files containing the predictions on test data from each of two classifiers compared on that Data Representation.

Also, the confusion matrix, accuracies, confidance intervals for each pair of classifers are plotted. Their Results along with Bias are discussed in the same section.

Future enhancements has been suggested.
