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

## Featured Projects

### 🚁 AeroPulse — AI Digital Twin for UAV Engine Health

AI-enabled Digital Twin and health-monitoring system for aero-piston UAV engines.

**Core work**

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

**Research data:** NASA ACES, with supporting CWRU vibration research and other methodology datasets.

> Research/SIH prototype — not a certified flight-safety or airworthiness system.

---

### ✍️ SYNAPSE — Intelligent Signature Verification & Fraud Risk Assessment

End-to-end signature verification platform combining biometric verification with transaction and behavioral risk assessment.

**Core work**

* Siamese Neural Network
* ResNet-based signature embeddings
* Classical SVM baseline
* Vision Transformer baseline
* Metric learning
* Image preprocessing and quality assessment
* Fraud-risk scoring
* Manual review workflow
* PostgreSQL/SQLite
* FastAPI
* Audit logging
* Docker & automated testing

**Benchmark**

| Model              |    ROC-AUC |        EER |   Accuracy | CPU Latency |
| ------------------ | ---------: | ---------: | ---------: | ----------: |
| SVM                |     0.8423 |     23.00% |     76.75% |      7.3 ms |
| Vision Transformer |     0.8118 |     24.50% |     75.50% |     38.4 ms |
| Siamese ResNet     | **0.9008** | **18.74%** | **81.50%** |     42.1 ms |

Evaluation uses writer-separated CEDAR cohorts.

---

### 🔥 India Forest Fire Prediction

India-wide forest-fire occurrence prediction using satellite fire detections and multi-timescale meteorological data.

**Pipeline**

* NASA FIRMS / VIIRS fire detections
* ERA5-Land meteorological data
* Spatial grid construction
* 1-day / 3-day / 7-day weather features
* Temporal feature engineering
* HistGradientBoosting
* Temporal train/validation/test separation
* Spatial generalization analysis
* Live FIRMS visualization

**Test-set results**

* Accuracy: **70.01%**
* Precision: **68.47%**
* Recall: **74.21%**
* F1: **71.22%**
* ROC-AUC: **78.52%**
* PR-AUC: **78.32%**

The ML model is a research prediction/classification system; the live FIRMS component provides observed fire detections rather than predictions.

---

### 🔎 DeepResolve ER — Amazon ML Challenge

Business Entity Resolution system designed for large-scale matching of business records.

**Architecture**

* Multi-channel candidate blocking
* Normalized-name matching
* Legal-suffix normalization
* Token sorting
* Address/numeric blocking
* Pairwise similarity features
* Hard-negative mining
* LightGBM ranking/classification
* Adaptive decision thresholds
* Memory-bounded inference

**Validation**

* Macro F0.5: **0.81172**
* Precision: **0.88801**
* Recall: **0.66169**
* Singleton accuracy: **0.89933**
* Candidate retrieval experiments reaching substantially higher candidate recall through additional blocking strategies
* Streaming inference designed for low memory usage

The project focuses on the complete entity-resolution pipeline rather than only the final classifier.

---

### 🛣️ Road Guardian AI

Computer-vision system for automated pothole detection and road-condition reporting.

**Technology**

* YOLO
* OpenCV
* GPS
* Python
* Pandas
* Geotagged detection
* Automated reporting

Pipeline:

`Camera → Object Detection → Confidence Filtering → GPS/Time → Evidence → Road Report`

---

## Technical Stack

### Machine Learning

`Python` · `Scikit-learn` · `PyTorch` · `LightGBM` · `Hugging Face Transformers`

### Deep Learning

`CNNs` · `ResNet` · `Siamese Networks` · `Metric Learning` · `Vision Transformers`

### Computer Vision

`OpenCV` · `YOLO` · `Image Preprocessing` · `Feature Extraction`

### Data & Scientific Computing

`Pandas` · `NumPy` · `Matplotlib` · `ERA5-Land` · `NASA FIRMS`

### Backend & Systems

`FastAPI` · `Flask` · `REST APIs` · `WebSockets` · `SQLAlchemy`

### Databases

`PostgreSQL` · `SQLite`

### Engineering

`Git` · `GitHub` · `Docker` · `CI/CD` · `Pytest`

---

## What I Work On

```text
Data
  ↓
Data Cleaning & Validation
  ↓
Feature Engineering
  ↓
Baseline Models
  ↓
Experimentation
  ↓
Error / Failure Analysis
  ↓
Model Improvement
  ↓
Evaluation
  ↓
API / System Integration
  ↓
Deployment
```

I am particularly interested in projects where the ML model is only one component of a larger system.

---

## Current Focus

* Advanced Machine Learning
* Deep Learning
* Computer Vision
* Retrieval & Entity Resolution
* Spatiotemporal ML
* Anomaly Detection
* AI-powered engineering systems
* ML experimentation and evaluation
* Production-oriented ML architecture

---

## Selected Repositories

| Project                         | Area                                       |
| ------------------------------- | ------------------------------------------ |
| 🚁 AeroPulse                    | AI + Digital Twin + Predictive Maintenance |
| ✍️ SYNAPSE                      | Deep Learning + Biometrics + Risk          |
| 🔥 India Forest Fire Prediction | Spatiotemporal ML                          |
| 🔎 DeepResolve ER               | Retrieval + Entity Resolution              |
| 🛣️ Road Guardian AI            | Computer Vision                            |

---

## GitHub

[![GitHub](https://img.shields.io/badge/GitHub-neeravjain91--jpg-181717?style=for-the-badge\&logo=github)](https://github.com/neeravjain91-jpg)

---

> Building systems that move beyond notebooks — from data and experiments to deployable AI applications.
