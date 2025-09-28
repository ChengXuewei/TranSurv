# TranSurv

TranSurv: A Transformer-Based Deep Learning Framework for Enhanced Survival Prediction

Xuewei Cheng, Shu Kay Ng, and Hong Wang

Abstract: Building a deep learning-based survival model for right-censored data that fully exploits the powerful representational capacity of deep neural networks remains highly challenging. Existing deep survival models suffer from two main limitations: (1) Cox-based models are limited in their capacity to model complex, global interactions among features; and (2) discrete-time approaches are susceptible to bias induced by time discretization and often require large sample sizes for stable estimation. To address these issues, this paper introduces TranSurv, a novel survival model based on the Transformer architecture, which employs a regularized negative log partial likelihood function to model the log-risk function. The proposed model not only captures complex nonlinear and non-proportional log-risk relationships but also employs the self-attention mechanism to efficiently characterize global dependencies among covariates. We extensively validate the effectiveness and robustness of TranSurv through comprehensive simulation studies and real-world data analyses.




## Environment

* CUDA 12.6
* torch 2.5.1+cu121
* torchvision   0.20.1+cu121

## Create a virtual environment with conda

```bash
conda create -n TranSurv python=3.9.20
conda activate TranSurv
pip install -r requirements.txt
```

