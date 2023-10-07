# Multivariable_Regression

**The performance of the algorithm in case of complex boundaries. **
Multivariable Regression up to 2-degree polynomial for all the feature present in the Boston dataset.

Here Two algorithm is implemented one is with simple Linear Regression with all the feature and other one is with the complex boundaries up to 2-degree polynomials.
After that we check the case of **OVERFITTING** by comparing the coefficient of determination for both of the algorithm.

In the **Algo_one** the simple Linear Regression is applied and for **Algo_two** all possible 2-degree polynomials are applied.
Now for the below image it is clear that Algo_one has less score on training data but more score on testing data in comparison with Algo_two.
Algo_two really perform well on training data but really bad performance on the testing data. By adding the more complexity on the boundaries,
the training score improved by testing score is reduced. So, it is not a good idea to add all the 2-degree polynomial, Instead we can add few important boundary feature to improve the algorithm.

![image](https://github.com/Data-Engineering-SUV/Multivariable_Regression/assets/106040176/e309c70f-21ce-437d-b8e9-4b46f451ea00)
