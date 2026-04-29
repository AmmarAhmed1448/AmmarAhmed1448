**Ammar Ahmed Khan**
**Software Engineer | CS & AI Researcher**

I am a Software Engineering graduate who spent four years building things and researching why they work. My undergraduate work sits mostly in applied machine learning, anomaly detection, domain adaptation, and network security, and I am continuing that thread while working professionally as a software developer.

I write code that ships and papers that question. Not many people do both, and I think that combination matters.

---

**What I have worked on**

**Domain Adaptation with Adversarial Networks**
 https://github.com/AmmarAhmed1448/Domain-Adaptation-with-DANN

The core problem: a model trained on CIFAR-10 does not perform well when tested on STL-10, even though both datasets contain similar object categories. The distribution shift between the two is enough to break standard classifiers. I implemented a Domain-Adversarial Neural Network on a ResNet-50 backbone, using a Gradient Reversal Layer to push the feature extractor toward producing representations that a domain discriminator cannot distinguish. Target accuracy improved from a 45% baseline to 50.04%, with t-SNE visualizations and discriminator accuracy (~51%) confirming partial domain invariance.

---

**Insider Threat Detection via Unsupervised Anomaly Detection**
https://github.com/AmmarAhmed1448/Insider-Threat-Detection-with-Unsupervised-Anomaly-Detectio
n-and-UBA

The challenge here is subtle: insider threats look like normal activity on the surface. I worked on the CERT Insider Threat Dataset (r4.2), engineering behavioral features from logon patterns, device usage, file transfers, and OCEAN psychometric scores. Autoencoder-based anomaly detection with z-score thresholding was applied and benchmarked against One-Class SVM. User-PC relationships were modeled using bipartite graph analysis. LSTM-based sequence modeling was also attempted before pivoting to the autoencoder approach after evaluating feasibility within project scope.

---

**DDoS Detection in Software-Defined Networks**
https://github.com/AmmarAhmed1448/Detecting-and-Mitigating-DDoS-Attacks-in-SDN-Environments

I designed a three-layer detection architecture integrating Mininet for network emulation, a Ryu SDN controller, and OpenFlow13. A virtual topology of 6 switches and 18 hosts was built to simulate both benign and attack traffic. A Random Forest classifier trained on CICIDS 2017 runs predictions on a 10-second polling interval, with detected attacks triggering alerts identifying the victim host. Flow-rule-based blocking via the Ryu controller was designed as a system component and proposed for future implementation.

---

**KNN vs. Decision Trees on Medical Datasets**
 https://github.com/AmmarAhmed1448/comparitive-analysis-of-KNN-and-DT

A systematic comparison of both classifiers across three medical datasets of varying sizes — Heart Failure (~300 instances), Diabetes (~769 instances), and Stroke (~5,110 instances). Evaluated on accuracy, execution time, sensitivity, specificity, and precision with an 80/20 split. KNN consistently outperformed Decision Tree in accuracy; Decision Tree was faster across all dataset sizes.

---
**Biometric Attendance System**
Code: github.com/AmmarAhmed1448/Facelogger

Backend and data layer for an automated attendance system using face recognition. Built with Flask and MongoDB, handling attendance marking, late arrival tracking, and absence recording. Integrated Haar Cascade-based detection with the attendance logic. Designed for office environments with a registered user base.

---

**Technical skills**

Languages: Python, C++, C#, JavaScript, SQL
Deep Learning: PyTorch, TensorFlow, Keras, OpenCV, scikit-learn
Infrastructure: Docker, Git, Linux, PostgreSQL, Azure, AWS
Research: Jupyter, LaTeX

Mathematical background: Linear Algebra, Calculus, Probability and Statistics, Differential Equations, Stochastic Processes

---

**Currently**

Professionally: Building enterprise ERP modules and integration platforms at an early-stage software startup
Research direction: Interested in extending domain adaptation work and exploring self-supervised learning in computer vision
Learning: Robotics fundamentals, geometric deep learning, 3D vision

---

**What I am looking for**

A research environment where I can work on real, open problems the kind that do not have clean solutions yet. My background is in AI and software engineering. The direction I want to move in is intelligent systems that operate in physical environments. That intersection is where I want to spend the next few years.

---

## Connect

**Email**: aammarahmed1448@gmail.com@gmail.com  
**LinkedIn**: [linkedin.com/in/ammarahmedkhan](https://www.linkedin.com/in/ammar-ahmed-khan-26370522b/)

---

> *"Research is formalized curiosity. It is poking and prying with a purpose."* — Zora Neale Hurston
