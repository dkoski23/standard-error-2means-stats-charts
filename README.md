# standard-error-2means-stats-charts

This function takes in two columns of data, cleans the data so that only numerical values remain, finds the standard deviation of the samples, and subsequently calculates the standard error for the difference between the two means. I initially devised this function because I have not found anybody else who wrote a function/library that performs these tasks. Then I decided to expand the function to provide other useful statistical analysis with some further visualizations.

The next section runs a statistical z-test and shows the p-value (basically evaluating the strength of the evidence for a difference in means). It then calculates a 95% confidence interval for the difference between means. If the p-value (the odds of getting this result if the means are roughly equivalent) indicates that they are not equivalent, and 0 does not lie within the confidence interval, than the difference is unlikely to be equivalent.

Summary statistics tables are then created for each column of data. Finally, the data is combined to make a box and whisker plot, violin plot, line plot, and overlapping distribution plot, which can provide useful information about the data.
