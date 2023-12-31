link to Github: https://github.com/GabCopetti/Goodreads_Ratings_ML_Project/tree/main

*This project was carried out during the Python Machine Learning Lab course at Data ScienceTech Institute (DSTI), as part of the Applied MSc in Data Science & Artificial Intelligence qualification.*

***
# Goodreads dataset: Book rating prediction
***

by Gabriela Copetti


## **Aim**

The aim of this project is to apply machine learning techniques, including data cleaning and analysis, feature selection, model training and testing, to predict book average ratings on the Goodreads website, using the dataset provided in the course (originally from https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks).

## **Files**

- **Goodreads_Project_Report.pdf: a report with a summary of the steps taken and the results obtained.**

- Goodreads_Dataset_Data_Analysis.ipynb: Jupyter notebook in which exploratory data analysis was used to summarize main characteristics and to check for patterns within the data. Data cleaning was performed, as well as preliminary feature selection. 

- Goodreads_Dataset_Model_and_Evaluation.ipynb: Jupyter notebook in which four regression algorithms were trained and tested using different sets of features.

- books.csv: original dataset provided in the course.

- books_edited.csv: corrections were made to the original books.csv for it to become readable.

- books_processed.csv: dataset after data analysis, cleaning and preliminary feature selection. This file is created in the Goodreads_Dataset_Data_Analysis.ipynb notebook for use in the Goodreads_Dataset_Model_and_Evaluation.ipynb.


## **Installation**

All computations were performed using <a href="https://www.python.org/downloads/" target="_blank">Python</a> 3.9 and <a href="https://jupyter.org/install" target="_blank">Jupyter Notebook</a> 6.5.

To install the packages, use the command:

**pip install -r requirements.txt**

If the file is not placed in the current directory, the path needs to be specified like path/to/requirements.txt.

If using an environment in Anaconda, the command:

**conda install --file requirements.txt**

can be used.
 
