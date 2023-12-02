---
title: "A Reduced Order Schwarz Method for Nonlinear Multiscale Elliptic Equations Based on Two-Layer Neural Networks"
collection: publications
permalink: /publication/2021-11-03-paper-reduced-number-5
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-11-03
pubdate: 2023-03-28
venuestatus: 'Published in'
venue: 'Journal of Computational Mathematics'
cauthor: 'Zhiyan Ding, Qin Li and Stephen J. Wright'
paperurl: 'https://doi.org/10.4208/jcm.2204-m2021-0311'
arxivurl: 'https://arxiv.org/abs/2111.02280'
codeurl: 'https://github.com/simonchenthu/nn_reduced_Schwarz'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
imgurl: /images/reduced-img.png
imgcap: Despite the high-dimensionality of input and output space, the boundary-to-boundary operator in Schwarz iteration is an essentially low-dimensional operator that can be efficiently approximated by neural networks
imgfloat: left
imgwidth: 250px
---
Neural networks are powerful tools for approximating high dimensional data that have been used in many contexts, including solution of partial differential equations (PDEs). We describe a solver for multiscale fully nonlinear elliptic equations that makes use of domain decomposition, an accelerated Schwarz framework, and two-layer neural networks to approximate the boundary-to-boundary map for the subdomains, which is the key step in the Schwarz procedure. Conventionally, the boundary-to-boundary map requires solution of boundary-value elliptic problems on each subdomain. By leveraging the compressibility of multiscale problems, our approach trains the neural network offline to serve as a surrogate for the usual implementation of the boundary-to-boundary map. Our method is applied to a multiscale semilinear elliptic equation and a multiscale p-Laplace equation. In both cases we demonstrate significant improvement in efficiency as well as good accuracy and generalization performance.