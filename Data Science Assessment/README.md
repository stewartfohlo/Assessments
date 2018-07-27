#  DS Assignment Brief
The underlying goal of this assignment is to understand how you think as a data scientist. We recommend that you do this assignment in either a Python notebook or an R markdown notebook - but feel free to use a tool of your choosing. Write down all your thoughts and reasonings within the notebook with technical readers in mind. You should also provide an executive summary of your findings with non-technical readers in mind.

You have been given an anonymized data set containing 10 features and one target variable.

Your objectives are to:
* Perform data analysis and exploration of the data.
* Build a model to predict for the target variable `target_var` using the variables `feature_1` to `feature_9`. You are free to use any modelling technique but make sure to justify your reasonings.

Other information:
* It costs the company R20 000 per case when a prediction of 0 is made when in fact it was a 1 in the original dataset, it also costs the company R1000 when a prediction of 1 is made when in fact it was a 0 in the original dataset. It is up to you to decide how you will account for this in the assignment.
* You should not make any assumptions about the underlying source of the data.
* You must design the best model you can while avoiding overfitting. You must be able to quantitatively prove this.

Bonus points are given if `pySpark` / `rSpark` are used to perform the modelling and data exploration/analysis. You should pretend that you are working with millions of rows if you decided to use Apache Spark.
