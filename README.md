---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 3 V2               <br/>
**Topic**:  Linear Algebra <br/>
**Amount of time**:  60 minutes  <br/>
**Author**: Laura Colon-Melendez, Victor Geislinger

Some material ported from starter repo: [link](https://github.com/MrGeislinger/flatiron-school-data-science-curriculum-resources/blob/master/Mathematics/Calculus/gradient_descent.ipynb)
***

#### Lesson Summary:

The lesson motivates the topic of derivatives by starting with a physics example: we wish to know the speed of a runner at a given instant in time. This leads to a discussion of the derivative of a function at a point and how it relates to the slope of the line tangent at that point. The difference quotient is introduced and connected to the derivative. Students write code to compute the limit of the difference quotient as $\Delta x$ goes to zero, and compare the values of derivatives obtained in this fashion to the derivatives of functions obtained by appluing power rules, constant factor rules, and the chain rule. Students use the derivative of a function to compute the minimum of a function. This leads to a discussion of what happens to the slope of the lines tangent to a curve before and after optimal values. After this discussion, the subject of cost functions in simple linear regression is introduced in the context of finding the line of best fit for some data. An example is presented, and students are asked to compute the mean squared error for different regression lines as the slope changes and intercept remains constant. They plot the mean squared error against different slope values. This is identified as the cost curve. Finally, the 3-dimensional cost curve for simple linear regression is shown and gradient descent is mentioned as a technique to find the best values of slope and intercept.  


#### Topic:

Statistical Modeling - Calculus

#### Learn.co material:

[Introduction to Derivatives](https://github.com/learn-co-curriculum/dsc-derivatives-intro)

[Introduction to Derivatives - Lab](https://github.com/learn-co-curriculum/dsc-derivatives-intro-lab)

[Derivatives of Non-Linear Functions](https://github.com/learn-co-curriculum/dsc-derivatives-of-non-linear-functions)

[Rules for Derivatives](https://github.com/learn-co-curriculum/dsc-rules-for-derivatives)

[Rules for Derivatives - Lab](https://github.com/learn-co-curriculum/dsc-rules-for-derivatives-lab)

[Derivatives: the Chain Rule](https://github.com/learn-co-curriculum/dsc-derivatives-chain-rule)

[Derivatives: Conclusion](https://github.com/learn-co-curriculum/dsc-derivatives-conclusion)

[Introduction to Gradient Descent](https://github.com/learn-co-curriculum/dsc-gradient-descent-intro)


#### Prerequisite knowledge:

Students should know about solving simple linear regression problems using ordinary least squares.


#### Prerequisite Learn.co material:

[Regression Analysis using Linear Algebra and Numpy - Code Along](https://github.com/learn-co-curriculum/dsc-linalg-regression-codealong)

[Regression with Linear Algebra - Lab](https://github.com/learn-co-curriculum/dsc-linalg-regression-lab)

[Computational Complexity: From OLS to Gradient Descent](https://github.com/learn-co-curriculum/dsc-computational-complexity)


#### Learning goals for this lesson:

* Students can compute the derivative of a function using Python. 
* Students can compute the derivative of a function using power rules, constant factor and the addition rule. 
* Students can find the minimum and maximum of a function by setting the derivative of the function equal to zero. 
* Students can compute cost curves for simple linear regression examples in the case where one of the two parameters is constant.


#### Relevant learning goals from Airtable: 

* CALCULUS.1.recDyqR3NTzUraSmo

* CALCULUS.2.recqEQiKIWUraMo9L

* CALCULUS.2.rec1A5EIZyfW4sk72

* CALCULUS.2.rec9XtfukeoO8oRFI

* CALCULUS.3.recO4WOkYjVpzwZgh

* CALCULUS.1.recALruM4amjWAXht

#### Misconceptions / Notes


#### Materials

- Ipython notebook 

#### Vocab / Concepts 

* difference quotient 
* derivative 
* cost function

#### Lesson Outline:

* Derivatives (30 minutes overall)
    * Motivation (5 minutes) 
        * The derivative as the instantaneous rate of change of f(x) at a point x and the slope of the line tangent to f(x) at x
    * Computing the derivative by calculating the difference quotient as $\Delta x$ get smaller and smaller (15 minutes)
        * Compare to the derivative of a function obtained by applying rules (addition rules, constant factor rule, and chain rule) 
            * Two examples: one simple, the other more involved. 
    * Finding the minima and maxima of a function (10 minutes) 
        * What happens to the slope of the lines tangent to f(x) before and after the critical value
        
* Cost functions in linear regression (~20 minutes overall)
    * Evaluating how well a line fits data 
        * If needed, spend some extra time making sure students understand why they need to square the errors. 
    * Computing the mean squared error for different lines for the same data: plotting cost curves 
    * Three-dimensional cost curve 
    
* Summary (5 minutes)

Wiggle room: 5 minutes 