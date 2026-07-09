# README – Experimental Data and Code for Three Variants of CMST Problem

This repository contains the complete experimental data, source code, and detailed numerical results for the PR-BPC on three variants of  Capacitated Minimum Spanning Tree (CMST) problem, as reported in the manuscript. The material is organized to support full reproducibility of the results presented in **Sections 7.1–7.4**.

## File Overview

We provide three primary data files (**CMST-D**, **CMST-L**, and **CMST-F**) and one supplementary file for algorithm feature analysis.

| File | Corresponding Section | Content Description |
|------|------------------------|----------------------|
| **CMST-D** | Section 7.1 | Instances, implementation code, and detailed computational results for the first set of experiments. |
| **CMST-L*** | Section 7.2 | Instances, implementation code, and detailed computational results for the second set of experiments. |
| **CMST-F** | Section 7.3 | Instances, implementation code, and detailed computational results for the third set of experiments. |

> Each of these files is self‑contained and includes:
> - The problem instances used (input data).
> - The executable code (or scripts) that produced the results.
> - The full output logs, tables, and performance metrics (e.g., solution quality, runtime, optimality gaps) discussed in the corresponding section.

Additionally, we provide:

| File | Corresponding Section | Content Description |
|------|------------------------|----------------------|
| **Algorithm_Feature_Impact** | Section 7.4 | Detailed experimental results for the impact of each algorithmic component enhancement. This file includes ablation studies, and comparative performance evaluations that support the conclusions drawn in Section 7.4. |

## How to Use These Files

- **Reproducing results**: Each file (CMST-D, CMST-L, CMST-F*) contains the exact code and data used to generate the reported numbers. Simply run the provided scripts in the same environment to reproduce the tables.
- **Understanding the output**: All result files are formatted with clear headers and explanatory comments. Refer to the paper’s Section 7 for the interpretation of each metric.
- **Feature impact analysis**: The `Algorithm_Feature_Impact` file can be used to examine the contribution of each algorithmic improvement.

## Requirements

The code is written in [Java ] and requires the  dependencies of Gurobi 12.0.1. All experiments were conducted on a Mac server; execution times may vary.
