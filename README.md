# Ammar Ahmed Khan

**Computer Vision Researcher | Software Engineer**

I build intelligent systems grounded in mathematical rigor and engineered for real-world deployment. My work spans adversarial learning, biometric recognition, and anomaly detection—with a focus on bridging the gap between research and production.

Currently exploring domain adaptation and unsupervised learning while professionally developing enterprise software systems.

---

## Research Interests

My research investigates the theoretical and practical challenges of visual intelligence:

- **Domain Adaptation** – How can models generalize across distribution shifts without labeled target data?
- **Adversarial Learning** – Exploring min-max optimization dynamics in neural networks
- **Biometric Systems** – Robust face recognition under real-world constraints (lighting, occlusion, pose variation)
- **Anomaly Detection** – Unsupervised methods for identifying outlier behavior in high-dimensional data

I'm particularly drawn to problems at the intersection of **geometry, optimization, and perception**—where mathematical foundations directly inform algorithmic design.

---

## Research & Technical Projects

### Domain Adaptation with Adversarial Networks
**Paper**: *Unsupervised Domain Adaptation for Image Classification using Domain-Adversarial Neural Networks*  
**Code**: [github.com/AmmarAhmed1448/Domain-Adaptation-with-DANN](https://github.com/AmmarAhmed1448/Domain-Adaptation-with-DANN)

Investigated transfer learning under domain shift using adversarial training. Implemented DANN architecture with ResNet-50 backbone, achieving Nash equilibrium between feature extractor and domain discriminator. Demonstrated 50% target accuracy on MNIST→MNIST-M adaptation without target labels—validating the theoretical framework of learning domain-invariant representations.

**Key contributions**: Minimax optimization analysis, gradient reversal layer implementation, convergence diagnostics

---

### Insider Threat Detection via Unsupervised Anomaly Detection
**Paper**: *Advancing Insider Threat Detection with Unsupervised Anomaly Detection and User Behavious Analytics*  
**Code**: [github.com/AmmarAhmed1448/Insider-Threat-Detection](https://github.com/AmmarAhmed1448/Insider-Threat-Detection-with-Unsupervised-Anomaly-Detection-and-UBA)

Developed unsupervised framework for detecting malicious insiders in enterprise logs. Combined deep autoencoders with One-Class SVM and graph-theoretic user behavior analysis. Designed dynamic threshold mechanism using reconstruction error statistics (Z-score normalization) to flag anomalous access patterns.

**Methods**: Variational autoencoders, OCSVM decision boundaries, temporal graph construction

---

### Real-Time DDoS Mitigation in Software-Defined Networks
**Paper**: *Detecting and Mitigating DDoS Attacks in SDN Environments Using Machine Learning*  
**Code**: [github.com/AmmarAhmed1448/SDN-DDoS-Detection](https://github.com/AmmarAhmed1448/Detecting-and-Mitigating-DDoS-Attacks-in-SDN-Environments)

Designed real-time traffic classification system for OpenFlow networks. Trained Random Forest classifier on flow-level features (packet rate, entropy, protocol distribution) and integrated with Ryu SDN controller for automated rule injection. System achieves sub-second detection and blocking of malicious flows.

**Engineering**: Mininet network simulation, controller-switch communication protocols, production deployment considerations

---

### Biometric Attendance System with Face Recognition
**Code**: [https://github.com/AmmarAhmed1448/Facelogger](https://github.com/AmmarAhmed1448/Facelogger)

Engineered end-to-end face recognition system robust to practical deployment challenges. Implemented cascade detection (Haar/HOG) with CNN-based verification network.

**Focus**: Geometric invariance, embedding space optimization, false acceptance/rejection tradeoffs

---

### 🔬 Featured Research & Projects

| Project | Tech Stack | Impact |
| :--- | :--- | :--- |
| **[Domain Adaptation (DANN)](https://github.com/AmmarAhmed1448/Domain-Adaptation-with-DANN)** | `PyTorch` `ResNet-50` `Adversarial Learning` | Achieved **Nash Equilibrium** between feature extractor & discriminator; boosted target accuracy to **50.04%**. |
| **[Insider Threat Detection](https://github.com/AmmarAhmed1448/Insider-Threat-Detection-with-Unsupervised-Anomaly-Detection-and-UBA)** | `Autoencoders` `OCSVM` `Graph Theory` | Detected anomalies in user behavior logs using dynamic reconstruction error thresholding (Z-scores). |
| **[SDN DDoS Mitigation](https://github.com/AmmarAhmed1448/Detecting-and-Mitigating-DDoS-Attacks-in-SDN-Environments)** | `Mininet` `Ryu Controller` `Random Forest` | Real-time flow classification and automated rule injection to block malicious IPs in software-defined networks. |
| **[Biometric Attendance](https://github.com/AmmarAhmed1448/Facelogger)** | `OpenCV` `CNN` `Haar Cascades` | Engineered an end-to-end face recognition pipeline robust to varying lighting conditions. |
| **[KNN vs. Decision Trees](https://github.com/AmmarAhmed1448/KNN-vs-Decision-tree-for-traffic-prediction)** | `Python` `Scikit-Learn` `Algorithmic Analysis` | Benchmarked **Big-O time complexity** and accuracy for traffic forecasting; analyzed scalability limits. |

---

## Technical Foundation

**Core**: Python, C++, C#, javacript, SQL  
**Deep Learning**: PyTorch, TensorFlow, OpenCV, scikit-learn  
**Infrastructure**: Docker, Git, Linux, PostgreSQL, Kuberntes, Azure, AWS
**Research Tools**: Jupyter, LaTeX

**Mathematical Background**: Linear Algebra, Calculus, Probability & Statistics, Differential Equations, Stochastic Processes

---

## Current Work

**Professional**: Software Engineer developing enterprise ERP solutions and integration platforms  
**Research**: Extending domain adaptation work; exploring self-supervised learning in computer vision  
**Learning**: Advanced optimization methods, geometric deep learning, 3D vision fundamentals

---

## What Drives Me

I'm fascinated by the question: *How do we build visual systems that understand, not just recognize?*

The most interesting problems in computer vision aren't purely algorithmic—they're about understanding the geometry of visual data, the statistics of natural images, and the optimization landscapes of neural networks. I believe the next generation of intelligent systems will come from researchers who can navigate both the theory (differential geometry, information theory, statistical learning) and the practice (distributed training, model compression, deployment constraints).

My goal is to contribute to this future—conducting research that advances our theoretical understanding while building systems that work reliably in the real world.

---

## Connect

**Email**: aammarahmed1448@gmail.com@gmail.com  
**LinkedIn**: [linkedin.com/in/ammarahmedkhan](https://www.linkedin.com/in/ammar-ahmed-khan-26370522b/)
**Research Interests**: Domain Adaptation, Self-Supervised Learning, Geometric Deep Learning, 3D Computer Vision

---

> *"Research is formalized curiosity. It is poking and prying with a purpose."* — Zora Neale Hurston
