# MedGuardAI — Medical IoT Capstone Architecture Case Study

MedGuardAI was a Licence capstone project at USTHB focused on the architecture of a medical-monitoring and telehealth application.

> **Repository status:** the public repository currently contains this README only. It does not include the Flutter application, Flask backend, device firmware, database schema, trained-model files, or deployment configuration. The architecture below is a summary of the project scope, not a reproducible deployment package. Any simulated sensor values are demonstrations, not real patient monitoring.

## Project scope

The planned/academic system combined:

- ECG and blood-glucose sensor acquisition, with a Raspberry Pi used as an edge relay in the described architecture.
- A Python/Flask service and MongoDB for application data.
- Model-based or threshold-based anomaly alerts, depending on the component.
- Flutter patient/doctor interfaces and a proposed WebRTC telehealth workflow.

These are architecture-level descriptions; this repository itself does not verify that every component was integrated and tested end to end.

## Related model repositories

- [ECG arrhythmia classification](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-ECG)
- [Blood-glucose anomaly detection](https://github.com/HANIDEVINF/deep-learning-model-for-anomaly-detection-of-blood-glucose-monitoring)
- [Fall-detection model](https://github.com/HANIDEVINF/Fall-Detection-Model)

## Reproducibility and safety

There is no single command to run this repository because application source files are not included. A reviewer needs access to the relevant source and hardware setup to verify acquisition, alerting, telemedicine and deployment behavior.

This project is an academic engineering case study and is not a certified medical device. It must not be used for diagnosis, triage, or real patient monitoring.
