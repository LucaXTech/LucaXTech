# Luca Serioli

**Biomedical Engineer (MSc, cum laude) | Medical Imaging AI | Research Software Engineering | Neurotechnology**

I develop **research-grade software and applied AI tools** at the intersection of biomedical engineering, machine learning and real-world systems. My work spans medical-image analysis, EEG signal processing, reproducible experimental pipelines, and software/device interoperability.

I earned an MSc in Biomedical Engineering (110/110 cum laude) from the **Università degli Studi “G. d’Annunzio” Chieti–Pescara**. During an **Erasmus+ research traineeship at g.tec medical engineering (Austria)**, I worked on EEG-based mental-workload assessment using N-back tasks.

**Based in:** Brescia, Italy  
**Interests:** Biomedical R&D · Computer Vision · Neurotechnology · Applied AI · Scientific Software · Connected Systems

## Featured research software — SpineLocus

### [SpineLocus — thoracic spine landmark localization](https://github.com/LucaXTech/spinelocus)

[![SpineLocus v0.1.7 DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23325290.svg)](https://doi.org/10.5281/zenodo.23325290)

**Independently developed, single-author open-source Python research software.** SpineLocus locates **11 thoracic vertebral landmarks (T1–T11)** in digitally reconstructed radiographs (DRRs), combining **YOLO-Pose** with optional **HRNet** refinement.

Beyond model inference, the project implements **subject-disjoint data partitioning, training configurations, full-image evaluation, ensemble methods, automated tests, and dataset/provenance audits**.

**Reported development-validation baseline:** **82.31% mean subject PCK@5** and **6.424 px mean localization error**, evaluated on **750 images from 15 subjects**. This validation set was used during method development; these figures **are not independent held-out test results**.

**[Source code & documentation](https://github.com/LucaXTech/spinelocus)** · **[Versioned archive / DOI](https://doi.org/10.5281/zenodo.23325290)** · **AGPL-3.0-only** · **v0.1.7**

*Research software only; not validated for clinical use. Imaging data and trained model weights are not distributed.*

## Other selected projects

| Project | Engineering focus |
| --- | --- |
| **[EEG Mental Workload Analysis](https://github.com/LucaXTech/eeg-workload-analysis)** | MSc EEG research: N-back paradigms, ERP analysis, signal processing and mental-workload classification. Reproducibility-oriented research repository; distinct from SpineLocus. |
| **[Glucose–Insulin Modelling & Control](https://github.com/LucaXTech/glucose-insulin-simulink-control)** | Biomedical system simulation with MATLAB/Simulink, PID and fuzzy control. Academic modelling project; not for clinical use. |
| **[MAGI / BioAudit](https://github.com/LucaXTech/magi-multimodel)** | Experimental multi-model AI orchestration and biomedical research-auditing methodology. Research prototype. |
| **[Sanag Control for iOS](https://github.com/LucaXTech/sanag-b21s-control-ios)** | Original SwiftUI/CoreBluetooth application: reverse-engineered BLE interoperability, EQ presets and iOS Shortcuts. Hardware-tested on Sanag B21S. |
| **[UplinkWitness](https://github.com/LucaXTech/UplinkWitness)** | Self-hosted Linux/network diagnostics with multi-layer connectivity evidence, dashboard and Raspberry Pi validation. |
| **[Echo LiveView Bridge](https://github.com/LucaXTech/echo-liveview-bridge)** | Experimental WebRTC/H.264 device-interoperability and video-stream research. Proof of concept. |

## Technical areas

- **Medical imaging & AI:** Computer Vision, landmark localization, YOLO-Pose, HRNet, PyTorch, reproducible model evaluation.
- **Biomedical research:** EEG, ERP analysis, biosignal processing, experimental protocols and biomedical modelling.
- **Scientific software:** Python, scientific computing, scikit-learn, dataset integrity, testing, Git and CI.
- **Systems & development:** Swift/SwiftUI, CoreBluetooth, Linux, Raspberry Pi, network protocols and interoperability.
- **Modelling & control:** MATLAB/Simulink, dynamical systems and feedback control.

## Collaboration & contact

I'm interested in **biomedical R&D, AI/computer-vision engineering and research software development**, particularly where rigorous experiments need to become robust, maintainable software.

**[GitHub projects](https://github.com/LucaXTech)** · **[Email](mailto:luca@serioli.org)**

*Projects vary in maturity; each repository documents its evidence, scope and limitations. Third-party contributions and methods retain their own attribution.*
