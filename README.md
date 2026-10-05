# MedGuardAI — Real-Time Medical IoT, AI Anomaly Detection & Telemedicine Platform

> **Licence Graduation Capstone (PFE — USTHB) · Hardware ECG & Blood Glucose Sensors + Raspberry Pi + Python/Flask + Flutter + WebRTC**

## 1. System Overview
**MedGuardAI** is an end-to-end connected healthcare ecosystem engineered to bridge **physical biomedical sensors**, **real-time deep learning anomaly detection**, and **clinical telemedicine workflows**.

Unlike isolated notebook models, MedGuardAI streams live physiological signals from hardware ECG and blood glucose sensors through a Raspberry Pi edge relay to a Python/Flask inference backend, triggering instant emergency alerts and unlocking WebRTC video consultations between patients and physicians.

---

## 2. End-to-End Architecture

```text
[Physical ECG & Glucose Sensors]
        │ (Serial / BLE Acquisition)
        ▼
[Raspberry Pi Edge Relay] ──► Real-Time Telemetry Stream
        │
        ▼
[Python / Flask Backend + MongoDB]
  ├─► Deep Learning ECG & Glycemia Anomaly Detection Models (.h5 / Keras)
  ├─► Multi-Tier Clinical Alert Engine (Critical / Warning / Normal)
  ├─► Appointment Scheduling & Automated Digital Prescription Generator
  └─► WebRTC Signaling & Real-Time Chat Server
        │
        ▼
[Cross-Platform Flutter Mobile & Web Dashboards]
  ├─► Patient App: Live ECG waveform, glucose trendlines, emergency SOS, 1-tap video call
  └─► Doctor Portal: Multi-patient telemetry monitor, diagnostic history & prescription builder
```

---

## 3. Related Model Repositories
- **[Deep Learning ECG Anomaly Detection Model](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-ECG)**
- **[Deep Learning Blood Glucose Anomaly Detection Model](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-blood-glucose-monitoring)**
- **[Patient Fall Detection Computer Vision Model](https://github.com/HANIDEVINF/Fall-Detection-Model)**
