---
permalink: /
title: "Summary of Works and Interests"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Currently pursuing a PhD in **Cardiovascular Digital Twins** at the University of Sheffield. My research interests center on an information-theoretic approach to inverse problems and parameter estimation. 

In my first year, I developed a novel high-performance parameter estimation algorithm by introducing significant modifications to the Unscented Kalman Filter (UKF), achieving a **100x performance increase** over traditional implementations. I am currently focusing on the practical implementation of these theoretical advancements to solve real-world clinical problems.

## Current Work 
The main body of my work focuses on the development of parameter estimation techniques for personalizing **0-dimensional lumped-parameter cardiovascular models**. I also conduct a broad range of additional work related to consultancy and the practical application of these new numerical methods.

---

## Advancements in the Unscented Kalman Filter
The Unscented Kalman Filter is traditionally used for state estimation in control theory. While it is a Bayesian-adjacent method, it has historically been ill-conditioned for parameter estimation. 

Previous implementation algorithms struggled due to rank-deficiency in the $P_{xy}$ and $P_{yy}$ matrices, which makes solving the system uniquely impossible. This led to major issues with the stability and performance of the algorithm. 

### Key Improvements:
* **The Kalman Interval:** The introduction of the interval $\tau_k$ served as the first significant major improvement to stability.
* **Rank Restoration:** My modifications resolved the rank-deficiency issues, leading to the full practical identifiability of a **10-parameter model** from just **4 continuous observations**.
* **Efficiency:** These optimisations provided a **100x performance increase**, moving the theory closer to real-time clinical utility.



---

## Publications
**BREAKING RANK — A Novel Unscented Kalman Filter for Parameter Estimations of a Lumped-Parameter Cardiovascular Model** *Alex Thornton, Prof Ian Halliday, Dr Harry Saxton, Dr Xu Xu* [arXiv:2601.02390](https://arxiv.org/pdf/2601.02390)

---

## Technical Skills
**Domain Expertise**: Inverse Problems, Parameter Estimation, Statistical Physics, Information Theory 
**Modelling**: Cardiovascular Digital Twins, Biological Systems, Physical Systems, Numerical Modelling 
**Programming**: **Julia** (Fluent), **Python** (Competent), **R, C++, Matlab** (Familiar) |

---

## Academic Background
* **PhD in Theoretical Computational Medicine** *University of Sheffield* (Current)
* **MSc in Data Science** *University of Leeds* (Thesis: Complexity Theory)
* **BSc in Physics** *University of Birmingham* (Research: Machine Learning and Robotics)
