<p align="center">
  <a href="https://rakehsaleem.github.io/" target="_blank">
    <img 
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=378ADD&center=true&vCenter=true&width=800&height=70&lines=Muhammad+Rakeh+Saleem%2C+Ph.D.;AI+%26+Machine+Learning+Engineer+%7C+Data+Scientist;Multi-Agent+LLMs+%7C+Forecasting+%7C+Computer+Vision" 
      alt="Muhammad Rakeh Saleem, Ph.D."
    />
  </a>
</p>


I am a **Data Scientist and ML/AI Engineer (Ph.D.)** with 5+ years of experience building and deploying production machine learning systems across **probabilistic time-series forecasting**, **multimodal computer vision**, and **agentic LLM workflows**. 

- **Currently:** AI Engineer at **Kaba Construction**, architecting **MASON**—a two-stage multi-agent renovation platform in **LangGraph** that pairs multimodal LLM agents and Pydantic-validated structured outputs with deterministic Python pricing and **Google OR-Tools (CP-SAT)** crew scheduling.
- **Previously:** Data Scientist at **GA Telesis**, where I shipped a production intermittent-demand forecasting system for aviation spare parts on **AWS SageMaker** in 3.5 months and led an on-premise **Document AI** proof of concept (**LayoutLMv3, Qwen-VL, Florence-2**) for PII redaction across 50,000+ documents.
- **Research Foundation:** Completed my Ph.D. at **Penn State**, developing gaze-supervised computer vision and **Vision Transformer (ViT)** distillation pipelines for automated structural and UAV inspection (**11 peer-reviewed publications, 340+ citations**; invited talks at **ETH Zurich** and **Thornton Tomasetti**).

---

### What I'm Building & Shipped Systems

#### 1. Agentic AI & Constrained Mathematical Optimization
- **MASON (Multi-Agent Renovation & Scheduling Engine):** Two-stage autonomous pre-construction platform (`LangGraph`, `Streamlit`). Multimodal LLMs interpret site imagery and floor plans into Pydantic schemas, deterministic Python computes 100% of quantities and pricing, and a **Google OR-Tools CP-SAT** constraint program generates multi-trade crew schedules under precedence, skill, and room-occupancy limits.
- **On-Device Executive AI Agent:** Local autonomous desktop agent running **Qwen2.5 7B** on consumer GPU hardware via **LangGraph**, featuring 50+ system tools, SQLite memory checkpointers, hybrid ChromaDB RAG, wake-word voice (`faster-whisper` + `Piper TTS`), and strict human-in-the-loop safety tiers.

#### 2. Probabilistic Forecasting & Multimodal Document AI
- **Aviation Spare-Parts Demand Forecasting:** Multi-horizon **Temporal Fusion Transformer (TFT)**, LSTM, and LightGBM ensembles on **AWS SageMaker**, achieving **86% empirical coverage of 80% prediction intervals** over a 3-month horizon and an **11% MASE improvement** over baseline, backed by Snowflake-to-S3 ETL and MLflow tracking.
- **On-Premise Document AI for PII Redaction:** Fine-tuned **LayoutLMv3** with **PaddleOCR** on 1,800 annotated aviation records and benchmarked against **Qwen-VL** and **Florence-2** across 50,000+ documents, authoring the 4-year cloud-vs-on-prem TCO break-even analysis.

#### 3. Sim2Real Computer Vision & Edge Distillation
- **MAISI (Sim2Real Gaze Distillation for Edge UAVs):** Synthetic eye-tracking simulation in Unity (calibrated against a 12-participant expert dataset) paired with knowledge distillation that compresses gaze-guided attention into a compact **Vision Transformer (ViT)** for real-time on-device drone inspection.

---

### Technical Stack

| Domain | Core Technologies & Methods |
| :--- | :--- |
| **Languages & APIs** | Python (NumPy, Pandas, scikit-learn), SQL, C++, FastAPI, REST APIs, Git, Streamlit |
| **Agentic AI & Optimization** | LangGraph, LangChain, Structured Outputs, Pydantic, Google OR-Tools (CP-SAT), ChromaDB (RAG) |
| **ML & Deep Learning** | PyTorch, TensorFlow, Hugging Face (Fine-Tuning), Transformers (TFT, ViT), CNNs, LSTM, LightGBM, XGBoost, Optuna |
| **Computer Vision & DocAI** | LayoutLMv3, Qwen-VL, Florence-2, PaddleOCR, docTR, OpenCV, Object Detection, Knowledge Distillation |
| **Forecasting & Statistics** | Intermittent-Demand & Probabilistic Forecasting, Conformal Prediction, Quantile Regression, Croston/SBA, SARIMA, Matrix Profile, A/B Testing |
| **MLOps & Cloud** | AWS (SageMaker, S3, CloudWatch), Snowflake, MLflow, Docker, CI/CD, pytest, Drift Monitoring, Power BI |

---

![Snake animation](https://raw.githubusercontent.com/rakehsaleem/rakehsaleem/output/github-snake.svg)

<p align="center">
  <i>"Combining mathematical rigor, deterministic optimization, and deep learning to build AI systems that survive contact with the physical world."</i>
</p>
