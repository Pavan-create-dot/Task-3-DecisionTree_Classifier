# Overview 📝
Welcome to the DS_Task3 repository! This project demonstrates how to build a Decision Tree Classifier using the `bank.csv` dataset. The goal is to predict whether a person will subscribe to a term deposit based on their demographic and behavioral features.

This repository provides all the necessary code to preprocess the data, train a Decision Tree model, visualize the tree structure, and interpret the results. 🔥

## Dataset 📊
The dataset used in this project is related to bank marketing. It contains information about individuals' demographic and behavioral data. The objective is to predict whether or not an individual subscribes to a term deposit based on various features.
Bank : https://1drv.ms/x/c/f6bc90f75ca4b431/EcYMKMGoKIROr_k4cT1Zi5wBfWz_NWkV36MjXkKfDHgHfg?e=Wgu3ZC
Bank-full : https://1drv.ms/x/c/f6bc90f75ca4b431/EdDBowS-DOVCthZAtrFiHPwBf7YgoSx0YsP9g_kuCDVVoQ?e=4ozaxB


### Data Details:
The dataset includes the following columns:

- **age**: Age of the individual. 🎂
- **job**: Type of job (e.g., unemployed, services, management, etc.). 💼
- **marital**: Marital status (e.g., married, single). 💍
- **education**: Education level (e.g., primary, secondary, tertiary). 🎓
- **default**: Whether the individual has credit in default (yes/no). 💳
- **balance**: Account balance. 💵
- **housing**: Whether the individual has a housing loan (yes/no). 🏡
- **loan**: Whether the individual has a personal loan (yes/no). 💰
- **contact**: Contact communication type (e.g., cellular, telephone). 📞
- **day**: Last contact day of the month. 📅
- **month**: Last contact month of the year. 📆
- **duration**: Duration of the last contact. ⏳
- **campaign**: Number of contacts performed during the campaign. 📈
- **pdays**: Number of days since the client was last contacted. 🕰️
- **previous**: Number of contacts performed before this campaign. 📞
- **poutcome**: Outcome of the previous marketing campaign (success, failure, etc.). 🏆
- **y**: Target variable (whether the person subscribed to the term deposit - yes/no). ✅

## Tools and Libraries 🛠️
To successfully run the code and visualize the decision tree, the following tools and libraries are required:

- **Python 3.x**: The main programming language used. 🐍
- **pandas**: For data manipulation and loading. 📊
- **numpy**: For numerical operations. 🔢
- **scikit-learn**: For building the Decision Tree model. 🧠
- **matplotlib**: For plotting visualizations. 📊

## What does the code do? 🤖
The notebook follows these major steps:

1. **Data Preprocessing**:
   - Load the dataset and inspect its structure.
   - Handle missing values and encode categorical variables. 🔧

2. **Model Training**:
   - Train a Decision Tree Classifier on the dataset using the target column `y`. 🌟

3. **Visualization**:
   - Visualize the Decision Tree  to understand the model's decision-making process. 🌱

4. **Evaluation**:
   - Assess model performance using metrics like accuracy and a classification report. 📈

## How to Run 🚀
Follow these steps to set up and run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/DS_Task3.git
   cd DS_Task3
   ```

2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn  matplotlib
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook DS_Task3.ipynb
   ```

4. Run all cells in the notebook to train the Decision Tree and visualize the results.

## Handling Issues ⚠️
- **Dataset Not Found**: Ensure the `bank.csv` file is placed in the correct directory or update the file path in the notebook. 🗂️

## Desired Output 🎯
The project outputs the following:

- A visualized Decision Tree saved as a `.png` file.
- ![image](https://github.com/user-attachments/assets/54dcab76-b545-4d8a-9fe9-4dab02af71d7)

- Model evaluation metrics, including accuracy and classification report.
- 

https://github.com/user-attachments/assets/f2105402-9aa1-4d7c-b805-2bbf1b58c052



## Conclusion 🎉
By following this guide, you will:
- Preprocess and prepare the `bank.csv` dataset for analysis. 🔧
- Train and visualize a Decision Tree Classifier. 🌟
- Evaluate the model's performance and understand its decision-making process. 🌳
