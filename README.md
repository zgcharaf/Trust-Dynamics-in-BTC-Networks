# Trust Dynamics in the BTC Alpha Network: Analyzing Impact and Predicting Changes 📊

**Authors:** Gwendoline Hays-Valentin & Charaf Zguiouar  
**Date:** April 3, 2024  
**Institution:** University Paris 1 Panthéon-Sorbonne 🏛️

## Project Overview 🌐

This project investigates the dynamics of trust within the BTC Alpha cryptocurrency network by analyzing transaction data to identify anomalies and predict potential drops in network confidence. By employing the Isolation Forest algorithm to detect anomalous transactions indicative of unusual trust-related behavior, and subsequent analysis with a machine learning model, this study correlates trust pattern anomalies with historical events known to affect network confidence, such as the Bitcoin hack of February 2014.

## Dataset 📁

The BTC-Alpha network dataset encompasses interactions between 5,881 users, documented through 35,592 trust/distrust relationships. Trust levels range from -10 (total distrust) to +10 (total trust), with 89% of these relationships being positive. This unique dataset allows for in-depth exploration of trust dynamics and their influence on behavior within cryptocurrency networks.

## Contents 📑

1. **Descriptive Statistics**
   - Overview of the dataset and initial exploratory data analysis (EDA).

2. **Network Plots**
   - Visualization and statistical analysis of trust and mistrust relationships within the network.
   - Community detection and analysis over time.

3. **Questions and Answers**
   - Simulation of trust dynamics using the Independent Cascade Model to assess market impact due to a significant drop in confidence.
   - Machine learning predictions on community retention and shifts during times of crisis, focusing on the Mt. Gox Hack and employing XGBoost for predictive modeling.

4. **Conclusion**
   - Summary of findings, contributions of the study, and potential implications for the design of robust, trust-based systems in decentralized financial networks.

## How to Use 🛠️

This repository contains Jupyter notebooks for each section of the analysis, along with the necessary datasets and a Python environment file for replicating the study:

- `Valentin_Zguiouar`: Main notebook for running the analyses described above.
- `data/`: Folder containing the BTC-Alpha network dataset.

## Bibliography 📚

- Refer to the `Bibliography` section in the study for detailed references and sources used throughout this research.



