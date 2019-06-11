# grades_prediction_KERAS
design a model that learns weights to calculate a grade on provided pairwise comparisons.

## Problem statement
A school receives each year a given number of student applications. These applications are made both of qualitative elements (that we will ignore in this exercise) and some quantitative ones about the grades they obtained for a given list of courses the student followed.

Let us assume that people in charge of the selection process in this school would like to compute, for each student, a kind of global grade that would be a weighted average of its grades. Unfortunately, these peolpe are not able to reach a consensus on which weights to use. The only consensus they could reach is when they have to compare a pair of files and decide on which is better.

The goal of this assignment is then to design a model that could learn those weights based on provided pairwise comparisons. To do so, you are given a dataset that indicates, for each pair of student candidates, the one that would be prefered (and hence ranked higher) by the jury.

### Constraints for this problem are as follows:

the final score given to a student should be a linear combination of its grades;
each weight should be positive;
