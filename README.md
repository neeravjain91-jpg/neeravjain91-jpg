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

Additional benchmark work includes writer-separated evaluation on a frozen test cohort.

> Production-oriented research prototype; biometric performance depends on dataset, writer population, image quality, and operating threshold.

---

## 🔥 India Forest Fire Prediction

India-wide forest-fire occurrence prediction using satellite fire detections and multi-timescale meteorological data.

### Pipeline

* NASA FIRMS / VIIRS fire detections
* ERA5-Land meteorological data
* Spatial grid construction
* 1-day / 3-day / 7-day weather features
* Temporal feature engineering
* HistGradientBoosting
* Temporal train/validation/test separation
* Spatial generalization analysis
* Live FIRMS visualization

### Dataset

* **131,000 observations**
* **2018–2025**
* **26,494 spatial cells**
* **65,518 fire observations**
* **65,482 non-fire observations**
* Zero missing values in final model features

### Test-Set Results

| Metric    |     Result |
| --------- | ---------: |
| Accuracy  | **70.01%** |
| Precision | **68.47%** |
| Recall    | **74.21%** |
| F1 Score  | **71.22%** |
| ROC-AUC   | **78.52%** |
| PR-AUC    | **78.32%** |

The model uses historical weather and spatial-temporal information to classify fire occurrence.

The live FIRMS component provides **observed satellite fire detections** and should not be confused with the ML model's predictions.

> Research and demonstration system — not an operational emergency fire-warning service.

---

## 🔎 DeepResolve ER — Amazon ML Challenge

Large-scale **Business Entity Resolution** system developed for the Amazon ML Challenge 2026.

### Architecture

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

### Validation Results

| Metric              |      Result |
| ------------------- | ----------: |
| Macro F0.5          | **0.81172** |
| Precision           | **0.88801** |
| Recall              | **0.66169** |
| Singleton Accuracy  |  **89.93%** |
| Candidate Retrieval |  **85.62%** |
| Reduction Ratio     | **99.991%** |

The project focuses on the complete entity-resolution pipeline:

```text
Raw Business Records
        ↓
Normalization
        ↓
Candidate Blocking
        ↓
Candidate Retrieval
        ↓
Pairwise Features
        ↓
Hard-Negative Training
        ↓
LightGBM
        ↓
Adaptive Decision Engine
        ↓
Resolved Entities
```

Additional retrieval experiments explored address-numeric blocking and other candidate-generation strategies to improve the retrieval ceiling.

---

## 🛣️ Road Guardian AI

Computer-vision system for automated pothole detection and road-condition reporting.

### Technology

* YOLO
* OpenCV
* Python
* Pandas
* GPS
* Geotagged detection
* Visual evidence capture
* Automated reporting

### Pipeline

```text
Camera
  ↓
Object Detection
  ↓
Confidence Filtering
  ↓
GPS + Timestamp
  ↓
Visual Evidence
  ↓
Road Condition Report
```

Designed as an applied computer-vision system for detecting and documenting road infrastructure problems.

---

# Technical Stack

### Machine Learning

`Python` · `Scikit-learn` · `LightGBM` · `PyTorch`

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

# What I Work On

My projects generally follow an end-to-end ML workflow:

```text
Data Collection
      ↓
Data Validation & Cleaning
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

# Current Focus

* Advanced Machine Learning
* Deep Learning
* Computer Vision
* Retrieval & Entity Resolution
* Spatiotemporal ML
* Anomaly Detection
* Metric Learning
* AI-powered engineering systems
* ML experimentation and evaluation
* Production-oriented ML architecture

---

# Selected Projects

| Project                             | Primary Area                               |
| ----------------------------------- | ------------------------------------------ |
| 🚁 **AeroPulse**                    | AI + Digital Twin + Predictive Maintenance |
| ✍️ **SYNAPSE**                      | Deep Learning + Biometrics + Risk          |
| 🔥 **India Forest Fire Prediction** | Spatiotemporal ML                          |
| 🔎 **DeepResolve ER**               | Retrieval + Entity Resolution              |
| 🛣️ **Road Guardian AI**            | Computer Vision                            |

---

# Engineering Philosophy

I try to build projects around three principles:

**1. Measure before claiming**

Model performance should be reported together with the dataset, split strategy, evaluation protocol, and limitations.

**2. Build beyond the notebook**

A model becomes more useful when it can be integrated into an API, application, pipeline, or complete system.

**3. Analyze failures**

Improving an ML system requires understanding where retrieval, features, models, thresholds, and data fail—not only optimizing a single metric.

---

# GitHub

[![GitHub](https://img.shields.io/badge/GitHub-neeravjain91--jpg-181717?style=for-the-badge\&logo=github)](https://github.com/neeravjain91-jpg)

---

> **Building AI systems from data and experimentation to deployable applications.**

