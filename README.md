*This project was carried out during the Python Machine Learning Lab course at Data ScienceTech Institute (DSTI), as part of the Applied MSc in Data Science & Artificial Intelligence qualification.*
***
# Prediction of Goodreads book ratings
***
by Gabriela Copetti


## **Aim**

The aim of this project is to apply machine learning techniques, including data cleaning and analysis, feature selection, model training, and evaluation, to predict book average ratings at the Goodreads website using the dataset provided in the course.

## **Structure**

All computations were performed using Python 3.9 and Jupyter Notebook 6.5. 

- Goodreads_Project_Report.pdf: a report with a summary of the steps taken and the results obtained.

- Goodreads_Dataset_Data_Analysis.ipynb: Jupyter notebook in which exploratory data analysis was used to summarize main characteristics and to check for patterns within the data. Data cleaning was performed, as well preliminary feature selection and engineering. 

- Goodreads_Dataset_Model_and_Evaluation: Jupyter notebook in which four regression algorithms are used to predict the average rating, using different sets of features.

- books.csv: original dataset provided in the course.

- books_edited.csv: corrections were made to the original books.csv for it to become readable.

- books_processed.csv: dataset after data analysis, cleaning and preliminary feature selection. This file is produced by the Goodreads_Dataset_Data_Analysis.ipynb notebook.


## **Installation**

Use the command

**pip install -r requirements.txt**

to install the packages. If the file is not placed in the current directory, the path needs to be specified like path/to/requirements.txt.

If using an environment in Anaconda, the command

**conda install --file requirements.txt**

can be used.
 
