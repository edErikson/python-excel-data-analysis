Titanic Dataset Analysis
This repository presents a comprehensive analysis of the widely used Titanic dataset, employing both Python (via a Jupyter Notebook) and Microsoft Excel for the analysis.

Python Analysis - Jupyter Notebook
The Python analysis conducted in a Jupyter Notebook starts with data preprocessing where the structure of the dataset is understood, and missing values are identified. Visualization of the 'Survived' column in relation to 'Sex' of the passengers gives an early insight into the data. 'Age' column's missing values are treated by replacing them with the mean age, and the 'Cabin' column is removed due to a high percentage of missing data. The 'Sex' column is then binarized and unnecessary columns ('Name', 'Sex', 'Ticket', 'Embarked') are dropped for a more focused analysis. The data is divided into training and testing sets for model building. A logistic regression model is trained on this data, which is then used to make predictions on the test data. The final step in the Python analysis involves evaluating the model performance via a confusion matrix and a classification report.

Excel Analysis
Microsoft Excel is used to perform basic count functions and create pivot tables to add depth to the analysis. The number of males and females are counted, followed by the count of passengers in each class. The number of survivors is also counted, providing a clear picture of the survival situation. Pivot tables are created, highlighting the survival status by class and gender, and the survival rate by age.

This project provides an excellent platform for individuals just starting with data analysis or aspiring to learn more about machine learning, as it involves a widely recognized dataset and the use of two popular tools - Python and Excel.
