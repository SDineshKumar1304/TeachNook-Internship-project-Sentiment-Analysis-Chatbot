# Name : Dineshkumar S
Sentiment Analysis with Support Vector Machine (SVM)
# Overview (Teach Noook Pvt ltd Simple Internship Task)
This project implements a sentiment analysis model using a Support Vector Machine (SVM) with a linear kernel. The model is trained on a dataset containing examples of positive, negative, and neutral sentiments. The sentiment analysis is performed using a TF-IDF vectorizer to convert text data into numerical features.

# Requirements
Make sure you have the required libraries installed before running the code. You can install them using:

pip install nltk scikit-learn


# Clone the repository:
git clone <repository-url>

# Navigate to the project directory:
cd <project-directory>

# Run the script:
python sentiment_analysis.py

# Dataset
The sentiment dataset consists of manually labeled examples, including positive, negative, and neutral sentiments. The dataset is split into training and testing sets to evaluate the model's performance.

# Model Training
The sentiment analysis model is a pipeline that includes a TF-IDF vectorizer and an SVM classifier with a linear kernel. The model is trained on the training dataset to learn the relationships between the text features and their corresponding sentiment labels.

# Evaluation
The model's performance is evaluated using various metrics, including accuracy, a classification report, and a confusion matrix. These metrics provide insights into how well the model generalizes to unseen data and its ability to classify sentiments accurately.

# Additional Notes
The dataset is extended with additional examples to ensure a diverse set of training and testing instances.
You can experiment with different models, hyperparameters, or feature extraction techniques to further enhance the sentiment analysis performance.
Feel free to explore and modify the code to suit your specific requirements. If you have any questions or suggestions, please don't hesitate to reach out.

Happy sentiment analyzing!
