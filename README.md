# Engineering-Graduate-Salary-Prediction


About
----------------------
Mini-Project for SC1015 ( Introduction to Data Science and Artificial Intelligence) using a dataset from kaggle
Dataset from Kaggle : **"Engineering Graduate Salary Prediction"** by *Manish Kc*  
Source: https://www.kaggle.com/datasets/manishkc06/engineering-graduate-salary-prediction


Problem Definition
----------------------
How can (engineering?) undergraduates predict their expected salary?
- Does it pay well?
- Is there demand for what i'm currently studying?
- What can I expect for various different jobs under engineering?


Models Used
----------------------
- Linear Regression
- XGBoost
- ADABoost
- Gradient Boosting

Conclusion
-----------------------

> - ####  Our predictor variables have very low correlation to our response variable(Salary) 
>   - From the plotted graph, we deduced that 10th percentage and 12th percentage have a linear relationship hence we decided to drop 10percentage, as it is redundant.
>   - Where our highest correlation to Salary is Quant of 0.24.
>   -  Hence, we can conclude that the R^2 of our model will be low
> - ####  With the vast amount of specialization, we decided grouped everything that is less than 10 into others category
> - #### Normalized all variables with one-hot encoding as when we do further analysis, like multivariate linear regression, for example, the attributed income will intrinsically influence the result more due to its larger value. But this doesn't necessarily mean it is more important as a predictor. So we normalize the data to bring all the variables to the same range.
> - #### After using LinearRegression model, we used to other models to compare with our LinearRegression, with conclusions shows that our LinearRegression model shows the best fir for the the datasets as compared to other models, with Gradient Boosting model confirming that it gives the maximum and best fit of the data set having the lowest RMSE and MAPE


Reflection
-----------------------
> - #### We started to explore on problems of our everyday lives and it came to formulate our problems definition.
> - #### Using techniques of handling the data set, exploratory analysis, data visualization efficiently.
> - #### Learning to utilize powerful regression model such as XGBoost, ADABoost and Gradient boosting.
> - #### Realising that lower R^2 model doesn't meant that its a bad fit of model for the dataset.
> - #### Version control using github
> - #### Methods using VIF Score, Backward Elimination.
> - #### One hot encoding to normalized the vast range of the dataset


Repository Description
----------------------

Faiz Bin Rosli (FAIZ007@e.ntu.edu.sg)

Kang Jun Hui Bryan (KANG0121@e.ntu.edu.sg)

Low Zheng Han (ZLOW030@e.ntu.edu.sg)

School of Computer Science and Engineering

Nanyang Technological University

Apr 2022

This repository is submitted to Nanyang Technological University as part of a 
graded assignment for the course CZ1115 (Introduction to Data Science & 
Artificial Intelligence).

Repository Contents
-------------------

Project.ipynb

LICENSE
        
README.txt

images
        
        graduates.png

presentation
        
        Presentation.pdf
       
File Descriptions
-----------------

Project.ipynb
    
    A Jupyter Notebook containing the main source code for the project.
    
LICENSE

    The licensing information for this project.

README.txt (this file)
    
    Basic information about the project repository.
    
presentation/Presentation.pdf
    
    A PDF copy of the presentation slides (video presentation not available in 
    this repository).
    
    
## References

> - XGBoost : https://xgboost.readthedocs.io/en/stable/
> - ADABoost : https://www.analyticsvidhya.com/blog/2021/09/adaboost-algorithm-a-complete-guide-for-beginners/
> - Gradient boosting : https://en.wikipedia.org/wiki/Gradient_boosting
> - Low R^2 : https://blog.minitab.com/en/adventures-in-statistics-2/how-to-interpret-a-regression-model-with-low-r-squared-and-low-p-values
> - Engineering Salary Prediction Dataset: https://www.kaggle.com/datasets/manishkc06/engineering-graduate-salary-prediction
> - VIF Score : https://www.analyticsvidhya.com/blog/2020/03/what-is-multicollinearity/#:~:text=%E2%80%9C,-or&text=VIF%20score%20of%20an%20independent,explained%20by%20other%20independent%20variables.&text=So%2C%20the%20closer%20the%20R,with%20the%20particular%20independent%20variable.
> - One Hot Encoding : https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html

