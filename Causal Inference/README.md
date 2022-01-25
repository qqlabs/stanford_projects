## Impact of COVID Misinformation on Vaccination - A Reanalysis Identifying and Addressing Covariate Imabalances

Class: [STATS 209](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&page=0&catalog=&q=STATS+209%3A+Introduction+to+Causal+Inference&collapse=) - Causal Inference

Code (in R): [Google Colab](https://colab.research.google.com/drive/1m-5hD2vt-CH9IzeQGlbHD6cQt5Qaih9b?usp=sharing)

We reanalyzed a randomized controlled trial ([Original Paper](https://www.nature.com/articles/s41562-021-01056-1), [Original Github](https://github.com/sloomba/covid19-misinfo/)) that exposed participants to COVID misinformation and measured its impact on vaccination intent. We evaluated the study’s randomization and show that it is **significantly imbalanced** (p-value < 0.0001) using a Monte Carlo simulation of the **Mahalanobis distance between Treatment and Control**. We then reduced the bias of the estimates by applying **matching estimators** and performing **regression adjustment using Lin’s Estimator**. We also explored **heterogeneous treatment effects** and provide some intuitive insights.
