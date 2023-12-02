# NLP Class Project - Named Entity Recognition in E-commerce
Welcome to our NLP class project, where we delve into the fascinating realm of Named Entity Recognition (NER) in the context of e-commerce. This project serves as a vital component of our NLP coursework, guided by Professor JD Osborne.

## Project Overview
Our project focuses on addressing a real-world NLP challenge by applying Named Entity Recognition (NER) to e-commerce data. We are inspired by eBay's Annual University Challenge and aim to bring the practical application of NER to the forefront.

## The Challenge
Named Entity Recognition (NER) is a fundamental NLP task that plays a vital role in various language understanding tasks. This challenge is tailored to eBay's unique setting and involves applying NER specifically to eBay listing titles. Examples of NER labeling in listing titles may include identifying brand names, product names, and other relevant information.

The challenge revolves around accurately extracting and labeling aspects within the dataset of item titles. An interesting aspect of this challenge is that not all titles contain the same aspects, making it a puzzle to determine which aspect is present in a given title.

## Dataset
Our dataset comprises 10 million randomly selected, unlabeled item titles from eBay Germany, all related to "Athletic Shoes" categories. Within this dataset, we have 10,000 labeled item titles, indicating that aspects have been successfully extracted.

These labeled item titles are divided into three categories:

Training set (5,000 records)
Quiz set (2,500 records)
Test set (2,500 records)
The training set includes aspects for each item title, while the quiz set does not. Both sets are used for leaderboard scoring. The complete 10 million title dataset, along with the training and quiz sets, will be made available when the project commences.

The test set is vital for determining the winners of the project. It will only be distributed to the top-scoring teams after the project's completion. Similar to the quiz set, aspects will not be provided for the test set.
 
### Setting Up a Virtual Environment and Installing Project Dependencies

Follow these steps to set up a virtual environment for an existing project and install dependencies from a requirements file:

Open a Terminal or Command Prompt:

Navigate to the Project Directory, Use the cd command to navigate to your project directory.

`cd path/to/my_project`

### Create a Virtual Environment:

If you haven't already created a virtual environment, follow these steps to create one:


Run the following command to create a virtual environment named "myenv" (you can choose a different name) but First, ensure you have the virtualenv package installed by running:

`pip install virtualenv
`

Then, create a virtual environment (e.g., "myenv") with this command:

`python -m venv myenv
`

Activate the virtual environment based on your operating system:

**On Windows:**

`myenv\Scripts\activate
`

**On macOS and Linux:**

`source myenv/bin/activate
`

After activation, your command prompt will reflect the virtual environment's name (e.g., "(myenv)"). Install Project Dependencies from a Requirements File, Use pip to read the requirements file and install the packages:

`pip install -r requirements.txt
`

This command will install all the packages listed in the requirements.txt file into your virtual environment.

#### Work on the Project:

Your virtual environment is now active, and you can work on the project using the installed dependencies. Any packages you install or update will be isolated from your system's Python environment.

#### Deactivate the Virtual Environment:

When you're done working on your project, you can deactivate the virtual environment, returning you to your system's Python environment.

`deactivate`

##### Install packages in your conda environment.

Create your conda environment and ensure you have the following packages and dependencies before running project. (Virtual Environment and Google Collab were used by team members for the project). In Google collab run `!pip install {package}`

packages:
pandas
nltk
matplotlib
collections  
seaborn 
wordcloud 
random
pytorch-transformers
seqeval
seqeval.metrics
torch.nn.functional
sklearn
numpy

dependencies:
nltk.tokenize.word_tokenize
nltk.tokenize.sent_tokenize
nltk.corpus.stopwords
matplotlib.pyplot
Counter
WordCloud
os
f1_score
classification_report
accuracy_score
metrics
confusion_matrix
