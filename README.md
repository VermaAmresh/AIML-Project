Spam Email Detection System

This project is a simple machine learning application that classifies emails as spam or not spam. It was built to understand how text classification works in practice and how a trained model can be used in a real-world scenario.

The approach is intentionally kept simple, focusing on the core idea — taking email text as input, processing it, and predicting the result.

Features


Takes email text as input
Performs basic text preprocessing
Converts text into numerical form using TF-IDF
Uses a trained model for classification
Outputs whether the email is spam or not spam


Project Structure


Spam_Email_Classifier/
│
├── data/
│   └── spam.csv
│
├── models/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── preprocess.py
├── train.py
├── email_checker.py
└── requirements.txt



Setup and Execution

First, navigate to the project folder:

cd Spam_Email_Classifier

Install the required dependencies:

pip install -r requirements.txt

Train the model:

python train.py

Run the email checker:

python email_checker.py
How to Use

Run the program in the terminal and enter the email text when prompted.
The model will classify the input as spam or not spam.
You can continue testing multiple emails if needed.

Sample Inputs

Spam example:

Congratulations! You have won a free prize

Not spam example:

Hi, are we meeting tomorrow for the project
What I Learned
Basics of text preprocessing
TF-IDF vectorization
Naive Bayes classification
Saving and loading trained models
Building a simple command-line tool
Notes

This is a beginner-level project created for learning purposes.
The model's accuracy depends on the dataset used for training.
Performance can be improved by using more data and advanced techniques.

Author

Amresh Verma

This project helped build a clear understanding of how machine learning models can be applied to text classification problems in a practical way.