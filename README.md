<div align="center">

[![English](https://img.shields.io/badge/🇬🇧_English-00D9FF?style=for-the-badge&labelColor=0D1117)](README.md)

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=30&duration=2500&pause=800&color=00D9FF&center=true&vCenter=true&width=850&lines=Nguyen+Phuc+Nguyen;AI+Engineer+%7C+AI+Researcher;Deep+Learning+%7C+Computer+Vision;Medical+Imaging+%7C+EEG+%7C+GenAI" alt="Typing SVG" />

[![GitHub followers](https://img.shields.io/github/followers/PhucNguyenne?style=flat-square&logo=github&labelColor=0D1117&color=00D9FF)](https://github.com/PhucNguyenne)
[![Profile Views](https://komarev.com/ghpvc/?username=PhucNguyenne&color=00D9FF&style=flat-square&label=Views)](https://github.com/PhucNguyenne)
[![Publications](https://img.shields.io/badge/Publications-3-00D9FF?style=flat-square&labelColor=0D1117)](#publications)
[![Status](https://img.shields.io/badge/Status-Open_to_work-00D9FF?style=flat-square&labelColor=0D1117)](#)

</div>

---

## About Me

**AI Engineer & AI Researcher** based in Ho Chi Minh City, Vietnam. I work at the intersection of deep learning research and production engineering — with published work in a **Q1 SCI journal (IEEE Access)** and **international IEEE conferences**, plus hands-on industry experience building RAG pipelines and data infrastructure.

My research spans **medical image segmentation**, **EEG signal decoding (Brain–Computer Interfaces)**, **remote sensing / LiDAR point clouds**, and **unsupervised representation learning** — with a recurring theme of designing hybrid architectures (Transformer + CNN, attention-augmented networks) that are both accurate and efficient.

| Role | Focus |
| :--- | :--- |
| **AI Researcher** | Medical image segmentation (BraTS), EEG motor imagery decoding, TLS wood–leaf separation, hybrid SwinViT + CNN architectures, model pruning |
| **NLP / GenAI Engineer** | RAG pipelines, LLM fine-tuning, prompt engineering, MPNet-based text representation |
| **Machine Learning Eng.** | Deep Embedded Clustering, HDBSCAN, LSTM-based action recognition, pose estimation |
| **Data Engineer** | ETL pipelines, object storage (MinIO), graph databases (Neo4j), privacy-compliant data collection |

---

## Publications

<div align="center">

| Year | Paper | Venue | Role |
| :--: | :--- | :--- | :--: |
| **2026** | Automated Wood and Leaf Separation: A Comprehensive Review on Advanced Methods and Forestry Applications | **IEEE Access** — *Q1 SCI, IF 4.2* | Co-author |
| **2026** | ATCNet-CIAM for Multi-Session Motor Imagery EEG Signal Classification | **ISRSD 2026** — *Accepted* | Co-author |
| **2025** | Swin-PResU: Hybrid SwinViT and Pruned Residual CNN for Precise Brain Tumor MRI Segmentation | **RIVF 2025**  | **First author** |

</div>

<details open>
<summary><b>Details & Key Results</b></summary>

<br>

### Automated Wood and Leaf Separation — *IEEE Access (Q1 SCI, IF 4.2)*
**`Remote Sensing`** **`LiDAR / TLS`** **`Survey`** **`Forestry`**

A comprehensive review systematizing traditional, machine learning, and deep learning approaches to **TLS-based wood–leaf separation**. My contribution covered the literature systematization and data synthesis, the comparative analysis of classification metrics (Accuracy, F1-score) across methods, quantitative analysis of downstream forestry applications (biomass estimation, canopy structure profiling), and manuscript preparation.

### ATCNet-CIAM — *ISRSD 2026*
**`EEG`** **`Brain-Computer Interface`** **`Attention`** **`PyTorch`**

An attention-augmented architecture integrating a **frequency-band-aware channel attention module (CIAM)** into ATCNet to improve robustness of multi-session motor imagery decoding.


### Swin-PResU — *RIVF 2025* 
**`Medical Imaging`** **`SwinViT`** **`MONAI`** **`Model Pruning`**

A hybrid architecture pairing a **Swin Transformer encoder** with a **pruned residual CNN decoder** for brain tumor MRI segmentation. Led architecture design, built the preprocessing pipeline in MONAI, and ran extensive comparisons against established baselines on **BraTS 2020** — reaching a **mean Dice score of 86.22%**, evaluated with DSC and HD95.

</details>

---

## Professional Experience

### AI Engineer Intern (NLP) — Vietravel IT Center
`Jun 2025 – Sep 2025`

- Built a **RAG-based chatbot** for sales consultation, plus automated customer data tooling on **MinIO** and **Dify**.
- Automated multi-source data collection pipelines with privacy-compliance safeguards.
- Designed secure storage systems and fine-tuned models for personalized recommendations.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### Deep Embedded Clustering for Social Media Post Classification
**`NLP`** **`Unsupervised Learning`** **`MPNet`** **`DEC`**
`Apr 2025 – Dec 2025` · Team of 2

Automated topic classification over **580,000+ unlabeled Facebook posts** by pairing the **MPNet** language model with **Deep Embedded Clustering**.

Achieved **58.48% accuracy / 0.3504 NMI using only 0.5% labeled data** for cluster-to-label mapping — outperforming K-Means and BERTopic while retaining **100% data coverage** (no noisy samples discarded).

</td>
<td width="50%" valign="top">

### VNHCAREAI — Smart AI Assistant for Home Health & Safety
**`Computer Vision`** **`LSTM`** **`MediaPipe`** **`Flask`**
`Jul 2025 – Sep 2025` · Team of 3

Camera-based elderly monitoring system built on an **LSTM-P** model classifying 5+ health-related actions (including fall detection) from **MediaPipe** pose landmarks on RGB frames.

Shipped a lightweight **Flask** prototype for real-time visualization and abnormal-behavior alerts.
*🏆 Potential Project Award — VietFuture 2025 (VINASA).*

</td>
</tr>
</table>

<details>
<summary><b>Other Work</b></summary>

<br>

| Project | Description |
| :--- | :--- |
| **SKY-SENTRY HCMC** | CanSat sensor network for air-quality monitoring across Ho Chi Minh City — technical specification, deployment planning, and the environmental data analysis pipeline. |
| **Face Detection and Prediction (Age/Gender/Emotion)** | Built an end-to-end facial attribute analysis pipeline (age, gender, emotion) for consumer behavior tracking, utilizing
MTCNN for face alignment, a ResNet18 backbone for classification, and SQLite for automated data storage. |
| **Weather Forecast Website** | Developed and containerized a 7-day weather forecasting web application using Flask and Docker, implementing
Random Forest algorithms to process historical API data from Visual Crossing. |

</details>

---

## Education

| Institution | Program | Period |
| :--- | :--- | :--- |
| **Van Lang University**, Vietnam | B.S. in Information Technology — *Data Technology* | Sep 2022 – 2026 |

- **GPA: 8.8/10.0** (≈ 3.52/4.00)
- **Valedictorian of the Graduation Thesis — 10.0/10.0**
- School-Level Scientific Research Award — 81.0/100.0 (2025)
- 50% Tuition Scholarship (2025)

---

## Technical Stack

<details open>
<summary><b>Deep Learning & Research</b></summary>
<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=0D1117)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white&labelColor=0D1117)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white&labelColor=0D1117)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white&labelColor=0D1117)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white&labelColor=0D1117)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white&labelColor=0D1117)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white&labelColor=0D1117)

</div>

- **Architectures:** SwinViT / Vision Transformers, U-Net family, CNNs, LSTM, attention modules, model pruning
- **Computer Vision:** Medical MRI segmentation (MONAI, BraTS), pose estimation (MediaPipe), image classification
- **Signal Processing:** EEG decoding, motor imagery BCI, frequency-band-aware attention
- **Machine Learning:** Deep Embedded Clustering, HDBSCAN, PCA, Deep Reinforcement Learning

</details>

<details open>
<summary><b>GenAI, Data & Infrastructure</b></summary>
<div align="center">

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=0D1117)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white&labelColor=0D1117)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white&labelColor=0D1117)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white&labelColor=0D1117)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white&labelColor=0D1117)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white&labelColor=0D1117)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black&labelColor=0D1117)

</div>

- **GenAI & NLP:** RAG pipelines, Dify, LLM fine-tuning, prompt engineering, MPNet / BERT-family models
- **Databases & Storage:** SQL, NoSQL, Neo4j (Graph DB), MinIO (Object Storage)
- **MLOps & Deployment:** Docker, Flask, Git, Linux, ETL & sensor-data ingestion pipelines
- **Environments:** Google Colab, Jupyter, VS Code

</details>

---

## Awards & Certifications

| Awards | Certifications |
| :--- | :--- |
| 🥉 Third Prize — Vietnam AI Olympiad, Southern Round | Neo4j Graph Data Science Certification (2025) |
| 🎖️ Consolation Prize — Vietnam AI Olympiad, Final Round | Kaggle Computer Vision Certificate (2025) |
| 🎖️ Consolation Prize — VINASA VietFuture (2025) | Google AI Essentials Certificate (2024) |

**Languages:** Vietnamese (Native) · English (B2)

---

## GitHub Statistics

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=PhucNguyenne&theme=github-dark&hide_border=true&bg_color=0D1117&color=FFFFFF&line=00D9FF&point=00D9FF&area=true&area_color=00D9FF" alt="Contribution Graph" />

</div>

---

## Let's Connect

<div align="center">

[![Email Me](https://img.shields.io/badge/📧_Email-phucnguyen2892k4%40gmail.com-00D9FF?style=for-the-badge&labelColor=0D1117)](mailto:phucnguyen2892k4@gmail.com)

[![LinkedIn](https://img.shields.io/badge/🔗_LinkedIn-Phuc_Nguyen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/phucnguyenne)
[![Google Scholar](https://img.shields.io/badge/🎓_Google_Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=0D1117)](#)

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio_/_Blog-phucnguyenne.github.io-00D9FF?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0D1117)](#)

<sub>Open to AI Engineer, AI Research, and research collaboration opportunities — feel free to reach out!</sub>

</div>
