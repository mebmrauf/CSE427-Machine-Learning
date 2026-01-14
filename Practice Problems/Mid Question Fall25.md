**Instructions:**  
Answer the following questions.  
Figures in the right margin indicate marks.

**Name:** ____________________  
**ID:** ____________________  
**Section:** ____________________

---

## Question 1

### (a) [5 marks]
Grades of students are predicted using the data in **Table 1**. Naïve Bayesian classifier is used for this prediction task.  

What will be the prediction for a student having:
- **Section = A**
- **Mid Marks = 25**

You are given:  
- μ_pass = 23.8  
- μ_fail = 20.9  
- σ_pass = 6.5  
- σ_fail = 7.4  

for the **Mid Marks** attribute.

---

### (b) [5 marks]
The line  
\[
y = mx + 3
\]
fits the data points of **Table 2**.  

Update the value of **m** using **gradient descent** if:
- Initial value of m = 1  
- Learning rate = 0.5  
- Single iteration only  

---

## Table 1

| Student ID | Section | Mid Marks | Grade |
|----------|---------|-----------|-------|
| 1 | A | 10.5 | Fail |
| 2 | B | 13.2 | Pass |
| 3 | C | 15.4 | Fail |
| 4 | A | 20.8 | Pass |
| 5 | A | 23.5 | Fail |
| 6 | B | 25.1 | Pass |
| 7 | C | 26.7 | Fail |
| 8 | B | 27.3 | Fail |
| 9 | C | 27.9 | Pass |
|10 | A | 29.4 | Pass |

---

## Table 2

| x | y |
|---|---|
| 1 | 5 |
| 2 | 7 |
| 3 | 9 |

---

## Question 2

### (a) [6 marks]
You are using **Random Forest Algorithm** to predict the grade of a student. Suppose **Table 1** is one of the subsets of your overall dataset after bootstrapping.

Using:
- `max_depth = 1`
- `criterion = gini`

find the **best separator** among the following:

1. Section = B  
2. Mid Marks ≤ 11.85  
3. Mid Marks ≤ 24.30  

---

### (b) [4 marks]
Now, you are also trying to implement the **AdaBoost Classifier**.

Considering the **best tree (estimator)** from part (a) as your **first stump**, calculate:
- The **Amount of Say**
- Updated **weights** for the **Correctly** and **Incorrectly** classified instances for **Table 1**.

---

## Question 3

### (a) [5 marks]
Consider the truth table of two inputs (x₁, x₂) **XOR gate** as a dataset of a classification problem.

You are asked to use **Logistic Regression** for classification.  
Now find the **cross-entropy loss** for each example in the dataset using the Z-score:

\[
Z = 0.5X1 + 0.75X2 - 0.6
\]

---

### (b) [5 marks]
Consider the dataset in **Table 3**. Apply **Gradient Boost** to the dataset.

1. Calculate the **initial log odds**, **probability**, and **residuals**  
2. Consider the stump for **“Semester”** as the tree for the first iteration  
3. Calculate the **updated log odds**, **probability**, and **residuals** after the first iteration  

Assume the **learning rate = 0.1**

---

## Table 3

| Gender | Semester | Department | Result |
|------|---------|------------|--------|
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

---

## Question 4

Consider the dataset in **Table 4** to **predict fasting blood glucose (mg/dL)**.

---

### (a) [5 marks]
Find out which will be the **better split** among:
- **DIET TYPE**
- **EXERCISE**

to build a decision tree from this dataset.

---

### (b) [5 marks]
Now label the target column as:

- **FASTING GLUCOSE < 100** → Normal  
- **100 ≤ FASTING GLUCOSE < 126** → Prediabetes  
- **FASTING GLUCOSE ≥ 126** → High  

Use the split you got from part (a) as the **root** and complete the tree using **Gini Index**.

---

## Table 4

| BMI | Diet Type | Exercise | Fasting Glucose |
|----|-----------|----------|-----------------|
| 19.8 | Vegetarian | Yes | 82.0 |
| 22.5 | Mixed | Yes | 89.5 |
| 24.0 | Vegetarian | Yes | 94.1 |
| 29.8 | High Sugar | Yes | 142.6 |
| 21.4 | Mixed | Yes | 86.3 |
| 34.5 | High Sugar | No | 156.9 |
| 18.6 | Vegetarian | Yes | 79.4 |
| 26.0 | Mixed | No | 108.8 |

---
