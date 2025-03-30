# **Stable Diffusion for Anomaly Detection in Multivariate Time Series**

## **Overview**
This project implements a **Stable Diffusion Model** for anomaly detection in **multivariate time series data**. The model leverages **anomaly scores** computed using the **MTAD-GAT model** as a **conditioning input** in the reverse diffusion process to improve anomaly detection accuracy.

## **Objective**
The model predicts whether a given **timestamp** is **anomalous** or **normal**, making it suitable for **real-world anomaly detection tasks** in time-series data.

## **Key Features**
✅ **Stable Diffusion Model for anomaly detection**  
✅ **Anomaly scores from MTAD-GAT used as conditioning input**  
✅ **Reverse diffusion process incorporates anomaly scores**  
✅ **Best F1-score optimization achieved: 0.96 F1-score**  
✅ **Requires a GPU for training on a new dataset**  


## **Performance**
- **F1-Score**: *0.96* (using best F1-score search method)

## **Applications**
This model can be applied to various **time-series anomaly detection tasks**, including:  
- 🏦 **Fraud Detection**  
- 🏭 **Industrial Equipment Monitoring**  
- 🌐 **Network Intrusion Detection**  
- 🏥 **Healthcare Anomaly Detection**  

## **Installation & Usage**

### **1️⃣ Setup AWS EC2 Instance (GPU Recommended)**
- Launch an **AWS EC2 instance** with a **GPU 

### **2️⃣ Clone the repository**
```bash
git clone https://github.com/JisnaP/stableDiffTSAD.git
cd stableDiffTSAD




