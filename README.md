


**MS AI Student @ UT Austin**

📧 [ashita0904@gmail.com](mailto:ashita0904@gmail.com) | 💼 [LinkedIn](https://www.linkedin.com/in/ashita-chandnani/) | 💻 [GitHub](https://github.com/AshitaC)

---


## About Me
Master’s in Artificial Intelligence student at UT Austin, building on a strong foundation from a recent MS in Computer Science (4.0 GPA). Building specialization in Generative AI systems, agentic workflows, and cloud-native ML infrastructure. 

Passionate about bridging LLM research and real-world systems at scale, my hands-on experience includes engineering RAG pipelines, multi-turn conversational agents, and automated CI/CD MLOps pipelines deployed on AWS. **Actively seeking AI Engineering, Machine Learning Engineering, or Data Science internships and roles for 2027.**

---


## Technical Skills

- **Generative AI & LLMs**: LangChain, LangGraph, RAG, Agentic Workflows, OpenAI API, Llama 3.3, FAISS, ChromaDB, HuggingFace Transformers, Prompt Engineering
- **Cloud & MLOps**: AWS Bedrock AgentCore, EC2, S3, ECR, Docker, GitHub Actions (CI/CD), ML Pipeline Orchestration
- **Machine Learning**: PyTorch, TensorFlow, BERT, Scikit-Learn, Feature Engineering, Model Evaluation
- **Data & Backend**: Python, FastAPI, Streamlit, SQL, Pandas, NumPy, Power BI




## Education

-  **M.S., Artificial Intelligence** — The University of Texas at Austin, Expected Dec 2027  
   Focus: Deep Learning Architectures, Scalable AI Systems, and MLOps Optimization.

-  **M.S., Computer Science** — Boise State University, Aug 2025 | GPA: 4.0/4.0  
   Research focused on Trust-Based AI, NLP, and Misinformation Mitigation using PyTorch.

-  **M.Tech., Electrical Engineering** — Indian Institute of Technology (IIT) Gandhinagar | CPI: 9.2/10.0

-  **B.E., Electronics & Communication Engineering** — Government Engineering College Bikaner (University of Rajasthan) | CGPA: 8.5/10.0

-  **Certifications:** Linear Algebra & Calculus for ML (DeepLearning.AI), Introduction to Statistics (Stanford Online), Data Science with Python (Edureka), SQL, Python & Power BI (Codebasics)
  
---


## Experience

-  **Graduate Researcher, Computer Science** — Boise State University | 2024 – 2025  
   Trust-aware recommender systems and misinformation mitigation (see *Trust-aware Neural News Recommender* below).

-  **Graduate Researcher, Electrical & Computer Engineering (Doctoral Program)** — Boise State University | 2016 – 2020  
   *  Research in printed and flexible electronics: graphene- and carbon-nanotube-based sensors and graphene inks; funded by an **IGEM fellowship**.
   *  Co-authored *"A Review of Inkjet Printed Graphene and Carbon Nanotubes Based Gas Sensors,"* **Sensors (MDPI), 2020** — **120+ citations**.
   *  Co-inventor, **US Patent Application 15/916,712**, "Modular Solar Cell Electrical Power Generating Layer for Low Earth Orbit Space Suits" (2018).
   *  Passed the doctoral comprehensive exam; 4.0 GPA in graduate coursework including Deep Learning with Python, Digital IC Design, and Nanoscale Transport.
   *  Transitioned to machine learning, completing an M.S. in Computer Science (2025).

-  **Assistant Professor, Electronics & Communication Engineering** — Nirma University, Ahmedabad | 2014 – 2015  
   Taught Digital Electronics and Communication Systems; mentored undergraduate student projects.

## Publications

-  M. S. Ahmed, **A. Chandnani**, F. Spezzano, "Reproducibility of FANAR: Adapting a Trust-based News Recommender for Fake News Mitigation to Public Benchmarks," under review at *ECIR 2027* (Reproducibility track).
-  T. Pandhi, **A. Chandnani**, H. Subbaraman, D. Estrada, "A Review of Inkjet Printed Graphene and Carbon Nanotubes Based Gas Sensors," *Sensors*, 20(19), 5642, 2020. [doi:10.3390/s20195642](https://doi.org/10.3390/s20195642) — 120+ citations
-  **A. Chandnani** et al., "Design and Analysis of Piezoresistive Polyimide Nanocantilevers for Surface Stress Sensing Applications," *International Conference on MEMS and Sensors*, 2014.

---

## Projects

### Semiconductor Research Assistant RAG | LangChain, Groq, ChromaDB, Llama 3.3, Streamlit
**[Live App](https://semiconductor-research-assistant-rag.streamlit.app/) | [GitHub Repository](https://github.com/AshitaC/semiconductor-research-assistant-rag)**

*   Engineered a **Retrieval-Augmented Generation (RAG)** system tailored for the semiconductor industry, utilizing **LangChain** and **Llama 3.3 70B** to automate technical research.
*   Optimized data retrieval by implementing a vector search pipeline with **ChromaDB** and **HuggingFace embeddings**, enabling cited Q&A from **complex PDFs** and **URLs**.
*   Developed a **production-ready interface** using **Streamlit**, featuring session-isolated storage and Markdown export functionality for secure research workflows.

![Semiconductor Research Assistant](/assets/img/Semiconductor_RAG.PNG)

---


### Conversational Agent with Long-Term Memory | AWS Bedrock AgentCore, LangGraph, FAISS, Groq  

**[GitHub Repository](https://github.com/AshitaC/Conversational-Agent_AWS-BedrockAgentCore)**

* Designed and deployed a **stateful conversational AI agent** on AWS Bedrock AgentCore with **cross-session memory** and **RAG-based FAQ** retrieval.

*	Engineered three **agentic LangChain tools** backed by **FAISS** vector store with HuggingFace embeddings for dynamic FAQ retrieval.

*	Built custom **memory middleware** that semantically retrieves user preferences before each LLM call enabling **context retention** across sessions.

*	Containerized with **Docker** and integrated **CloudWatch observability** for serverless scaling on **AWS managed runtime**.

![Agent Behavior With vs Without Memory](/assets/img/WithAndWithoutMemory.png)

--- 

### MLOps Pipeline for Insurance Lead Prediction | FastAPI, Docker, MongoDB Atlas, AWS, GitHub Actions
**[GitHub Repository](https://github.com/AshitaC/MLOps-Pipeline-for-Insurance-Lead-Prediction)**

*   Architected a **production-grade MLOps pipeline** for vehicle insurance lead prediction, automating the end-to-end lifecycle from data ingestion to cloud deployment.
*   Engineered **modular ML pipelines** for data validation, transformation, and model training using **Python** and **FastAPI**, improving code maintainability and scalability.
*   Developed a **CI/CD workflow** with **GitHub Actions** and **Docker**, enabling automated containerization and deployment to **AWS EC2** via **Amazon ECR**.
*   Implemented **cloud-native data management** by integrating **MongoDB Atlas** for training data and **AWS S3** as a centralized model registry.


![Insurance Lead Prediction](/assets/img/MlopsInsurance.PNG)

---

### Financial KPI Extractor | Python, LangChain, Streamlit, Llama 3
**[Live App](https://financial-kpi-extractor.streamlit.app/) | [GitHub Repository](https://github.com/AshitaC/financial-kpi-extractor)**

*   Engineered a **Generative AI application** to automate the extraction of critical financial metrics (Revenue, EPS) from unstructured news articles.
*   Implemented **robust data structuring** using **LangChain** and custom **System Prompts** to enforce strict JSON output formatting from the **Llama 3.3** model, ensuring downstream data compatibility.
*   Developed a responsive **Streamlit** frontend featuring side-by-side **Plotly** visualizations and CSV data export for financial analysis.
*   Deployed the full-stack application to the cloud, utilizing **Groq API** for low-latency text processing.

![Financial App Screenshot](https://github.com/user-attachments/assets/b64e0beb-da26-4cf3-9b99-b842f2077f23)

---

### Trust-aware Neural News Recommender | PyTorch, BERT, HuggingFace
**[GitHub Repository](https://github.com/AshitaC/Misinformation-Aware-News-Recommender-System)**

*  **Implemented a trust-based neural recommender system** in **PyTorch** specifically designed to mitigate the spread of misinformation and prioritize ethical AI principles.
*  Built **attention-based news-space and neighbor-space aggregation** over frozen **BERT** embeddings, with a **Beta trust model** that filters untrustworthy users out of each recommendation neighborhood.
*  Achieved **48% higher MRR@10** than the strongest of **7 classical baselines** on PolitiFact, with a lower fake-news ratio than every collaborative-filtering baseline; ablation showed trust filtering alone adds **18.8% MRR@10**.
*  Engineered reproducible research pipelines using **HuggingFace Transformers** on public benchmarks (FakeNewsNet PolitiFact, FakeHealth; 140K+ user-news interactions).
*  **Paper:** co-author of a reproducibility study under review at ECIR 2027 (see Publications).


<img src="/assets/img/ModelOverview.png" width="45%" /> <img src="/assets/img/ModelArchitecture.png" width="45%" />

---

### Business Insights 360 Dashboard | Power BI, SQL, DAX
**[Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzc2ZTNjNTgtNDg0OC00NjFlLThmNjAtMDFmNmI3ZDVlYWM2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) | [GitHub Repository](https://github.com/AshitaC/PowerBI---Business-Insights)**

* Designed an end-to-end business intelligence solution unifying Finance, Sales, Marketing, and Supply Chain analytics using **Power BI**.
* Engineered complex data transformations with **Power Query** and utilized advanced **DAX** functions to drive calculated measures.
* Built a dynamic **P&L engine** and profitability matrices to enable granular analysis of customer and product performance.
* Implemented forecasting accuracy modules and executive summary views to facilitate data-driven strategic planning.

![Finance View](/assets/img/FinanceView.png)

---


