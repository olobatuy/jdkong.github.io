---
title: "Bayesian Nonparametric Tensor Completion"
collection: projects
type: "Data Science"
permalink: /projects/2017-03-31-datascience
venue: "University of Alberta"
date: 2017-03-31
location: "Edmonton, Canada"
---

In this project, we propose a Bayesian nonparametric method to estimate missing data in tensors. The proposed method uses a Tucker-1 factorization to learn a smaller core tensor and a factor matrix via Gibbs sampling. Unlike most existing Tucker factorization algorithms, the tensor rank is estimated automatically. This is done by employing an Indian Buffet Process prior over the latent matrix, where the estimated number of non-zero columns corresponds to the tensor rank. The missing data is then estimated based on the latent structure learned from the factorization. As a result, the method provides a form of Bayesian model averaging over estimated ranks, allowing it to avoid overfitting. As an illustration, a num- ber of datasets are artificially corrupted at various levels. Relative error is used to assess completion performance and our result is compared to parallel matrix factorization as a baseline. The empirical results show that our method does not beat the current state of the art, but provides pertinent information that other methods do not. That is, statistical quantities, like mean standard error, are readily available due to the Bayesian estimation framework of our method. Lastly, we identify some future avenues for research that may improve performance.

