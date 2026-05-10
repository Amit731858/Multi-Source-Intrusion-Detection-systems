
# Multi-Source Intrusion Detection Framework

A machine learning based intrusion detection framework developed to detect cyber attacks using multi-source datasets including network traffic, host statistics, and system logs.

## Overview

This project creates a controlled virtual cybersecurity environment using Kali Linux, Ubuntu, and Metasploitable2 virtual machines to simulate attacks such as:

- DoS (Denial-of-Service)
- Ransomware

The collected data from multiple sources is processed and used to train machine learning models for intrusion detection.

## Features

- Multi-source dataset generation
- Packet flow analysis
- Host statistics monitoring
- System log analysis
- Machine Learning based attack detection
- SHAP explainability analysis

## Experimental Setup

- Kali Linux (Attacker)
- Ubuntu (Monitoring System)
- Metasploitable2 (Target Machine)
- Oracle VirtualBox

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SHAP
- Wireshark
- CICFlowMeter
- Argus
- rsyslog
- atop
- Linux

## Machine Learning Models

- Random Forest
- XGBoost

## Results

- Achieved up to **99.5% accuracy** for DoS attack detection
- Achieved up to **98.3% accuracy** for ransomware detection
- Multi-source datasets improved overall detection performance

## Project Structure

```bash
dataset/
models/
notebooks/
scripts/
results/
report/
```

## Future Improvements

- Real-time intrusion detection
- Deep learning based IDS
- Cloud & IoT attack detection
- Automated response systems

## Author

Amit Maurya  
M.Sc. Mathematics and Computing  
IIT Guwahati
