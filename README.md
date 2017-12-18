# SpamSmsClassification-using-NLP
The SMS Spam Collection (text file: smsspamcollection) has a total of 4,827 SMS legitimate messages (86.6%) and a total of 747 (13.4%) spam messages.

# Installation:
To run this notebook interactively:

1. Download this repository in a zip file by clicking on this link or execute this from the terminal: git clone
2. Install virtualenv.
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with virtualenv env.
4. Activate the environment with source env/bin/activate
5. Install the required dependencies with pip install -r requirements.txt.
6. Execute ipython notebook from the command line or terminal.
7. Click on Titanic.ipynb on the IPython Notebook dasboard and enjoy!
8. When you're done deactivate the virtual environment with deactivate.

# Dependencies:

1. NumPy
2. pandas
4. re
5. nltk
6. sklearn
7. Matplot

# Goal for this Notebook:

Show a simple example of Text analysis of the Retra. Review in Python using a full complement of PyData utilities. This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

This shows following:

1. Importing the libraries
2. Importing the dataset
3. EDA
4. Cleaning the texts
5. Creating the Bag of Words model
6. Splitting the dataset into the Training set and Test set
7. Fitting Naive Bayes to the Training set
8. Predicting the Test set results
9. Making the Confusion Matrix
