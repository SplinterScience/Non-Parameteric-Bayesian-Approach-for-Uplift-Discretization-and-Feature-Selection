# A Non-Parameteric-Bayesian-Approach-for-Uplift-Discretization-and-Feature-Selection

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

### Supplementary material
<p float="left">
  ![image](https://user-images.githubusercontent.com/75427835/162019101-ebcebd91-907a-43a7-ad2a-12267836cc24.png)
  ![image](https://user-images.githubusercontent.com/75427835/162017588-fbceb4cf-ad5d-4e57-adcc-47b26ca2d4b3.png)
  </p>
Pattern: Descending


Result:



==========================================================================================
Pattern: Ascending
![image](https://user-images.githubusercontent.com/75427835/162019028-562a0624-7478-46f8-a7d1-3ca704c9b3a3.png)

![image](https://user-images.githubusercontent.com/75427835/162018046-cfaedbc3-a105-454d-84ff-04730397e38c.png)


==========================================================================================

Inverse X
![image](https://user-images.githubusercontent.com/75427835/162018136-9bbe826a-8483-4c64-aad3-7baee7f1d80c.png)

==========================================================================================
Positive Negative UNBALANCED
![image](https://user-images.githubusercontent.com/75427835/162019221-8bbb4d59-dabc-42c0-ad9c-2699188c8475.png)

![image](https://user-images.githubusercontent.com/75427835/162018305-cc9ecb5e-1db0-4cf7-82a5-3811ca9b1c9a.png)

==========================================================================================

Positive Zero UNBALANCED
![image](https://user-images.githubusercontent.com/75427835/162019167-3e19591f-d93f-4051-9a5d-b83a1679280e.png)

![image](https://user-images.githubusercontent.com/75427835/162018424-11544cba-6eb6-464c-b47b-a150429e38ce.png)







