# ML_Project57-Xgboost_bow_tfidf

### XgBoost BOW TFIDF Project

### Overview
This project focuses on building a model to predict whether a pair of questions from the Quora dataset represents duplicate questions or not. It uses different text representation techniques such as Bag-of-Words (BOW) and Term Frequency-Inverse Document Frequency (TF-IDF) with XGBoost, a popular gradient boosting algorithm, to achieve this task. The project compares the performance of these techniques based on different levels of text representation.

### Project Structure
The project follows the below structure:
##### Data Loading and Preprocessing:
The Quora dataset (quora_train.csv) is loaded into a pandas DataFrame.

Data cleaning is performed to remove any null values.

##### Exploratory Data Analysis (EDA):
Basic statistics and visualizations are generated to understand the distribution of duplicate and non-duplicate questions.

##### Text Preprocessing:
The questions are preprocessed by applying various text cleaning techniques such as removing punctuation, converting text to lowercase, and replacing special characters.

##### Model Building:
Different text representation techniques (BOW, TF-IDF) are applied to represent the questions.

XGBoost classifier is trained using these representations to predict question duplicates.

##### Model Evaluation:
The trained models are evaluated using metrics such as F1-score, precision, recall, and accuracy.

Performance comparison is made between different text representation techniques.

##### Results Analysis:
The results are analyzed to understand the effectiveness of each text representation technique and the XGBoost model.

### How to Run
Clone Repository: Clone this repository to your local machine.

Install Dependencies: Ensure all dependencies mentioned in the requirements.txt file are installed.

Download Dataset: Download the Quora dataset file (quora_train.csv) and place it in the project directory.

Run Notebook: Open and run the xgboost_bow_tfidf.ipynb notebook using Jupyter Notebook or any compatible platform.

Review Results: After running the notebook, review the model performance metrics and analysis to understand the effectiveness of different text representation techniques.

### Notes

Experiment with different hyperparameters of the XGBoost model to optimize performance further.

Explore additional text preprocessing techniques or feature engineering methods to improve model accuracy.

Customize the notebook to include additional visualizations or analyses based on specific project requirements.

Feel free to reach out for any questions or assistance.

### Acknowledgements
This project uses the Quora dataset, which contains pairs of questions labeled as duplicate or non-duplicate.

Special thanks to the XGBoost library for providing an efficient implementation of the gradient boosting algorithm.

Credits to the scikit-learn library for providing tools for text preprocessing and model evaluation.
