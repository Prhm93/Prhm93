# Hi there 👋, I'm Parham

---

<p>
  <img src="https://img.shields.io/badge/COMPUTER%20VISION-7C3AED?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DEEP%20LEARNING-10B981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/IMAGE%20SEGMENTATION-2563EB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FLOOD%20AI-EA580C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/WAtER%20ENGINEERING-DC2626?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PROMPT%20ENGINEERING-0EA5E9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LLMs-9333EA?style=for-the-badge" />
</p>

## 👨‍🔬 About Me

I'm a **Researcher in AI and Deep Learning** at the **University of Salford**, working at the intersection of computer vision and flood resilience.

My research builds deep learning systems for **flood scene analysis**, including semantic segmentation, human detection, and emergency scene classification, combined into an end-to-end pipeline for disaster response. My first degree is in **civil engineering**, specialising in **water and hydraulic structures**, so my work sits naturally where hydraulic engineering, computer vision, and applied AI meet.

- 🔬 **Current research:** Transformer-based flood segmentation and end-to-end flood scene understanding


## 🛠️ Tech Stack

**Languages & Core**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</p>

**Computer Vision & Detection**

<p>
  <img src="https://img.shields.io/badge/Ultralytics-FF6B00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SAHI-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Albumentations-CC0000?style=for-the-badge" />
</p>

**LLMs & NLP**

<p>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Transformers-FFB300?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Prompt%20Engineering-0EA5E9?style=for-the-badge" />
</p>

**Backend & Data**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

**Frontend & GIS**

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white" />
</p>

**DevOps & Environment**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

## 🔬 Current Research

**Three-stage flood scene analysis pipeline** (MRes thesis)

1. **TMSA-Net** — Transformer-based Multi-Scale Attention U-Net for flood-water segmentation, with EfficientNet-B4 / ResNet34 encoder, Transformer bottleneck, multi-scale attention gates, and dual attention refinement.
2. **YOLOv8m + SAHI** — slicing-aided hyper inference for human detection in complex flood imagery.
3. **Fusion classifier** — combines segmentation and detection outputs to produce EMERGENCY / MONITOR / SAFE scene classifications.

### Recent research outputs

- 🎤 **IPGRC 2026** — *Dynamic Kernel Attention Gate U-Net for Flood Segmentation* — oral presentation and poster
- 📄 **CAAI Transactions on Intelligence Technology** — TMSA-Net manuscript, under review (R1)

## 📌 Featured Projects

### 🌊 [DKAG-UNet — Dynamic Kernel Attention Gate U-Net](https://github.com/Prhm93/dkag-unet-flood)

Replaces fixed 1×1 attention-gate projections in U-Net with adaptive depthwise-separable convolutions (kernel sizes k = 5, 5, 3, 1 across decoder levels). Achieves **+3.41 IoU** over the standard U-Net baseline (93.76% vs 90.35%) with minimal parameter overhead (~10K extra parameters, ~0.035% of the model). Presented at IPGRC 2026.

### 📍 FloodWatch — End-to-end flood scene analysis platform

Full-stack web application integrating the complete ML pipeline. FastAPI backend, PostgreSQL with PostGIS spatial extensions, React and Leaflet frontend, dockerised for local deployment. Accepts flood imagery and returns segmentation masks, detected people, and EMERGENCY / MONITOR / SAFE classification, visualised on an interactive map.

## 🎓 Teaching

**Postgraduate Demonstrator** — *Visual Information Analysis*, University of Salford

Running workshops covering spatial and frequency-domain filtering, morphological segmentation, classical feature extraction (PCA, RCM, LBP, SIFT), and 3D reconstruction pipelines.

## 📚 Currently Learning

**AI Engineer for Developers** *(in progress)*

A career track focused on building production-grade AI applications. Topics being covered:

- Working with Large Language Models and prompt engineering
- Retrieval-Augmented Generation (RAG) and embeddings
- LangChain — chains, tool use, and agent-based systems
- Vector databases (Pinecone) for semantic search and recommendation
- Hugging Face models and the OpenAI API
- LLMOps — production deployment, API integration, robustness
- Software engineering for AI — modularity, testing, documentation

## 📫 Connect

- 💻 GitHub: [@Prhm93](https://github.com/Prhm93)
- 🔗 Email: (pimanzadeh.ch@gmail.com)
