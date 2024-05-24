# DaAIR



### Efficient Degradation-aware Any Image Restoration

#### [Eduard Zamfir<sup>1</sup>](https://eduardzamfir.github.io), [Zongwei Wu<sup>1</sup>](https://sites.google.com/view/zwwu/accueil), [Nancy Mehta<sup>1</sup>](https://scholar.google.com/citations?user=WwdYdlUAAAAJ&hl=en&oi=ao), [Danda Dani Paudel<sup>2,3</sup>](https://people.ee.ethz.ch/~paudeld/),  [Yulun Zhang<sup>4</sup>](http://yulunzhang.com/) and [Radu Timofte<sup>1</sup>](https://www.informatik.uni-wuerzburg.de/computervision/)

#### **<sup>1</sup> University of Würzburg, Germany - <sup>2</sup> INSAIT Sofia University, Bulgaria - <sup>3</sup> ETH Zürich, Switzerland - <sup>4</sup> Shanghai Jiao Tong University, China**

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org)
[![project](https://img.shields.io/badge/project-page-brightgreen)](https://eduardzamfir.github.io/daair/)


## Latest
- `05/24/2024`: Repository is created.

## Method:
<br>
<details>
  <summary>
  <font size="+1">Abstract</font>
  </summary>
Reconstructing missing details from degraded low-quality inputs poses a significant challenge. Recent progress in image restoration has demonstrated the efficacy of learning large models capable of addressing various degradations simultaneously. 
Nonetheless, these approaches introduce considerable computational overhead and complex learning paradigms, limiting their practical utility. 
In response, we propose DaAIR, an efficient All-in-One image restorer employing a Degradation-aware Learner (DaLe) in the low-rank regime to collaboratively mine shared aspects and subtle nuances across diverse degradations, generating a degradation-aware embedding. By dynamically allocating model capacity to input degradations, we realize an efficient restorer integrating holistic and specific learning within a unified model. 
Furthermore, DaAIR introduces a cost-efficient parameter update mechanism that enhances degradation awareness while maintaining computational efficiency.
Extensive comparisons across five image degradations demonstrate that our DaAIR outperforms both state-of-the-art All-in-One models and degradation-specific counterparts, affirming our efficacy and practicality.
</details>
