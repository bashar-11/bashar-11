<div align="center">

# Bashar Sayed

**AI & Data Analytics Engineer** — computer vision, retrieval-augmented generation and LLM systems.

Cairo, Egypt · Open to AI / Data Analytics roles

[![GitHub](https://img.shields.io/badge/GitHub-bashar--11-181717?logo=github)](https://github.com/bashar-11)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-bashar--sayed-0A66C2?logo=linkedin)](https://linkedin.com/in/bashar-sayed-972110220)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-BasharSayed-FFD21E?logo=huggingface)](https://huggingface.co/BasharSayed)

</div>

---

I build systems that turn messy data and raw video into decisions people can act on. My work sits where machine learning meets the unglamorous parts: evaluation harnesses, reliability layers above a model, deployment that fits in 512 MB, and tests that catch the bug before a user does.

I care about the part after the demo. A letter-by-letter sign classifier is easy; making one that does not fire on every hand movement is the actual engineering.

## Projects

| Project | What it is |
|---|---|
| **[SignBridge](https://github.com/bashar-11/SignBridge)** | Real-time sign-language translation in the browser — sign ↔ text ↔ audio. Arabic (33 classes) and American (28 classes) sign, with WebRTC rooms, a 3D avatar and an interactive learning mode. Graduation project. |
| **[PPE Detection (YOLOv11)](https://github.com/bashar-11/PPE-Detection.yolov11)** | Workplace-safety compliance detection. YOLOv11 fine-tuned for reflective vests and hard hats, served through a Streamlit dashboard for images, video and live webcam. |
| **[Nexus RAG](https://github.com/bashar-11/nexus-rag)** | Bilingual retrieval-augmented generation. BM25 and dense vectors fused with Reciprocal Rank Fusion, answering in Arabic or English with page-level citations. |
| **[SignBridge AI](https://github.com/bashar-11/signbridge-ai)** | Sign-language ML pipeline over WLASL — dataset subsetting, video I/O and a pluggable pose backend — with a React/TypeScript interface. |
| **[Qwen3-4B Business Copilot](https://huggingface.co/BasharSayed/qwen3-4b-business-copilot)** | A 4B-parameter model fine-tuned for a business domain and published on the Hugging Face Hub under Apache 2.0. |

## Engineering practice

The parts of the work that rarely show up in a screenshot:

- **CI on every repository** — lint, tests, dependency audits, and, for the computer-vision repo, a job that fails the build if the dataset is ever committed again.
- **Tests that run in seconds** — suites written to need no API keys, no database and no GPU. 17 tests for PPE, 31 for RAG, 39 for the ML pipeline.
- **Bugs found by writing the tests.** The RAG loader had a fallback for non-UTF-8 files that never fired, because LangChain re-raises `UnicodeDecodeError` as a `RuntimeError`. Arabic summary detection matched inside longer words. Both were invisible until something asserted them.
- **Product-minded analytics** — built 10+ Power BI dashboards over 15 KPIs and cleaned and analysed 30+ datasets during a 300-hour applied programme.

## Certifications

| Certification | Issuer |
|---|---|
| Power BI Data Analyst Associate (PL-300) | Microsoft |
| AI Engineering Professional Certificate | IBM |
| Data Analytics Professional Certificate | Google |

## Stack

**Languages** Python · SQL · TypeScript · JavaScript  
**AI/ML** PyTorch · scikit-learn · TensorFlow / TFLite · Ultralytics YOLO · Hugging Face Transformers · MediaPipe · LangChain · Unsloth  
**Data & backend** pandas · NumPy · scikit-learn · FastAPI · Streamlit · Qdrant · BM25  
**Frontend & BI** React 19 · Vite · Tailwind · Radix UI · Three.js · WebRTC · Power BI · Tableau  
**Practice** pytest · Ruff · GitHub Actions · Docker · Render

## Currently learning (October 2026)

- LLM evaluation frameworks and production guardrails
- Real-time computer vision on edge devices (TFLite / ONNX)
- Bilingual (Arabic/English) retrieval and generation

## Education

BSc, Management Information Systems — MCI Academy, Cairo (2019–2023), GPA 3.7/4.0.  
Coursework in data analytics, database systems, business intelligence, statistics and information systems management.

## Languages

Arabic — native · English — professional working proficiency

---

## Get in touch

The fastest way to reach me is [LinkedIn](https://linkedin.com/in/bashar-sayed-972110220) or email: **basharsayed2020@gmail.com**

I am actively looking for AI / Data Analytics roles where the work has to survive contact with real users. If you are hiring, or you want to talk about retrieval, computer vision or assistive technology, I would be glad to hear from you.