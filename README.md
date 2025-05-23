
# MediChoice - Disease Detection and Medicine Recommendation System
MediChoice is a web application that uses machine learning algorithms to detect diseases from symptoms and recommend medicine. The application uses two machine learning models, both of which use decision tree algorithms.

### Installation
To run the application, you will need to install the many packages, some main one like:

* Flask
* scikit-learn
* pandas
* numpy

To install these packages, you can use the following command:

`pip install -r requirements.txt`

### Usage
To run the application, navigate to the Samudini directory and run the following command:

`python app.py`

This will start the Flask development server, and the application will be accessible at http://localhost:5000.

### Machine Learning Models
The application uses two machine learning models to detect diseases and recommend Ayurvedic medicine:

1. Decision Tree Classifier: This model is trained on a dataset of symptoms and their corresponding diseases. Given a set of symptoms, the model predicts the most likely disease.

2. Decision Tree Classifier: This model is trained on a dataset of diseases and their corresponding Ayurvedic medicines. Given a disease, the model recommends the most effective Ayurvedic medicine.

### Dataset
The datasets used to train the machine learning models are available in the dataset directory. The data.csv file contains a list of symptoms and their corresponding diseases, and the Drug prescription Dataset.csv file contains a list of diseases and their corresponding medicines.
