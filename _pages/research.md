---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---


## Block-coordinate BFGS for convex non-smooth optimization (with Michael O’Neill)  
I study a block-coordinate BFGS method for convex non-smooth optimization problems with overlapping group regularizers. The idea is to combine the curvature information of quasi-Newton methods with the structural advantages of block-coordinate descent: at each iteration, we update a block-specific approximation to the Hessian while respecting the sparsity pattern induced by groups. On the theory side, I focus on establishing convergence under mild assumptions and understanding when blockwise curvature updates help compared to first-order methods. On the empirical side, I compare the method to proximal-gradient–type baselines on synthetic and real datasets, looking at both convergence speed and solution quality for large-scale structured problems.

Manuscript in preparation for submission to _Computational Optimization and Applications_. Draft available [here]({{ '/files/Block_BFGS_paper.pdf' | relative_url }}).

---

## Data-Driven EMS Stroke Triage under Missed-Stroke Constraints (with Ali Parlaktürk, Chudi Zhong)  
We linked EMS–hospital data to study how machine learning and constrained classification can improve prehospital stroke triage. Current EMS screening tools are designed to be simple and fast, but they can miss clinically important stroke cases or flag too many non-stroke patients. I am working on models that use a richer feature set while explicitly constraining error trade-offs, for example by enforcing an upper bound on the false negative rate or by prioritizing performance in low–false-positive regions of the ROC curve. The broader goal is to translate these models into decision rules that are interpretable enough for EMS use and compatible with downstream stroke workflows in the hospital.

_Manuscript in Progress_
 
