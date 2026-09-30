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

**Primary evaluation**

| Metric                         |     Result |
| ------------------------------ | ---------: |
| Health Classification Accuracy | **89.47%** |
| Balanced Accuracy              | **89.29%** |
| Critical-State Recall          | **95.68%** |
| Critical-State Precision       | **63.88%** |
| Critical-State F1              |  **0.766** |
| Anomaly Detection AUROC        |  **0.960** |
| False Alarm Rate               |  **5.79%** |

**Evaluation scope**

The primary health-monitoring model is evaluated using **NASA ACES-based data**. The reported classification metrics describe the project's defined health-state classification task and should not be interpreted as real-world aircraft engine failure-prediction accuracy.

The anomaly detector is evaluated separately using the project's healthy-operation anomaly-detection setup.

Supporting components include CWRU vibration data and other datasets used for methodology validation rather than as direct evidence of UAV engine-failure prediction.

> Research/SIH prototype — not a certified flight-safety, airworthiness, maintenance-release, or operational defence system.
