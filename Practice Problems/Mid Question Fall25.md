SET A
<center>
BRAC UNIVERSITY
Department of Computer Science and Engineering
Examination: Semester Mid
Duration: 1.5 Hours
Semester: Fall 2025
Full Marks: 40
CSE 427: Machine Learning
Answer the following questions.
Figures in the right margin indicate marks.
</center>
1.
a. Grades of students are predicted using the data in Table 1. Naïve Bayesian classifier is used for this prediction task. What will be the prediction for a student having Section = A and Mid Marks = 25? You are given \mu_{\text{Pass}} = 23.8, \mu_{\text{Fail}} = 20.9, \sigma_{\text{Pass}} = 6.5 and \sigma_{\text{Fail}} = 7.4 for Mid Marks attribute. [5]
b. The line y = mx + 3 fits the data points of Table 2. Update the value of m using gradient descent if the initial value for m is taken 1 and the learning rate is set 0.5 (single iteration only). [5]
Table 1
| Student ID | Section | Mid Marks | Grade |
|---|---|---|---|
| 1 | A | 10.5 | Fail |
| 2 | B | 13.2 | Pass |
| 3 | C | 15.4 | Fail |
| 4 | A | 20.8 | Pass |
| 5 | A | 23.5 | Fail |
| 6 | B | 25.1 | Pass |
| 7 | C | 26.7 | Fail |
| 8 | B | 27.3 | Fail |
| 9 | C | 27.9 | Pass |
| 10 | A | 29.4 | Pass |
Table 2
| x | y |
|---|---|
| 1 | 5 |
| 2 | 7 |
| 3 | 9 |
2.
(a) You are using Random Forest Algorithm to predict the grade of a student. Suppose, Table 1 is one the subsets of your overall dataset after bootstrapping. Using max_depth = 1 and criterion = gini, find the best separator among these three: [6]
i) Section = B
ii) Mid Marks <= 11.85
iii) Mid Marks <= 24.30
(b) Now, you are also trying to implement the AdaBoost Classifier. Considering the best tree (estimator) from a) as your first stump, calculate the Amount of Say and update the weights for the Correctly and Incorrectly Classified instances for Table 1. [4]
3.
a. Consider the truth table of two input (x1, x2) XOR gate as a dataset of a classification problem. You are asked to use Logistic Regression for classification. Now find the cross entropy loss for each of the examples in the dataset using the Z score given by Z = 0.5 X1 + 0.75 X2 - 0.6. [5]
b. Consider the data set in Table 3. Apply gradient boost to the dataset. Calculate the initial log of odds, probability and residuals. Now consider the stump for “Semester” as the tree for the first iteration. Now calculate the updated log of odds, probability, and residuals after the first iteration. Assume the learning rate is 0.1. [5]
Table 3
| Gender | Semester | Department | Result |
|---|---|---|---|
| Male | Third | CSE | Good |
| Female | Seventh | EEE | Bad |
| Male | Twelfth | BBA | Good |
| Female | Seventh | EEE | Good |
| Male | Twelfth | BBA | Bad |
| Female | Third | CSE | Good |
| Male | Twelfth | BBA | Bad |
| Female | Seventh | EEE | Good |
| Male | Third | CSE | Good |
| Female | Third | CSE | Bad |
Table 4
| BMI | DIET TYPE | EXERCISE | FASTING GLUCOSE |
|---|---|---|---|
| 19.8 | Vegetarian | Yes | 82.0 |
| 22.5 | Mixed | Yes | 89.5 |
| 24.0 | Vegetarian | Yes | 94.1 |
| 29.8 | High Sugar | Yes | 142.6 |
| 21.4 | Mixed | Yes | 86.3 |
| 34.5 | High Sugar | No | 156.9 |
| 18.6 | Vegetarian | Yes | 79.4 |
| 26.0 | Mixed | No | 108.8 |
4. Consider the dataset in Table 4 to predict fasting blood glucose (mg/dL).
a. Find out which will be the better split among DIET TYPE and EXERCISE to build a tree from this dataset. [5]
b. Now Label the target column as,
Use the split you got from (a) as root and complete the tree using Gini Index. [5]
