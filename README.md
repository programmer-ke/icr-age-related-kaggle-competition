# Kaggle Competition [ICR Identifying Age-Related Conditions][1]

This repo has the notebooks used for the competition.

The best performing notebook on the private leaderboard was 
[this](notebooks/kfold-ensemble-gb-rf-nn.ipynb), scoring 0.28 in the
public leaderboard and 0.44 in the private leaderboard, almost getting
a bronze level position.

The ones I submitted however did not perform as well. Those were
[this](notebooks/hgb-kfold.ipynb) (0.26 public, 0.58 private) and
[this](notebooks/ensemble-them-all.ipynb) (0.6 public, 0.91 private).

Overall, it was quite an interesting competition. A small dataset
(which I understand is common with health records..),
how easy it was to overfit, how much even a [small shift][2] on  a single
data point's predictions impacted the overall metric, etc..

The winner's solution is explained [here][3].

I'll try document any learnings that will emerge.

[1]: https://www.kaggle.com/competitions/icr-identify-age-related-conditions
[2]: https://www.kaggle.com/competitions/icr-identify-age-related-conditions/discussion/430475
[3]: https://www.kaggle.com/competitions/icr-identify-age-related-conditions/discussion/430843
