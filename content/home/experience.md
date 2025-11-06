---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

id: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: AI Engineer
    company: Delineate Inc.
    company_url: 'https://gigatechltd.com/'
    company_logo: delineate_logo
    location: Remote
    date_start: '2024-10-01'
    date_end: ''
    description: |2-
      * Developed a Multi-Agent Data Extraction Pipeline for diverse files (PDF, DOCX, Code), outperforming general-purpose LLMs (Gemini 2.5 Pro, Claude Opus) by 15% on domain-specific extraction (e.g., dosing, covariates) and 10% on general extractions evaluated on 150 sources. Achieved 10% higher accuracy for large tables with >100 rows. [Demo](https://youtu.be/jnJo6u7b0mc?si=VbyaCR_pPT9hyC9u)
      * Designed the pipeline to automatically identify multiple fields from user queries, generate structured table outputs, and ensure correct data typing.
      * Engineered an advanced paper layout system that improved Retrieval-Augmented Generation (RAG) performance by 12%.
      * Trained a YOLOv11-based subfigure model (Global Average IoU: 0.8919) to decompose composite figures and extract metadata (captions, legends), boosting visual information retrieval.
      * Enhanced image and table data with section-level metadata, captions, footnotes, and summaries to enable advanced image-based search queries (e.g., “Find breast cancer papers that contain drug name on the x-axis and dosage amount on the y-axis”).
      * Created a production-grade Qdrant vector database containing 40M paper PDFs for scalable research paper retrieval.
      * Engineered a novel image Bounding Box (BBox) filtering algorithm that reduced false positives by 34% through a dynamic minimum BBox size heuristic integrated into NMS filtering.
      * Collaborated with pharmaceutical scientists to build an automated QC system for data cleaning and validation (unit standardization, column normalization, biomarker validation, dosing range checks), improving data accuracy to 97%.
      * Established scalable MLOps and secure deployment infrastructure for high-throughput inference services using Nvidia TensorRT and Triton Inference Server (TIS).
      * Migrated long-running tasks to Celery with RabbitMQ (RMQ) for event-driven architecture and decoupled data transfer.
      * Implemented event-driven autoscaling in Kubernetes (K8s) using KEDA to scale Celery worker pods dynamically based on RMQ queue length, ensuring stable throughput.
      * Enforced Zero Trust Security architecture by isolating all cloud services into private networks and securing inter-service communication with VPC Endpoints and S2S tokens.

  - title: Jr. AI Engineer
    company: Giga Tech Ltd.
    company_url: 'https://gigatechltd.com/'
    company_logo: gigatech-logo
    location: Dhaka, Bangladesh
    date_start: '2022-09-01'
    date_end: '2024-10-01'
    description: |2-
      * Achieved SOTA in Low-Resource Bangla NLP (NER, POS, QA, Lemmatization), exceeding 90% KPI for all modules.
      * Set new NER SOTA (81.85% Macro F1, +6% vs. prior SOTA, 90.49% Macro F1 on delivered dataset) and POS SOTA using a novel hierarchical voting mechanism among SLM predictions. [Demo](https://corpus.bangla.gov.bd/corpus/ml-model/tree-bank)
      * Delivered SOTA for QA (SQuAD-bn) using a novel loss function to balance null/non-null answers, outperforming prior SOTA by 6%. [Demo](https://corpus.bangla.gov.bd/corpus/ml-model/question-answer)
      * Co-developed and open-sourced the first production-grade Bangla Lemmatizer (96.36% accuracy) and Emotion Recognition system. [GitHub](https://github.com/eblict-gigatech/BanLemma), [Demo](https://sentiment.bangla.gov.bd)
      * Engineered Advanced LLM Methodologies and Data Pipelines for complex generation and tagging tasks.
      * Built GPT-4o inference pipelines (NER, Coref) using the [ReAct](https://arxiv.org/abs/2210.03629) prompting framework, matching fine-tuned model performance.
      * Resolved severe class imbalance in sequence tagging using a sentence resampling pipeline and advanced loss functions (Dice, Focal, CurricularFace).
      * Architected Core MLOps and Data Versioning Infrastructure to manage complete model and data lifecycles using DVC and MLflow.


  - title: Research Assistant
    company: Qatar Computing Research Institute
    company_url: 'https://www.hbku.edu.qa/en/qcri'
    company_logo: qcri_logo
    location: Remote
    date_start: '2021-09-01'
    date_end: '2021-12-31'
    description: |2-
      * Pretrained a HuBERT model on Bangla ASR dataset for joint task of speech and speaker recognition pipeline using SpeechBrain.
      * Assisted in enriching existing open source Bangla ASR datasets by adding more scripted audio and correcting existing annotation
  
  - title: Undergraduate Teacher Assistant
    company: BRAC University
    company_url: 'https://www.bracu.ac.bd/'
    company_logo: brac_uni
    location: Dhaka, Bangladesh
    date_start: '2020-04-01'
    date_end: '2022-04-30'
    description: |2-
      * Helped students with different coding assignments and helped teachers in checking scripts.
      * Assisted students in conducting research in various fields and submitting papers to conferences.
      * Assisted Teachers in lab classes and helped students with different course materials during consultation hour.

design:
  columns: '1'

advanced:
  css_class: "experience-section"
---
