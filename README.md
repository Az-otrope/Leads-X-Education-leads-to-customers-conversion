# X-Education Leads Scoring Model
- [Motivation](#Project-Motivation)
- [Installation](#Installation)
- [File Descriptions](#File-Descriptions)
- [Instructions](#How-To-Run-This-Project)
- [Licensing, Authors, Acknowledgements](#License)

## Project Motivation <a name="Project-Motivation"></a>
The motivation for this project is to understand factors attracting users and converting them to customers of online courses provided by an education company.

**Background:** X Education provides online courses to industry professionals. Many professionals who are interested in the courses land on the website and browse for courses. X education advertises its courses across several marketing platforms such as Google, Olark chat, etc. Once visitors land on the website, they might perform engagement activities such as browsing courses, filling up forms, or watching some videos. When visitors fill up forms providing their email address or phone number, they get converted to leads. The company also acquires leads through past referrals. Once leads are acquired, employees from the sales team phone and email campaigns. Through this process, a fraction of generated leads gets converted into customers. However, the typical lead conversion rate at X education is around 30%, which is something this notebook attempts to improve.

**The goal** of this project is to improve the conversion rate of visitors to customers for X Education. A logistic regression model identifies the impactful marketing and sale factors. The model is to assign a lead score on each lead. The higher the score, the higher the conversion chance.

## Installation <a name="Installation"></a>
The following packages and versions are used in this jupyter notebook. Any newer versions should work. 
| Package  | Version |
| ------------- | ------------- |
| Python  | 3.8.5  |
| Pandas  | 1.1.3  |
| Numpy   | 1.19.2 |
| Matplotlib | 3.3.2|

## File Description <a name="File-Descriptions"></a>
There are 4 files in this repository. <br>
The original dataset and info is provided in `.xlsx` and `.csv` files <br>
A jupyter notebook `.ipynb` includes the process of reading in, preprocessing, and modeling the dataset. <br>
A README.md file as a brief look at this repository.

## Instructions <a name="How-To-Run-This-Project"></a>
* Execute the codes in this notebook and follow along the insights to understand the decisions made throughout the process.
* The main findings and results of this project can be found in this [post](https://medium.com/@nguyenpham111/tips-to-improve-conversion-rate-for-online-educational-providers-fd84c9a43226)

## Licensing, Authors, Acknowledgements <a name="License"></a>
* The data set, licensing, and other descriptive information is available on [Kaggle](https://www.kaggle.com/lakshmikalyan/lead-scoring-x-online-education)
