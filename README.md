# Bootstraped-metrics
This little pet-project studies the following problems:
  1. The problem with certainty in ROC-AUC score. Since AUC score is a statistics, the confidence interval can be estimated by using the boostrap technique.
  2. In classification tasks, it is necessary to choose the probability threshold. This problem can be ressolved by the precision-recall curve. We choose that           threshold which corresponds to precision higher than fixed value and which corresponds to the maximum of recall. However, the precision-recall curve is not monotonous, so the specificity-recall curve is also implemented.
