# Bayesian Network Analysis of Water Quality in the River Trent

## Project Overview
Large river monitoring networks generate vast volumes of data, yet not all monitoring locations contribute equally to understanding system-wide water quality dynamics.

This project develops an **interpretable Bayesian Network framework constrained by river topology** to identify which monitoring sites in the **River Trent and its major tributaries** provide the greatest predictive value across multiple water quality determinands.  
The objective is to support **monitoring optimisation and evidence-based environmental decision-making** by quantifying informational redundancy and influence across the network.

This repository contains the **full reproducible analysis pipeline** developed as part of a Master’s dissertation in Data Science.

---

## Problem Statement
Environmental agencies face increasing pressure to optimise monitoring strategies while maintaining high-quality inference across large river systems. Traditional analyses often treat monitoring sites independently, overlooking **hydrological structure and information flow**.

This project addresses the question:

**Which monitoring locations contribute the most to predicting water quality across the entire river network, and which provide redundant information?**

---

## Methodology Overview
The analysis integrates probabilistic modelling, network theory, and spatial analysis to ensure both **statistical rigor and physical plausibility**.

Key components include:

- **River-constrained Bayesian Networks**  
  Directed acyclic graphs constructed to respect downstream hydrological flow.

- **Monthly aggregation and categorical discretisation**  
  Continuous measurements aggregated to reduce noise and discretised using entropy-preserving methods.

- **Node relevance quantification using complementary metrics**  
  - **Mutual Information** to measure global informational contribution  
  - **Markov blanket size** to capture local structural importance

- **Spatial mapping of influential nodes**  
  High-impact sites visualised to support monitoring prioritisation.

This dual-metric approach balances **system-wide predictability** with **local network influence**, providing interpretable insights rather than black-box predictions.

---

## Analysis Pipeline
The project follows a modular, reproducible pipeline designed to mirror real-world analytical workflows.

Raw monitoring data are progressively transformed into interpretable network-based insights through the following stages:

