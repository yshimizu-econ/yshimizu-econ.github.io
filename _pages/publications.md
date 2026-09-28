---
layout: page
permalink: /Research/
title: Research
nav: true
nav_order: 1
---

#### <b>Job Market Paper</b>

<h5>
     <a href="https://yshimizu-econ.github.io/assets/pdf/Shimizu_JMP_Embedding.pdf" target="_blank" rel="noopener noreferrer">Econometrics with Pre-Trained Embeddings for Unstructured Data</a>
</h5>
<small style="color: gray;">presentation: Econometric Society Interdisciplinary Frontiers Conference on Economics and AI+ML (Ithaca), Chicago Booth AI and Economics Summer Conference, Midwest Econometrics Group (Cincinnati, scheduled), Canadian Econometrics Study Group (Vancouver, scheduled), Southern Economic Association (Houston, scheduled)</small><br>
<!-- [<a href="https://github.com/">R Package</a>]<br> -->
<!-- [<a href="https://arxiv.org/abs/2607.17378">arXiv</a>]<br> -->
<details>
  <summary>Abstract</summary>
  <p>
    Unstructured data, such as images and text, are increasingly used in empirical economics. Since training machine-learning models on unstructured data is costly, economists often use off-the-shelf pre-trained deep learning models developed by computer scientists to extract embeddings, which are then used as covariates in target economic analyses. Despite the popularity of this practice, its theoretical foundations remain limited. There are two main difficulties. First, pre-trained models are typically trained on different datasets and for different tasks, making it unclear when they can be used reliably for the target task. Second, the embedding function is subject to an identification problem, complicating the analysis of its estimation error and the effect of that error on the target task. We provide sufficient conditions to overcome these difficulties. A key condition, which we call transferability, governs the convergence rate we derive. This rate depends on three components: target estimation error with the pre-trained embeddings treated as standard covariates, source estimation error adjusted for the strength of transferability, and approximation error of the target model class using embeddings as inputs. We also extend this analysis for high-dimensional embeddings. To assess transferability, we develop a computationally feasible bootstrap test that does not require re-estimating the embeddings and nuisance functions. Our theory applies to a wide range of double machine learning applications, including partially linear regression with unstructured controls, price elasticity estimation in demand models accounting for product quality measured by images and text, missing-data imputation using unstructured data, and average treatment effect estimation with unstructured confounders. As an empirical application, we estimate the labor supply elasticity on Amazon Mechanical Turk, an online labor market platform, using job-description embeddings as controls.
  </p>
</details>
<br>









#### <b>Working Papers</b>

<h5>
     <a href="https://arxiv.org/abs/2506.22989" target="_blank" rel="noopener noreferrer">Design-Based and Network Sampling-Based Uncertainties in Network Experiments</a>
</h5>
<!-- [<a href="https://github.com/">R Package</a>]<br> -->
with <a href="https://kensakamot.github.io/" target="_blank" rel="noopener noreferrer">Kensuke Sakamoto</a>.<br>
<em>Revision Requested at <b>Review of Economics and Statistics</b></em> <br>
<details>
  <summary>Abstract</summary>
  <p>
    Ordinary least squares (OLS) estimators are widely used in network experiments to estimate spillover effects. We study the causal interpretation of, and inference for the OLS estimator under both design-based uncertainty from random treatment assignment and sampling-based uncertainty in network links. We show that correlations among regressors that capture the exposure to neighbors' treatments can induce contamination bias, preventing the OLS from aggregating heterogeneous spillover effects for clear causal interpretation. We derive the OLS estimator's asymptotic distribution and propose a network-robust variance estimator. Simulations and an empirical application demonstrate that contamination bias can be substantial, leading to inflated spillover estimates.
  </p>
</details>
<br>


<h5>
  <a href="https://arxiv.org/abs/2403.16413" target="_blank" rel="noopener noreferrer">Optimal Testing in a Class of Nonregular Models</a>
</h5>
<!-- [<a href="https://github.com/">R Package</a>]<br> -->
with <a href="https://personal.lse.ac.uk/otsu/" target="_blank" rel="noopener noreferrer">Taisuke Otsu</a>.<br>
<em>Revision Requested at <b>Econometric Theory</b></em> <br>
<details>
  <summary>Abstract</summary>
  <p>
    This paper studies optimal hypothesis testing for nonregular econometric models with parameter-dependent support. We consider both one-sided and two-sided hypothesis testing and develop asymptotically uniformly most powerful tests based on a limit experiment. Our two-sided test becomes asymptotically uniformly most powerful without imposing further restrictions such as unbiasedness, and can be inverted to construct a confidence set for the nonregular parameter. Simulation results illustrate desirable finite sample properties of the proposed tests.
  </p>
</details>
<br>



<h5>
     <a href="https://arxiv.org/abs/2510.27633" target="_blank" rel="noopener noreferrer">Testing Inequalities Linear in Nuisance Parameters</a>
</h5>
<!-- [<a href="https://github.com/">R Package</a>]<br> -->
With <a href="https://sites.google.com/site/gregoryfcox/" target="_blank" rel="noopener noreferrer">Gregory Cox</a> and <a href="https://users.ssc.wisc.edu/~xshi/" target="_blank" rel="noopener noreferrer">Xiaoxia Shi</a>.<br>
<details>
  <summary>Abstract</summary>
  <p>
    This paper proposes a new test for inequalities that are linear in possibly partially identified nuisance parameters. This type of hypothesis arises in a broad set of problems, including subvector inference for linear unconditional moment (in)equality models, specification testing of such models, and inference for parameters bounded by linear programs. The new test uses a two-step test statistic and a chi-squared critical value with data-dependent degrees of freedom that can be calculated by an elementary formula. Its simple structure and tuning-parameter-free implementation make it attractive for practical use. We establish uniform asymptotic validity of the test, demonstrate its finite-sample size and power in simulations, and illustrate its use in an empirical application that analyzes women's labor supply in response to a welfare policy reform.
  </p>
</details>
<br>














<!--
#### <b>Work in Progress</b>
<h5>
  Econometrics with Pre-Trained Embeddings for Unstructured Data [draft coming soon]
</h5>
[<a href="https://github.com/">R Package</a>]<br>
With <a href="https://sites.google.com/site/gregoryfcox/">Gregory Cox</a> and <a href="https://users.ssc.wisc.edu/~xshi/">Xiaoxia Shi</a>.<br>
[Draft coming soon]<br>





<br>
-->



#### <b>Publication</b>
<h5>
  <a href="https://yshimizu-econ.github.io/assets/pdf/NonparaCluster2025.pdf" target="_blank" rel="noopener noreferrer">Nonparametric Regression under Cluster Sampling</a>
</h5>
<em><b>Journal of Econometrics</b> (2025)</em> <br>
<em>Award: Kanematsu Prize 2023</em> <br>
[<a href="https://arxiv.org/abs/2403.04766" target="_blank" rel="noopener noreferrer">arXiv</a> | <a href="https://github.com/yshimizu-econ/Nonparametric-Regression-under-Cluster-Sampling" target="_blank" rel="noopener noreferrer">R code</a>]<br>
<details>
  <summary>Abstract</summary>
  <p>
    This paper develops a general asymptotic theory for nonparametric kernel regression in the presence of cluster dependence. We examine nonparametric density estimation, Nadaraya-Watson kernel regression, and local linear estimation. Our theory accommodates growing and heterogeneous cluster sizes. We derive asymptotic conditional bias and variance, establish uniform consistency, and prove asymptotic normality. Our findings reveal that under heterogeneous cluster sizes, the asymptotic variance includes a new term reflecting within-cluster dependence, which is overlooked when cluster sizes are presumed to be bounded. We propose valid approaches for bandwidth selection and inference, introduce estimators of the asymptotic variance, and demonstrate their consistency. In simulations, we verify the effectiveness of the cluster-robust bandwidth selection and show that the derived cluster-robust confidence interval improves the coverage ratio. We illustrate the application of these methods using a policy-targeting dataset in development economics.
  </p>
</details>
<br>










#### <b>Pre-Ph.D. Publication</b>
<h5>
  <a href="https://onlinelibrary.wiley.com/doi/epdf/10.1002/sta4.241" target="_blank" rel="noopener noreferrer">Doubly Robust-type Estimation of Population Moments and Parameters in Biased Sampling</a>
</h5>
<!-- [<a href="https://github.com/">R Package</a>]<br> -->
With <a href="https://k-ris.keio.ac.jp/html/100000523_en.html" target="_blank" rel="noopener noreferrer">Takahiro Hoshino</a>.<br>
<em><b>Stat</b> (2019)</em>
<br>







<div style="height: 1em;"></div>

#### <b>Translation Work</b>
<h5>
  Imbens, G. W. and D. B. Rubin,
  “Causal Inference for Statistics, Social, and Biomedical Sciences: An Introduction,”
  (<a href="https://www.asakura.co.jp/detail.php?book_code=12291" target="_blank" rel="noopener noreferrer">translation into Japanese</a>; responsible for Chapters 15 and 16)
</h5>
<em>Asakura Publishing (2023)</em> <br>
