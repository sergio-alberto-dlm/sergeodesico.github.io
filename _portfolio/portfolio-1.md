---
title: "DynaMiTE: Towards Robust 2D Gaussian Splatting-based camera localization"
excerpt: "<br/><img src='/images/demo_dynamite_ANYmal1.gif'>"
collection: portfolio
---

In this work we introduce a module based on Gaussian Process to distinguish between static and dynamic elements in a 2D Gaussian Splatting-based SLAM system. This module is learned on the fly and naturally computes an estimation of the uncertainty of predictions. Go to the [project webpage](https://sergio-alberto-dlm.github.io/dynamite/)

<!-- We take as supervision a robust residual that considers high level differences between render and original key-frames (contrast, luminescence and structure), we then assume that this residual is parametrized by semantic features provided by an off-the-shelf backbone (DINOv2), we then train a GP to predict the residual of following frames. Since compute the exact posterior will be computationally expensive we opt for a variational approach that considers a family of surrogated functions which are optimized towards the real posterior leveraging stochastic gradient descent and taking the ELBO as target. Additionally to keep a compact dataset we make active point selection. -->
