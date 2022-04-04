# Non-Parameteric-Bayesian-Approach-for-Uplift-Discretization-and-Feature-Selection

This repository contains the code of the paper entitled : Non-Parameteric Bayesian Approach for Uplift Discretization and Feature Selection submitted to  the conference ECML/PKDD 2022.

### Abstract:
Uplift modeling aims to estimate the incremental impact of a treatment, such as a marketing campaign or a drug, on an individual’s outcome. Uplift data of Bank or Telecom have often hundreds to thousands of features. In such situations, detection of irrelevant features is an essential step to reduce computational time and increase model performance. We present a parameter-free feature selection method for uplift modeling founded on a Bayesian approach. We start by defining UMODL an automatic feature discretization method for uplift. UMODL is based on a space of discretization models and a prior distribution. From this model space, we define a Bayes optimal evaluation criterion of a discretization model for uplift.  We then propose a O(n log n) optimization algorithm that finds near-optimal discretization for estimating uplift. Experiments demonstrate the high performances obtained by this new discretization method. Then we describe UMODL feature selection a parameter-free feature selection method for uplift. Experiments show that the new method both removes irrelevant features and achieves better performances than state of the art methods.

### CODE
The code consists of:

1. Greedy Search algorithm with post optimization
2. Experiments for UMODL evaluation
3. Experiments for UMODL feature selection


### Requirements
Python 3.7


