# FreeCodeCamp - ML Notes

## What is Machine Learning?
<!--<hr>-->
Machine Learning is a subdomain of Computer Science that focuses on Algorithms which helps a computer to learn from data without explicit Programming.

## AI vs ML vs DS
<!--<hr>-->

- <b>Artificial Intelligence</b> is an area of computer science, where the goal is to enable computers and machines to perform human-like tasks and simulate human behavior

- <b>Machine Learning</b> is a subset of AI that tries to solve a specific problem and make predictions using data

- <b>Data Science</b> is a field that attempts to find patterns and draw insights from data (might use ML!)

All fields overlap! All may use ML!

## Types of Machine Learning
<!--<hr>-->

- <b>Supervised Learning:</b> uses labelled inputs (meaning the input has a corresponding output label) to train models and learn outputs

- <b>Unsupervised Learning:</b> uses unlabeled data to learn about patterns in data

- <b>Reinforcement Learning:</b> agent learning in interactive environment based on rewards and penalties

## Supervised Learning
<!--<hr>-->

```
                ___________
Input 1 -----> |           |
Input 2 -----> |           |
  ...   -----> |   MODEL   | -----> OUTPUT
  ...   -----> |           |
Input n -----> |___________|

```

<b>Feature Vector</b> - collection of all the inputs

### <b>Features</b>
- <b>Qualitative:</b> categorical data (finite number of categories or groups). Ex: Gender, Nationality
    - Nominal Data (no inherent order)
        - We would want to use ONE-HOT ENCODING (if a category matches, make it a 1 else 0)
    - Ordinal Data (inherent order)
        - Give a number

- <b>Quantitative:</b> numerical valued data (could be discrete or continuous). Ex: Length, Tempetature
    - Can be continuous or discrete

### <b>Types of Predictions</b>
- <b>Classification:</b> predict discrete classes
    - Multiclass Classification. Ex. Animals, Fruits, Plants
    - Binary Classification (Something or NOT something). Ex: Spam/Not Spam, Positive/Negative

- <b>Regression:</b> predict continuous values (coming up with some number). Ex. Stock Price, Temperature, House Price

### <b>About the Model</b>
##### How do we make the model learn?
##### How can we tell whether or not it is learning?

- <b>Features matrix(X):</b> matrix collecting all the data points and features
- <b>Labels/Targets vector(Y):</b> collection of all the output labels

```
 ________________
|          |     |
|----------|     |
|    FV    |     |
|----------|     |
|          |  Y  |
|          |     |
|    X     |     |
|          |     |
|__________|_____|

FV = Feature Vector
```
We break our dataset into three categories:
- Training Dataset
- Validation Dataset
- Testing Dataset
