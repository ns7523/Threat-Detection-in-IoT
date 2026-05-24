<div align="center">
  <br />
  <img src="https://via.placeholder.com/120x120/0a0a0a/ffffff?text=Threat+Det" alt="Threat Detection Icon" />
  <br />

  <h1 align="center">Threat Detection in IoT</h1>

  <p align="center">
    <strong>Intelligent Machine Learning Architecture for Enhancing IoT Security Posture.</strong>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Accuracy-90%25-success?style=flat-square" alt="Accuracy">
    <img src="https://img.shields.io/badge/Framework-TensorFlow-orange?style=flat-square&logo=tensorflow" alt="TensorFlow">
    <img src="https://img.shields.io/badge/Python-3.8+-black?style=flat-square&logo=python" alt="Python">
  </p>
</div>

<br />

## Overview

This project provides an advanced, scalable threat detection engine tailored for Internet of Things (IoT) ecosystems. Utilizing comprehensive machine learning pipelines, the system analyzes high-throughput IoT telemetry to identify anomalous patterns indicative of security breaches, providing robust defense mechanisms for edge networks.

[View Full Research Report & Artifacts](https://drive.google.com/file/d/1JL_SB7ZA1FG9mH_b_VMA6hgqIiiG2FaW/view?usp=sharing)

### Engineering & Security Significance
As IoT device deployments scale exponentially, traditional signature-based detection becomes computationally unviable. This architecture shifts the paradigm toward intelligent anomaly detection, utilizing a model trained on over 800,000 traffic variations to achieve 90% precision and recall metrics.

<br />

## System Architecture

<table>
  <tr>
    <th align="center">Chosen System Design Topology</th>
  </tr>
  <tr>
    <td align="center"><img width="600" alt="Architecture" src="https://github.com/user-attachments/assets/8d90513a-3edd-47d7-865a-4f86e20ff3dd"></td>
  </tr>
</table>

<br />

## Core Features

- **Algorithmic Anomaly Detection**: Capable of isolating zero-day attack vectors through deviation mapping.
- **Enterprise Scalability**: Designed to ingest parallel telemetry streams via MQTT/HTTP without performance degradation.
- **Interactive SOC Dashboard**: Comprehensive web-based visualization for immediate threat triage and device status tracking.
- **Customizable Alerting Logic**: Threshold-based alerting for varied severity levels.

<br />

## Tech Stack

| Layer | Technologies |
| --- | --- |
| **ML Inference Engine** | Python, TensorFlow, Scikit-learn |
| **Data Processing** | Pandas, NumPy |
| **Network Protocols** | MQTT, HTTP, CoAP |
| **Persistence** | MongoDB, SQLite |
| **Visualization & UI** | Grafana, Matplotlib, Custom Web Dashboard |

<br />

## Quick Start

### Prerequisites
It is highly recommended to use **Anaconda Navigator** as the base environment to prevent dependency conflicts.

### Deployment

```bash
# Clone the repository
git clone https://github.com/ns7523/Threat-Detection-in-IoT.git
cd Threat-Detection-in-IoT

# Initialize the application server
python app.py
```
Access the local Security Operations Center (SOC) dashboard via `localhost`.

<br />

## Performance Metrics

Extensive validation against massive simulated traffic datasets yields the following inference metrics:

- **Global Accuracy**: `90.0%`
- **Precision**: `90.0%`
- **Recall**: `90.0%`

*Binary Output Configuration: `1` (Attack Detected), `0` (Benign Traffic).*

<br />

## Visual Interface

<table>
  <tr>
    <th align="center">Threat Analytics Engine</th>
    <th align="center">Prediction Results Matrix</th>
  </tr>
  <tr>
    <td align="center"><img width="400" alt="Prediction" src="https://github.com/user-attachments/assets/8021707d-c790-4686-b7bb-5d347fa563ce"></td>
    <td align="center"><img width="400" alt="Results" src="https://github.com/user-attachments/assets/b05e5097-00b0-4fa0-a6ea-c8b6090b6fbd"></td>
  </tr>
</table>

<br />

<div align="center">
  <br />
  <sub>Security Architecture by <a href="https://github.com/ns7523">N S AKASH</a></sub>
  <br />
  <sub>Contact: nsakash752003@gmail.com</sub>
</div>
