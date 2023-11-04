# Resume-Selection-using-MLResume Selection Using Machine Learning

This project focuses on using machine learning techniques to classify resumes into two categories: flagged or not flagged. It utilizes Python libraries and tools to preprocess text data, build a machine learning model, and evaluate its performance.

# Installation

Make sure to install the required Python libraries by running the following commands:

pip install pandas

pip install numpy

pip install matplotlib

pip install seaborn

pip install --upgrade pip

pip install nltk

pip install gensim

pip install sklearn

pip install wordcloud



# Getting Started

To start working with this project, follow these steps:

Clone the repository: (https://github.com/jmdharshana/Resume-Selection-using-ML/)
Navigate to the project directory: cd your_repository
Run the provided Python script: python resume_selection.py


# Dataset

The project uses a dataset named resume_data.csv, which contains resume text and corresponding class labels. This dataset is loaded using the Pandas library.


# Data Preprocessing

The text data is cleaned by removing unnecessary characters and line breaks.
Stop words and common words are removed from the text data using NLTK's stopwords.
Text data is tokenized and processed to prepare it for machine learning.


# Exploratory Data Analysis

The distribution of the class labels (1 for flagged and 0 for not flagged) is visualized using a count plot.
Word clouds are generated to provide a visual representation of the most common words in each class of resumes.


# Model Building

The text data is converted into numerical features using Count Vectorization.
A Multinomial Naive Bayes classifier is trained on the data to classify resumes as flagged or not flagged.


# Model Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
Confusion matrices are plotted to visualize the model's performance on both training and test data.


# Results

The results of the model, including accuracy, F1-score, precision, and recall, are displayed to assess its performance on the test dataset.


# Contributing

Contributions, suggestions, and feedback are welcome! If you'd like to contribute to this project, feel free to submit a pull request.


# License

This project is licensed under the MIT License. For details, see the LICENSE file in the repository.

Now, you can create a README.md file in your GitHub repository, paste this content into it, and customize it as needed. Don't forget to add the actual text of the MIT License in a file called "LICENSE" in your repository if it's not already there.




