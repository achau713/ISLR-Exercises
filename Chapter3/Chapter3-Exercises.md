---
title: "ISLR Chapter 3 Exercises"
author: "Anthony Chau"
date: 'Last compiled: May 30 2020'
output: 
  html_document:
    toc: true
    keep_md: true
---


\newpage

# Conceptual Exercises

## Question 1

Describe the null hypotheses to which the p-values given in Table 3.4 correspond. Explain what conclusions you can draw based on these p-values. Your explanation should be phrased in terms of sales, TV, radio, and newspaper, rather than in terms of the coefficients of the linear model.

_Solution:_

The null hypotheses to which these p-values correspond to is if the true regression coefficients are zero. Note that there is nothing said about a specified significance levels. We will not state that some coefficients are "significant" vs "non-significant". However, the regression results suggest that for for every $1000 increase in television, radio, and newspaper advertising, there will be an average change in sales by 46, 189, and -1 units, respectively.

\newpage

## Question 2

Carefully explain the differences between the KNN classifier and KNN regression methods.

_Solution:_  
  
KNN regression is a regression method used to estimate a functional form for a given dataset. It does this by identifying K training observations that are closest to $x_{0}$ (represented by $N_{0}$) and then estimates $f (x_{0})$ by the following formula: $f(x_{0})  = \frac{1}{K} * \sum_{x_{i} \in N_{0}} y_{i}$. That is, KNN regressions averages the response values from all the points in $N_{0}$.

KNN classification is a classification algorithm used to classify observations into different classes within the dataset. The algorithm assigns the observation to the class corresponding to the most common class of its neighboring points.


\newpage

## Question 3

Suppose we have a data set with five predictors, X1 = GPA, X2 = IQ, X3 = Gender (1 for Female and 0 for Male), X4 = Interaction between GPA and IQ, and X5 = Interaction between GPA and Gender. The response is starting salary after graduation (in thousands of dollars). Suppose we use least squares to fit the model, and get 

$$\begin{align}
\beta_{0} &=  50 \\
\beta_{1} &=  20 \\
\beta_{2} &=  0.07 \\
\beta_{3} &=  35 \\
\beta_{4} &=  0.01 \\
\beta_{5} &=  −10
\end{align}$$






_Solution:_

We write out the equation:

\[
Salary = 50 + 20 \cdot GPA + 0.07 \cdot IQ + 35 \cdot Gender + 0.01 \cdot (GPA \cdot IQ)  -10 \cdot (GPA \cdot Gender)
\]

a)

To answer this question, we assume that IQ and GPA is fixed. Then, we write the equation for males and for females

_Equation for males given fixed IQ and GPA:_

\[
Salary = 50 + 20 \cdot GPA + 0.07 \cdot IQ + 0.01 \cdot (GPA \cdot IQ)
\]

_Equation for females given fixed IQ and GPA:_

\[
\begin{align}
Salary & =  50 + 20 \cdot GPA + 0.07 \cdot IQ + 35 + 0.01 \cdot (GPA \cdot IQ)  -10 \cdot GPA\\
& =  85 + 20 \cdot GPA + 0.07 \cdot IQ + 0.01 \cdot (GPA \cdot IQ)  -10 \cdot GPA
\end{align}
\]


\newpage

## Question 4

\newpage

## Question 5

\newpage

## Question 6

\newpage

## Question 7

\newpage

## Question 8

\newpage

## Question 9

\newpage

## Question 10
