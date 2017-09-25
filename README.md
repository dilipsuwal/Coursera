### Prediction Assignment Writeup project for the Coursera Practical Machine Learning course

Following is the outcome of this project

1. ML_Writeup_Assignment.html
2. ML_Writeup_Assignment.Rmd

Please download and open the html page "ML_Writeup_Assignment.html" in your local machine to view the project report. The code deltail is in ML_Writeup_Assignment.Rmd

ML_Writeup_Assignment.pdf can also be open to view the project report, just in case. The pdf version was generated in the second run and Model accuracy has slighlty increased than that in previous run, which we can observe in the ML_Writeup_Assignment.html.

For Course Project Prediction Quiz Portion, identified base model "random forest machine learning algorithm" has been applied to the 20 test cases available in the test data and we can see the prediction for 20 cases given velow.

predictionRF <- predict(fit.rf, TestingSet)

predictionRF [1] B A B A A E D B A A B C B A E E A B B B

Levels: A B C D E
 
