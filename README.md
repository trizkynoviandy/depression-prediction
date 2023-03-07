# Depression Prediction

This project uses natural language processing and machine learning algorithms to predict if a user is depressed based on their text post. The goal of this project is to develop a model that can accurately identify if a user is suffering from depression, which could have important implications for mental health interventions and support.

## Dataset
The dataset for this project is obtained from [Kaggle](https://www.kaggle.com/datasets/infamouscoder/depression-reddit-cleaned). The raw data is collected through web scrapping Subreddits and is cleaned using multiple NLP techniques. The data is only in English language. It mainly targets mental health classification. The dataset includes a total of 7731 posts, with 3900 negative post (not depressed) and 3831 positive post (depressed).

## Methodology

The text data was preprocessed by removing stop words, converting all text to lowercase, and stemming the words. The data was then split into training and testing sets, with 80% of the data used for training and 20% used for testing. Several machine learning algorithms were tested on the preprocessed data, including Decision Tree, KNN, Logistic Regression, SVC, and XGBoost. The performance of each model was evaluated using accuracy, precision, recall, and F1-score.

## Results

The SVM model performed the best, achieving an accuracy and f1-score of 96.2% on the testing set.

## Conclusion

This project demonstrates the potential for using natural language processing and machine learning to identify depression in social media posts. The SVM model performed well, indicating that it may be useful in identifying users who are at risk of depression and providing them with appropriate support and resources. However, further research is needed to refine the model and ensure that it is effective across different populations and platforms.

## Requirements

In order to run the python script and notebook, you will need to have the following packages installed:

* matplotlib
* numpy
* pandas
* scikit-learn

## Disclaimer

The information provided in this project is for educational and informational purposes only. The predictions made by the machine learning model are based on the data provided and may not be accurate for all cases. This model is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified healthcare provider with any questions you may have regarding a medical condition. The creators of this project make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability with respect to the project or the information, products, services, or related graphics contained in the project for any purpose. Any reliance you place on such information is therefore strictly at your own risk. In no event will the creators be liable for any loss or damage including without limitation, indirect or consequential loss or damage, or any loss or damage whatsoever arising from loss of data or profits arising out of, or in connection with, the use of this project.

