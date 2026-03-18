# Akhil Vaidya

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akhilvaidya2004@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akhil-vaidya-90487a257/)
[![GitHub followers](https://img.shields.io/github/followers/AkhilVaidya91?label=Follow&style=social)](https://github.com/AkhilVaidya91)

---

Final-year Computer Engineering student. I build ML systems across the full stack - from transformer architectures and multimodal retrieval to MLOps pipelines and LLM-powered analytics. My work has been published in **Elsevier's Knowledge-Based Systems**, **IEEE Xplore**, and **Springer**, with research internships at **IIT Patna** and **SPJIMR**.

---

## Tech Stack

```yaml
Languages   : Python, C++, SQL, HTML/CSS
ML / AI     : PyTorch, TensorFlow, Scikit-learn, Transformers, LangChain, LlamaIndex, vLLM
Web & DevOps: FastAPI, Django, React, Docker, Kubernetes, GitHub Actions
Cloud       : AWS, Azure, SageMaker, Databricks
Analytics   : PySpark, MLflow, DVC, Optuna, Tableau
```

---

## Experience

**Research Intern - Data Analytics** | [SPJIMR](https://www.sciencedirect.com/science/article/abs/pii/S0950705125019641) | Oct 2024 - Present

- Designed **[QualiVec](https://github.com/AkhilVaidya91/QualiVec)**, a qualitative content analysis framework using transformer embeddings and cosine similarity; achieved **96.5% F1-score** in thematic classification across 100+ corporate annual reports; co-authored paper in **Knowledge-Based Systems** (Elsevier, Q1).
- Built LLM-powered pipelines using SMOL-Agents and Apify MCP to aggregate and analyze data across **500+ organizations** and **1,250+ documents** for UN SDG alignment research.

**Research Intern - Computer Vision** | [IIT Patna](https://drive.google.com/drive/folders/1VFEmXlPviXGsQgixweTQMiBx7eTJkorD?usp=sharing) | Jan 2025 - Jun 2025

- Built a Swin Transformer-based Siamese network for vehicle re-identification, outperforming CNN baselines by **15%** with **98.75% Top-1 accuracy**; integrated YOLOv12 (mAP@50 = 0.851) for robust detection under occlusion; benchmarked 8 architectures in ablation studies.
- Applied GradCAM and t-SNE for model interpretability; results published in **Springer TIPCE 2025**.

**Software Developer Intern** | Six Ladders (Ed-Tech) | Jun 2024 - Aug 2024

- Built a FastAPI microservice using LLaVA, Universal Sentence Encoder, and HDBSCAN for handwritten exam answer segmentation, achieving **86% question-grouping accuracy**.
- Implemented a multi-agent LLM workflow using Llama 3.1 70B for personalized learning roadmap generation based on dynamic user profiling.

---

## Featured Projects

**[MedRAG: Radiology Report Validation](https://akhilvaidya91.github.io/MedRAG/)** | [[GitHub](https://github.com/AkhilVaidya91/MedRAG)] | *FastAPI, Docker, vLLM, Supabase, pgvector, Grafana*

- Multimodal RAG system that validates radiology reports by retrieving similar cases from **30,000+ MIMIC-CXR samples** using MedSigLIP-448 for image-text embeddings.
- Deployed MedGemma 1.5 4B on a vLLM inference server (A100 GPU); containerized with Docker on Hugging Face Spaces via GitHub Actions; monitored with Prometheus + Grafana.
- Built an ETL pipeline to preprocess medical images, generate normalized vector embeddings, and populate a dual-modality Supabase/pgvector database.

**[Vision Transformer from Scratch - GTSRB](https://github.com/AkhilVaidya91/ViT-From-Scratch)** | *PyTorch, OpenCV, Gradio*

- Trained a 17.8M parameter ViT from scratch in PyTorch, achieving **96.58% test accuracy** on the 43-class GTSRB traffic sign dataset.
- Training optimized with AdamW, cosine annealing, linear warmup, and label smoothing; preprocessing pipeline includes CLAHE contrast enhancement and data augmentation.
- Gradio deployment features Grad-CAM, attention heatmaps, PCA-projected latent spaces, and per-head attention diversity analysis.

**[Forest Audio Classification - MLOps Pipeline](https://github.com/AkhilVaidya91/Forest-Audio)** | *LightGBM, MLflow, DVC, Optuna*

- Distributed edge-cloud framework for real-time illegal logging detection using Raspberry Pi nodes with MEMS microphones; **86% edge accuracy** with sub-20 ms latency.
- Hierarchical inference: lightweight LightGBM on edge devices, transformer-based classifiers for cloud re-evaluation; Optuna-driven hyperparameter optimization.
- MLOps pipeline with MLflow and DVC covering experiment tracking, model versioning, and continuous learning across 70 configurations and 14 architectures.

**[Traffic Sign Recognition - Hybrid Model](https://doi.org/10.1109/SSITCON62437.2024.10795884)** | *YOLOv8, VGG16, Random Forest*

- Two-stage hybrid model published in **IEEE Xplore**; achieved **99.34% mAP50** and **F1-score of 98.61%** on the GTSRB dataset.

---

## Other Projects

| Project | Tech Stack | Description |
|---|---|---|
| Functional Map Generator | TensorFlow Hub, scikit-learn | Automated urban region classification (industrial / commercial / residential) using semi-supervised learning |
| Fashion Recommendation System | TensorFlow, NLTK, Streamlit | AI-powered outfit generator using image embeddings and the Gemini API |
| Seller Rating & Forecasting | Flask, scikit-learn, Statsmodels | R2 > 0.97 seller rating prediction; ARIMA-based demand forecasting with < 5% error |
| Plant Disease Classifier (CBAM-VGG16) | TensorFlow | Integrated Convolutional Block Attention Module, boosting accuracy from 95% to 99% |

---

## Publications

- **Decision Support Content Analysis** - *Knowledge-Based Systems*, Elsevier [[DOI](https://doi.org/10.1016/j.knosys.2025.114926)]
- **Vehicle Fingerprinting via Swin Transformer** - *TIPCE 2025*, Springer (Accepted)
- **Automated Urban Zone Classification** - *IEEE* [[DOI](https://doi.org/10.1109/ICERECT65215.2025.11379759)]
- **Traffic Sign Recognition System** - *IEEE Xplore* [[DOI](https://doi.org/10.1109/SSITCON62437.2024.10795884)]

*[akhilvaidya2004@gmail.com](mailto:akhilvaidya2004@gmail.com)*
