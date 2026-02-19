


**MS Computer Science - AI & ML**

📧 [ashita0904@gmail.com](mailto:ashita0904@gmail.com) | 💼 [LinkedIn](https://www.linkedin.com/in/ashita-chandnani/) | 💻 [GitHub](https://github.com/AshitaC)

---

## About Me

AI Engineer specializing in production grade Generative AI systems, agentic workflows, and cloud-native ML infrastructure. Recent Master's in CS (4.0 GPA) with hands-on experience building RAG pipelines, multi-turn conversational agents, and end-to-end MLOps pipelines deployed on AWS. Passionate about bridging LLM research and real-world systems at scale. Actively seeking roles in AI Engineering, MLOps, or Applied ML.

---


## Technical Skills

- **Generative AI & LLMs**: LangChain, LangGraph, RAG, Agentic Workflows, OpenAI API, Llama 3.3, FAISS, ChromaDB, HuggingFace Transformers, Prompt Engineering
- **Cloud & MLOps**: AWS Bedrock AgentCore, EC2, S3, ECR , Docker, GitHub Actions (CI/CD), ML Pipeline Orchestration
- **Machine Learning**: PyTorch, TensorFlow, BERT, Scikit-Learn, Feature Engineering, Model Evaluation
- **Data & Backend**: Python, FastAPI, Streamlit, SQL, Pandas, NumPy, Power BI



## Education
- **M.S., Computer Science** — Boise State University, Aug 2025 | GPA: 4.0/4.0
- **M.S., Electrical & Computer Engineering**  — IIT Gandhinagar, India | CGPA: 9.2/10.0
- **B.S., Electrical Engineering**— University of Rajasthan University, India | CGPA: 8.5/10.0
---

## Projects

### Semiconductor Research Assistant RAG | LangChain, Groq, ChromaDB, Llama 3.3, Streamlit
**[Live App](https://semiconductor-research-assistant-rag.streamlit.app/) | [GitHub Repository](https://github.com/AshitaC/semiconductor-research-assistant-rag)**

*   Engineered a **Retrieval-Augmented Generation (RAG)** system tailored for the semiconductor industry, utilizing **LangChain** and **Llama 3.3 70B** to automate technical research.
*   Optimized data retrieval by implementing a vector search pipeline with **ChromaDB** and **HuggingFace embeddings**, enabling sub-second, cited Q&A from **complex PDFs** and **URLs**.
*   Developed a **production-ready interface** using **Streamlit**, featuring session-isolated storage and Markdown export functionality for secure research workflows.
*   **Reduced inference latency by 70%** by leveraging **Groq LPUs**, ensuring a real-time, responsive user experience for technical analysis.

![Semiconductor Research Assistant](/assets/img/Semiconductor_RAG.PNG)

---


### Conversational Agent with Long-Term Memory | AWS Bedrock AgentCore, LangGraph, FAISS, Groq  

**[GitHub Repository](https://github.com/AshitaC/Convesational-Agent_AWS-BedrockAgentCore/tree/main)**

* Designed and deployed a **stateful conversational AI agent** on AWS Bedrock AgentCore with **cross-session memory** and **RAG-based FAQ** retrieval.

*	Engineered three **agentic LangChain tools** backed by **FAISS** vector store with HuggingFace embeddings for dynamic FAQ retrieval.

*	Built custom **memory middleware** that semantically retrieves user preferences before each LLM call enabling **context retention** across sessions.

*	Containerized with **Docker** and integrated **CloudWatch observability** for serverless scaling on **AWS managed runtime**.

![Agent Behavior With vs Without Memory](/assets/img/WithAndWithoutMemory.png)

--- 

### MLOps Pipeline for Insurance Lead Prediction | FastAPI, Docker, MongoDB Atlas, AWS, GitHub Actions
**[Live App](http://34.231.138.39:5000/) | [GitHub Repository](https://github.com/AshitaC/MLOps-Pipeline-for-Insurance-Lead-Prediction)**

*   Architected a **production-grade MLOps pipeline** for vehicle insurance lead prediction, automating the end-to-end lifecycle from data ingestion to cloud deployment.
*   Engineered **modular ML pipelines** for data validation, transformation, and model training using **Python** and **FastAPI**, improving code maintainability and scalability.
*   Developed a **CI/CD workflow** with **GitHub Actions** and **Docker**, enabling automated containerization and deployment to **AWS EC2** via **Amazon ECR**.
*   Implemented **cloud-native data management** by integrating **MongoDB Atlas** for training data and **AWS S3** as a centralized model registry.


![Insurance Lead Prediction](/assets/img/MlopsInsurance.PNG)

---

### Financial KPI Extractor | Python, LangChain, Streamlit, Llama 3
**[Live App](https://financial-kpi-extractor.streamlit.app/) | [GitHub Repository](https://github.com/AshitaC/financial-kpi-extractor)**

*   Engineered a **Generative AI application** to automate the extraction of critical financial metrics (Revenue, EPS) from unstructured news articles with high precision.
*   Implemented **robust data structuring** using **LangChain** and custom **System Prompts** to enforce strict JSON output formatting from the **Llama 3.3** model, ensuring downstream data compatibility.
*   Developed a responsive **Streamlit** frontend featuring side-by-side **Plotly** visualizations and CSV data export for financial analysis.
*   Deployed the full-stack application to the cloud, utilizing **Groq API** for low-latency text processing.

![Financial App Screenshot](https://github.com/user-attachments/assets/b64e0beb-da26-4cf3-9b99-b842f2077f23)

---

### Trust-aware Neural News Recommender | PyTorch, BERT, HuggingFace
**[GitHub Repository](https://github.com/AshitaC/Misinformation-Aware-News-Recommender-System)**

*  **Implemented a trust-based neural recommender system** in **PyTorch** specifically designed to mitigate the spread of misinformation and prioritize ethical AI principles.
*  Architected a **multi-head attention mechanism** to integrate **BERT-based content embeddings** with source reliability metrics, creating highly robust user representations.
*  Engineered reproducible research pipelines using **HuggingFace Transformers** to validate model performance against industry-standard benchmarks.

*  **Publication** - A. Chandnani,  M. S. Ahmed, and F. Spezzano. **"Reproducibility of FANAR: Adapting a Trust-based News Recommender for Fake News Mitigation to Public Benchmarks."** Under review at SIGIR 2026 (49th International ACM SIGIR Conference on Research and Development in Information Retrieval).

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


