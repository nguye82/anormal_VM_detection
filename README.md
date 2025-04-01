## Anomalous VM Detection and Energy Analysis

# Overview

This project focuses on detecting anomalous Virtual Machines (VMs) with low energy efficiency using machine learning techniques. It analyzes cloud computing resource usage patterns to identify inefficiencies and suggest optimizations.

# Features

Anomaly Detection: Uses Isolation Forest to identify VMs with unusual resource usage patterns.

Energy Efficiency Analysis: Categorizes inefficient VMs based on CPU, memory, network, and power consumption.

Investigative Insights: Provides explanations, possible causes, and diagnostic methods for each anomaly type.

# Installation

Clone the repository:

git clone https://github.com/nguye82/anormal_VM_detection.git
cd anormal_VM_detection

Install dependencies:

pip install -r requirements.txt

Open and run the Jupyter Notebook:

jupyter notebook cloud_computer_energy_analysis.ipynb

# Usage

Load and preprocess VM resource usage data.

Train the Isolation Forest model for anomaly detection.

Analyze detected anomalies and categorize them based on inefficiency patterns.

Investigate the root causes of inefficiencies and suggest optimizations.

# Dataset

The project utilizes cloud VM resource metrics. Data can be found here (https://www.kaggle.com/datasets/abdurraziq01/cloud-computing-performance-metrics/data)

# Results

Identification of VMs with inefficient resource usage.

Classification of anomalies into predefined cases.

Insights into possible causes and investigative methods for each case
