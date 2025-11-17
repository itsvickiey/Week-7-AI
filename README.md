# COMPAS Dataset Bias Audit

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![AI Fairness](https://img.shields.io/badge/AI%20Fairness-360-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive bias audit of the COMPAS recidivism algorithm using IBM's AI Fairness 360 toolkit. This project analyzes racial disparities in risk assessment scores and provides remediation recommendations.

## 📋 Project Overview

This audit examines the COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) dataset for racial bias in recidivism predictions. The analysis follows ProPublica's methodology and uses statistical fairness metrics to quantify disparities between African-American and Caucasian defendants.

## 🎯 Key Findings

- **False Positive Rate Disparity**: African-American defendants have 2x higher false positive rates (24.7% vs 12.3%)
- **Statistical Parity Difference**: -0.143, indicating systematic bias
- **Disparate Impact Ratio**: 0.676 (below 0.8 fairness threshold)
- **Error Rate Imbalance**: Significant racial disparities in prediction errors

## 🛠️ Installation

```bash
# Clone repository
git clone https://github.com/your-username/compas-bias-audit.git
cd compas-bias-audit

# Install requirements
pip install -r requirements.txt
