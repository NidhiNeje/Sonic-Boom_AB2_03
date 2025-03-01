# Sonic-Boom_AB2_03
A GitHub repository of entire documentation of Enhancing clinical decision support systems with retrieval- augmented generation (RAG) model  

**PROBLEM STATEMENT 3 (PS 3)**

**ClinQAI (CLINICAL QUERY AI): ENHANCING CLINICAL DECISION SUPPORT SYSTEMS WITH RETRIEVAL-AUGMENTED GENERATION (RAG) MODEL**  

**INTRODUCTION**  
"Artificial Intelligence (AI) in healthcare could boost India's GDP by USD 25-30 billion by 2025, driven by initiatives like the IndiaAI Mission." quotes The Economic Times according to a report from Deloitte, enhnacing accesibilty, diagnostics and treatment outcomes. The IndiaAI Mission focuses towards setting the stage for a digitally empowered healthcare ecosystem, with resposible AI integration and enhnaced data security.In recent times, there has been a significant surge in research articles and industry analyses on transformative role AI plays in medical decision supoort. With advancements in modern healthcare, Clinical Decision Support Systems (CDSS) has emerged in assisting with diagnostics, recommendations in treatment and healthcare management.   

Conventional CDSS is associated with drawbacks in terms of limited knowledge updates and poor contextual understanding. In addition to this, traditional Machine Learning (ML) models and Large Language Models (LLMs) are powerful, but lack real-time adaptability and evidence based decision making capabilities.The future of AI in healthcare lies in ethical human-centred AI models that enhance- but not replace clinical expertise. A comprehensive solution must be formulated for integration of retrievl-based AI models and real-time patient monitoring.  

To mitigate all the drawbacks of conventional CDSS, the aim of our project revolves around implementing a unique approach to enhance clinical decision support making it more interpretable, data-driven and highly adaptive to faciliate most relevant and evidence-based insights for improving patient outcomes. The ultimate goal is to successfully generate a Retrieval-Augmentation Model (RAG) model by integrating real-time information retrieval with natural language generation.  

**PROPOSED SOLUTION**  
Our model aims towards levaraging the contribution of AI in healthcare by developing model with improved diagnosis and prediction of disease, provide personal treatment strategies and intelligently retrive data and knowledge for integration. The selected idea incorporates development of a RAG model which is an AI framework capable of retrieving relevant medical knowledge from large databases, generation of comntext-aware repsonses,improving accuracy in diagnostics by grounding responses in real-world data of patients.  

Our RAG-based CDSS model comprises of following components:  
| COMPONENT | SIGNIFICANCE IN MODEL |
|----------|----------|
| Facebook AI Similarity Search (FAISS)    | To efficiently retrieve medical records and research papers   |
| Biomedical Bidirectional Encoder Representations from Transformers (BioBERT)    | To extract and understand the medical language using semnatic approach   |
| MIMIC-IV, PubMed and Kaggle ICU Datasets    | To provide structured and unstructured data medical data for real-world analysis   |
| Transformer-based LLM    | To generate responses based on retrieved knowledge   |  

The novelty and advantages introduced in ClinQAI over existing models are:  
-->Retrieving latest medical evidence before generating responses i.e. Real-Time Retrieval of Knowledge.
-->Domain specific language understanding using BioBERT that improves clinical accuracy.
-->Optimization for larger medical datasets because FAISS enables fast similarity research across millions of patient records.
