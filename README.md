# Supervised-Research-Exposition

## Overview

This repository presents research on a Multi-Arm Bandit problem with K groups of arms, where each group contains N arms. The objective is to identify the group with the highest mean reward while ensuring that the minimum mean reward in the group exceeds a given threshold.

## General Successive Elimination

The algorithm involves maintaining an active set of arms, sampling from the reward distribution of each arm in the active set, and eliminating arms with estimated rewards outside the anytime confidence interval. The process continues until only one arm remains in the active set.


## Theorem 1
Show that with high probability (w.p) ≥ 1 − δ, Successive Elimination identifies the best arm in O(PΣi≠i∗ ∆−2i log(n log(∆−2i))) samples.


## Conclusion
This exposition outlines the General Successive Elimination algorithm for solving the Multi-Arm Bandit problem. The presented theorems and lemmas provide insights into the efficiency and accuracy of the algorithm in identifying the best arm.

For more details, refer to the full research document.



