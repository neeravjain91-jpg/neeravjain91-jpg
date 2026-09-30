# Hi, I'm Neerav Jain

### B.Tech CSE — Artificial Intelligence & Machine Learning

I build **machine learning systems, computer vision applications, intelligent data pipelines, and AI-powered engineering prototypes** with an emphasis on measurable evaluation, reproducibility, and real-world deployment.

---

## About Me

* 🎓 B.Tech CSE — AI/ML
* 🤖 Focused on **Machine Learning, Deep Learning, Computer Vision & AI Systems**
* 🔬 Interested in applied ML research and experimentation
* 🛠️ Building end-to-end systems from **data → modeling → evaluation → API → deployment**
* 📊 Interested in retrieval, classification, anomaly detection, metric learning, and spatiotemporal ML
* 🚀 Currently developing projects at the intersection of **AI, engineering systems, and real-world applications**

---

# Featured Projects

## 🚁 AeroPulse — AI Digital Twin for UAV Engine Health

AI-enabled Digital Twin and health-monitoring system for aero-piston UAV engines.

### Core Work

* Context-aware Digital Twin
* Physics/state-based engine simulation
* ML health classification
* Anomaly detection
* Sensor-trust and fault-evidence analysis
* Mission risk assessment
* Fault injection
* Mission replay
* RUL methodology
* FastAPI backend
* Real-time WebSocket telemetry
* GCS-style dashboard

### Primary Evaluation

| Metric                         |     Result |
| ------------------------------ | ---------: |
| Health Classification Accuracy | **89.47%** |
| Balanced Accuracy              | **89.29%** |
| Critical-State Recall          | **95.68%** |
| Critical-State Precision       | **63.88%** |
| Critical-State F1              |  **0.766** |
| Anomaly Detection AUROC        |  **0.960** |
| False Alarm Rate               |  **5.79%** |

### Evaluation Scope

The primary health-monitoring model is evaluated using **NASA ACES-based data**. The reported classification metrics describe the project's defined health-state classification task and should not be interpreted as real-world aircraft engine failure-prediction accuracy.

The anomaly detector is evaluated separately using the project's healthy-operation anomaly-detection setup.

Supporting components include CWRU vibration data and other datasets used for methodology validation rather than as direct evidence of UAV engine-failure prediction.

> Research/SIH prototype — not a certified flight-safety, airworthiness, maintenance-release, or operational defence system.

---

## ✍️ SYNAPSE — Intelligent Signature Verification & Fraud Risk Assessment

End-to-end signature verification platform combining biometric verification with transaction and behavioral risk assessment.

### Core Work

* Siamese Neural Network
* ResNet-based signature embeddings
* Classical SVM baseline
* Vision Transformer baseline
* Metric learning
* Image preprocessing and quality assessment
* Fraud-risk scoring
* Manual review workflow
* PostgreSQL / SQLite
* FastAPI
* Audit logging
* Docker & automated testing

### Three-Track Benchmark

| Model              |    ROC-AUC |        EER |   Accuracy |        FAR |        FRR | CPU Latency |
| ------------------ | ---------: | ---------: | ---------: | ---------: | ---------: | ----------: |
| SVM                |     0.8423 |     23.00% |     76.75% |     23.04% |     23.47% |      7.3 ms |
| Vision Transformer |     0.8118 |     24.50% |     75.50% |     24.51% |     24.49% |     38.4 ms |
| Siamese ResNet     | **0.9008** | **18.74%** | **81.50%** | **19.12%** | **17.86%** |     42.1 ms |

Additional benchmark work includes w
