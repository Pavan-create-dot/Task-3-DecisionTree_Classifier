# DS_Task3
A comprehensive guide and implementation of a Decision Tree Classifier. This project demonstrates the end-to-end workflow for training and evaluating a model on a real-world dataset, including preprocessing, visualization, and performance metrics. Perfect for those looking to understand decision tree concepts in data science.
## Overview 📝
Welcome to the DS_Task3 repository! This project demonstrates a comprehensive data science workflow, including data preprocessing, exploratory data analysis (EDA), machine learning modeling, and result evaluation. The primary goal is to classify sentiments in textual data and analyze the performance of the classification model. 🔥

## Dataset 📊
The project utilizes two datasets:
1. **Training Dataset**: Used for building the sentiment classification model.
2. **Validation Dataset**: Used to evaluate the model's performance and compare predicted sentiments with actual sentiments.

### Data Details
The datasets consist of the following key features:
- **text**: The main text data containing user comments or tweets.
- **cleaned_text**: Preprocessed version of the `text` column.
- **sentiment**: Sentiment label (Positive, Negative, Neutral).

The training dataset is used to develop the model, while the validation dataset is used to test and refine the predictions. 🧹

## Tools and Libraries 🛠️
The following tools and libraries are used:
- **Python 3.x**: The programming language used. 🐍
- **pandas**: For data manipulation and cleaning. 📊
- **re**: For text preprocessing using regular expressions. ✂️
- **TextBlob**: For sentiment analysis. 📜
- **matplotlib** & **seaborn**: For data visualization. 📈
- **wordcloud**: To create a word cloud visualization. ☁️

## What does the code do? 🤖
The project is divided into several major steps:

### 1. Data Loading
The datasets are loaded from CSV files into pandas DataFrames for analysis and processing.

### 2. Data Preprocessing
- Filling missing values in the `text` column.
- Cleaning the text data by removing URLs, mentions, hashtags, and non-alphabetic characters.
- Lowercasing and stripping unnecessary whitespace from the text.

### 3. Sentiment Classification
- Sentiments are classified using `TextBlob` polarity scores:
  - Positive polarity -> Positive sentiment.
  - Negative polarity -> Negative sentiment.
  - Neutral polarity -> Neutral sentiment.
- The results are stored in a new column `sentiment` (for training data) and `Predicted_Sentiment` (for validation data).

### 4. Visualization
- Bar plots are used to visualize sentiment distributions in both datasets.
- Word clouds are generated to highlight common words in positive sentiments.

### 5. Evaluation
- If the validation dataset contains actual sentiment labels, a comparison between actual and predicted sentiments is conducted using a confusion matrix.
- Performance metrics are analyzed to assess the model's accuracy and effectiveness.

## How to Run 🚀
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/DS_Task3.git
   cd DS_Task3
   ```
2. Install the required libraries:
   ```bash
   pip install pandas textblob matplotlib seaborn wordcloud
   ```
3. Ensure the dataset files are in the correct directory.
4. Run the main code:
   ```bash
   python DS_Task3.py
   ```
5. Visualizations and evaluation metrics will be displayed as part of the script output.

## Handling Directory Issues ⚠️
- Ensure the file paths for `training_data_path` and `validation_data_path` are correctly set in the script.
- Place the datasets in the specified directory or update the script with the correct paths.

## Sample Video 🎥
Here’s a quick demo of the workflow and visualizations:
- *Task-3-Demo.mp4*

## Desired Output 🎯
The project produces the following outputs:
1. Enhanced datasets with additional columns for cleaned text and predicted sentiments.
2. Visualizations:
   - Sentiment distributions in training and validation datasets.
   - Word cloud for positive sentiments.
3. Evaluation metrics (if actual sentiments are available in the validation dataset).

## Conclusion 🎉
By following this project, you will learn to:
- Preprocess textual data efficiently. ✂️
- Perform sentiment analysis using `TextBlob`. 📜
- Visualize sentiment distributions and common words. ☁️
- Evaluate model performance using confusion matrices and classification metrics. 📉
