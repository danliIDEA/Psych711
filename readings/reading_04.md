Exercises about Rex Kline's book (for Tues., Oct. 01)
===============================================================================

> Read pp. 75-112 in Rex Kline's book. There is no need to read in detail the sections on other SEM programs (AMOS, EQS, etc.) in chapter 4. Please do read, however, the introduction (pp. 75-79), the sections on Mplus (p. 83) and R (p. 86), and the summary of chapter 4. 

Chapter 4
-------------------------------------------------------------------------------

### 1. What does Rex Kline think about graphical user interfaces that allow the researchers to draw their model on the computer screen.

* Good for beginners
* Tedious
* Limited (for multiple levels or multiple groups)

### 2. What software did Rex Kline use to draw the model diagrams in his book?

Microsoft Word.




Chapter 5
-------------------------------------------------------------------------------

### 3. Kline talks about six basic steps in SEM. In which of these steps does theory play a particularly important role? Justify your answer.

Theory plays a role in the italicized items.

1. _Specify the model_
2. Evalute the model identification
3. _Select measures_ and collect the data.
4. Estimate the model
    a. Evaluate model fit
    b. _Interpret parameter estimates_
    c. _Consider equivalent or near equivalent models_
5. _Respecify the model if needed_
6. Report the results
7. Optional: Replicate the results
8. Apply the results.

### 4. Kline says that when looking at the results of a SEM analysis, we should not only evaluate the model fit, but also interpret the \_\_\_\_\_\_\_. Why?

Parameter estimates for specific effects. It is important to verify that the parameter estimates are meaningful. 

### 5. What does Kline mean when he says that we should strive for "statistical beauty"?

The model: 

> 1. Has a clear theoretical rationale.
2. Differentiates between what is known and what is unknown---that is, what is the model's range of convenience, or limits to its generality.
3. Set conditions for posing new questions.

We might add "parsimony" (or elegance) to the causal model.

It can be dangerously easy to find a model that fits a set of data, when we can ignore what the variables represent.

### 6. Why exactly are endogenous variables not free to vary, i.e., why do we not estimate the variance of endogenous variables, but the variance of the disturbances associated with the endogenous variables?

Endogenous variables are not free to vary because their causes are specified in the model. Disturbances act like latent causal variables, so we can estimate the variance of the disturbances.

The model should be describing how the endogenous vary.

### 7. Name at least three conditions that must be met before one can reasonably infer a causal relationship from X to Y.

1. Temporal precedence (X comes before Y)
2. Association (X and Y covary)
3. Isolation (no extraneous causes)
4. Correct effect priority (direction of causal effect)
5. Known distributional form (for probabilistic causality)

(Is point 2 necessary when samples are self-selecting or effects are suppressed?)

### 8. Assume we conduct a longitudinal study and we find that X measured at time 1 influences Y measured at time 2. Does such a result prove that there is a causal relationship between X on Y?

It may be the case that Y causes X and there observed relationship reflects covaration. 

### 9. What can researchers do when they are unsure about the directionality of an effect (does Y1 cause Y2 or does Y2 cause Y1)? 

> Discuss the advantages and disadvantages of each way to deal with this problem.

Careful longitudinal measurement to preserve temporal precedence. Longitudinal designs take more resources and face attrition risks. Simultaneous measurement avoids those problems but also removes temporal precedence. A sound theoretical justification can help assert directionality for concurrently measured relationships.

1. Specify a model without specifying the directionality between crucial variables (allow the two to covary)
2. Specify alternative models with different causal directions
3. Cover both directions with a reciprocal effect in the model

Option 1 works for exogenous variables, which are allowed to covary. In option 2, the alternative models may fit the data just as well, so the question remains unanswered. Option 3 makes the model more complicated. You may also use a minimally sufficient analysis, and skip SEM entirely.

### 10. Measurement reliability

> In multiple regression analysis there are (a) independent and (b) dependent variables, in structural equation modeling there are (a) exogenous and (b) endogenous variables. Say whether the scores of each of these four types of variables are assumed to be perfectly reliable (measured without error) or not.

Endogenous variables account for measurement error in the disturbances.

Exogenous variables and independent variables are assumed to be measured reliably.

### 11. Explain the difference between recursive, nonrecursive and partially recursive models. Explain the strength and weaknesses of recursive and nonrecursive models.

Recursive models have no loops among endogenous variables nor are the disturbances allowed to covary. Nonrecursive models have feedback loops or allows disturbances to covary, implying that the pair of endogenous variables share some unobserved cause. Partially recursive models allow the endogenous variables to have covarying disturbances, provided that there isn't a direct path betwen them.

Recursive models are easier to analyze.

### 12. "Panel designs are generally useful for resolving effect priority between reciprocally related variables." True or false? Justify your answer.

False, unless assumptions like stationarity or isolation are met.

### 13. Do exercise 3 on page 122.

```
Direct relations + covariances +  variances
10, 10, 9
```
