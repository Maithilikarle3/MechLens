# MechLens
# 🏭 Industrial Data Classification using Stacked Transformer  

## 🔍 Introduction  
This project implements a **Stacked Transformer-based Model** for classifying industrial machine efficiency based on real-time operational metrics. The model utilizes **multi-head self-attention** to analyze time-series data, helping in predictive maintenance and efficiency analysis.  

---

## 📌 Application  
- **Predictive Maintenance:** Identifies patterns in machine performance to prevent failures  
- **Operational Optimization:** Helps industries improve efficiency based on real-time data  
- **Anomaly Detection:** Detects irregular behavior in industrial machines  

---
## 🚀 Model Architecture  

### **1. Stacked Transformer Model**  
- **Embedding Layer:** Projects input features to higher-dimensional space  
- **Transformer Blocks:**  
  - Multi-head self-attention  
  - Feedforward layers with ReLU activation  
  - Layer normalization and dropout for stability  
- **Output Layer:** Predicts the efficiency status (`Low`, `Medium`, `High`)  

---
