Placement-Predictor
A Machine Learning project implementing a Linear Regression model to predict student placement outcomes (such as expected salary or placement scores) based on various academic and demographic features.

📁 Repository Structure
Placement Predictor.ipynb: The core Jupyter Notebook containing the end-to-end workflow, including data loading, exploratory data analysis (EDA), data preprocessing, model training, and performance evaluation. 
.ipynb_checkpoints/: Auto-generated Jupyter state files (Note: It is considered best practice to hide this folder in future commits using a .gitignore file). 

🛠️ Technologies Used
Language: Python

Environment: Jupyter Notebook

Libraries:
pandas and numpy for data manipulation
scikit-learn for building and evaluating the Linear Regression model

🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/Debojitghosh-it/Placement-Predictor.git
cd Placement-Predictor

Install dependencies

pip install pandas numpy scikit-learn matplotlib seaborn jupyter
Launch Jupyter Notebook
jupyter notebook

📊 Model Overview
This project uses Simple/Multiple Linear Regression to establish a linear relationship between the independent variables (student metrics) and the dependent variable (placement metric). The notebook walks through:
Handling missing values and encoding categorical data.
Splitting the dataset into training and testing sets.
Fitting the regression line.
Evaluating model accuracy using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared ($R^2$) score.
👤 Author
DebojitGhoshGitHub: @Debojitghosh-it
