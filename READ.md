# Autoscaling with GCP, Prometheus, and Grafana

## Objective:
This project demonstrates the setup of **auto-scaling** using **Google Cloud Platform (GCP)** and monitors the resource usage with **Prometheus** and **Grafana**. It automatically scales the instances in response to increased CPU and memory usage.

## Architecture:
The system consists of the following components:
- **Prometheus**: For monitoring resource usage (CPU, memory).
- **Grafana**: For visualizing the metrics collected by Prometheus.
- **Google Cloud Platform**: For managing and auto-scaling the virtual machines.

## Setup Instructions:
### 1. Clone the Repository:
Clone this repository to your local machine or VM:
```bash
git clone https://github.com/Surbhi0616/Autoscalingvcc2.git
cd Autoscalingvcc2
