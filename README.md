# Bootstrapping Challenge - Team Kaspar & Hussein

## Dataset: UW-Madison Wisconsin grades
found [here (link to kaggle.com)](https://www.kaggle.com/Madgrades/uw-madison-courses)

We anaylyzed the overall average GPA from all classes that reported A-F style, completely omitting any (pass / fail) or 
other student achievement reporting methods. After transforming the possible grades:  [A, AB, B, BC, C, D, F] onto the 
4.0 GPA scale, we computed the weighted average based on class size for the entire dataset. We then randomly sampled 2000 
records and computed a confidence interval for the population mean GPA utilizing bootstrapping for an emperical result.

## Resources

* [Bootstrapping Demo Notebook](uw_mad_grades_bootstrapping.ipynb)
