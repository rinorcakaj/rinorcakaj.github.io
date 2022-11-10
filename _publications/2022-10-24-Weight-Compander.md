---
title: "Weight Compander: A simple reparameterization for Regularization"
collection: publications
permalink: /publication/2022-10-24-Weight-Compander
excerpt: 'In this paper, we introduce
	**Weight Compander**, a novel effective method to improve generalization by
	reparameterizing each weight in deep neural networks using a nonlinear function.'
date: 2022-10-24
venue: ''
paperurl: ''
citation: 'Rinor Cakaj, Jens Mehnert, Bin Yang'
---
Regularization is a set of techniques that are used to improve the
generalization ability of deep neural networks. In this paper, we introduce
**Weight Compander**, a novel effective method to improve generalization by
reparameterizing each weight in deep neural networks using a nonlinear function.
It is a general, intuitive, cheap and easy to implement method, which can be
combined with various other regularization techniques. Large weights in deep
neural networks are a sign of a more complex network that is overfitted to the
training data. Moreover, regularized networks tend to have a greater range of
weights around zero with fewer weights centered at zero. We introduce a
weight reparameterization function which is applied to each weight and
implicitly reduces overfitting by restricting the magnitude of the weights while
forcing them away from zero at the same time. This leads to a more \emph{democratic}
decision-making in the network. Firstly, individual weights cannot have too much
influence in the prediction process due to the restriction of their magnitude.
Secondly, more weights are used in the prediction process, since they are forced
away from zero during the training. This promotes the extraction of more
features from the input data and increases the level of weight redundancy, which
makes the network less sensitive to statistical differences between training and
test data. We also extend our method to learn the hyperparameters of the introduced
weight reparameterization function. This avoids hyperparameter search and gives
the network the opportunity to align the weight reparameterization with the
training progress. We show experimentally that using weight compander in
addition to standard regularization methods improves the performance of neural
networks. Furthermore, we empirically analyze the weight distribution with and
without weight compander after training to confirm the companding effects of our
method on the weights.
