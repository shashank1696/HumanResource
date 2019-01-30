# HumanResource
Classification of Employees leaving the Company for different aspects using Decision Tree Classification Algorithm

## Goal of this Project: 
This project is considered to predict and classify with respect to human resource department various aspects and check if the employees are leaving the company.

## Attributes
1)  satisfaction level(binary) - Ability to satisfy your customers to gain customer loyalty is the critical determinant of your success in     driving sales and growing your business.
2)  last evaluation(binary) - It is a tool employers use to review the performance of an employee.
3)  number project(binary) - number of Projects undertaken.
4)  average month hours(binary) - average monthly hours the employee has worked for.
5)  time spend company(binary) - time spent in the company while working.
6)  Work accident(binary) - work accident is "discrete occurrence in the course of work" leading to physical or mental occupational injury.
7)  left(binary) - whether the employee left the company or not.
8)  promotion last 5years(binary) - promotions made by the company/employee in last 5 years.
9)  sales (categorial: IT,sales,support,hr,RandD,management,marketing,product mng,technical) - sales by different departments in a company. 
10) salary (categorial: low,medium,high)

## Data Handling
1) Importing Data with Pandas
2) Cleaning Data
3) Exploring Data through Visualizations with graphs
4) Data Prediction

## Packages required in Python
1) pandas
2) numpy
3) sklearn.tree
4) sklearn.model_selection
5) pydotplus
6) from IPython.display importing Image
7) sklearn.metrics
8) matplotlib.pyplot

## Graphs
 ![hr1](https://user-images.githubusercontent.com/44108439/51936858-2687af00-242f-11e9-953a-8d8a0c81d458.png)
-  Fig: a) Decision Tree for HR dataset
 
 ![hr2](https://user-images.githubusercontent.com/44108439/51937033-8ed69080-242f-11e9-80de-b6b5d132b0c3.png)
-  Fig: b) ROC Curve for tree 1 with max depth = 3

 ![hr3](https://user-images.githubusercontent.com/44108439/51937061-a01f9d00-242f-11e9-92ad-36965f17653e.png)
-  Fig: c) ROC Curve for tree 1 with max depth = 8

## Conclusion
Classification of various aspects with respect to human resource department are considered and Decision tree is constructed using Decision Tree Classifier Algorithm with 98.1% accuarcy for the Employees to leave the company.
- ROC Curve for tree 1 with max depth = 3 have an accuracy of 96.8%
