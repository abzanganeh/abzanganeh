# Alireza Barzin Zanganeh  
AI/ML Software Engineer | Back-End & ML Infrastructure  
Camas, WA  
[Email](mailto:alireza@zanganehai.com) | [LinkedIn](https://www.linkedin.com/in/alireza-barzin-zanganeh-2a9909126)

## About Me

I'm a software engineer with a strong foundation in back-end development, infrastructure design, and machine learning systems. Over the past few years, I've transitioned into AI and GenAI through structured training and hands-on project work. My focus is on building reliable, interpretable ML applications and integrating them into real-world systems.

## Learning Journey

I'm completing Interview Kickstart's AIML Software Engineering Program, which covers the full ML lifecycle. My learning approach combines theory, implementation, and project-based validation.

### Recently Completed
- Python for ML and data analysis  
- Pandas for feature engineering and statistical workflows  
- Seaborn and Matplotlib for data visualization  
- Supervised and unsupervised learning models (regression, classification, clustering, dimensionality reduction)  
- Deep learning architectures including CNNs, RNNs, and Transformers (BERT, LLMs)  
- ML model deployment strategies and evaluation techniques  
- Agentic AI frameworks: tool-calling agents, multi-step reasoning, and autonomous workflows

### Currently Exploring
- Large Language Models (LLMs): fine-tuning, embeddings, and retrieval-augmented generation  
- NLP pipelines: tokenization, vectorization, semantic search  
- Prompt engineering and GenAI system design  
- Advanced agentic AI patterns and production-grade system architecture
- End-to-end ML application development with LLM integration  

## Featured Projects
### Fraud Shield AI (In Progress)  
Capstone project -- an end-to-end fraud detection system combining ML pipelines with real-time data processing.

**Technical Stack**: Python, Spark, PyTorch (more details coming as the project progresses)
### [Movie Agent Service](https://github.com/abzanganeh/movie-agent-service) & [Demo](https://github.com/abzanganeh/movie-agent-demo)  
A production-grade agentic AI system for movie discovery using tool-calling agent architecture.

**Senior-Level Implementation Highlights:**
- **Architecture Design**: Chose tool-calling agent over ReAct for production reliability. Implemented clear separation of concerns: Service (rules + state) → Agent (reasoning) → Tools (execution) → Service (validation)
- **OOP Principles**: Applied Single Responsibility, Separation of Decision/Action, Dependency Inversion, Factory Pattern, and Strategy Pattern throughout the codebase
- **Design Philosophy**: "No class should decide and act at the same time unless it is an Agent" - enforced strict separation between decision-making (e.g., `SimilarityQueryAnalyzer`) and action execution (e.g., `MovieSearchTool`)
- **State Management**: Built session-based memory isolation with stateless service design for scalability
- **Tool Integration**: Implemented RAG with FAISS vector store, multi-tool orchestration (search, statistics, quiz generation, vision analysis)
- **Error Handling**: Graceful degradation with validation layers and structured error responses
- **Frontend Architecture**: Decoupled Flask presentation layer from agent logic with clean API boundaries

**Technical Stack**: Python, LangChain, FAISS, OpenAI/Groq APIs, Flask, JavaScript

---

### [Churn Risk Intelligence](https://github.com/abzanganeh/churn_risk_intelligence)  
Predictive modeling for customer churn using structured telecom data.

**Implementation Highlights:**
- Applied advanced feature engineering and correlation analysis
- Trained and evaluated multiple classifiers with cross-validation
- Delivered actionable insights for retention strategies with business-focused metrics
- Implemented proper train/validation/test splits with stratified sampling

**Technical Stack**: Python, Pandas, Scikit-learn, Matplotlib

---

### [Bank Term Deposit Prediction](https://github.com/abzanganeh/bank-term-deposit-prediction)  
Binary classification model to predict term deposit subscriptions.

**Implementation Highlights:**
- Explored imbalanced data handling with SMOTE and precision-recall tradeoffs
- Used interpretable models (logistic regression, decision trees) for business decision support
- Created comprehensive visualizations for model explainability
- Implemented proper evaluation metrics for imbalanced classification

**Technical Stack**: Python, Scikit-learn, Imbalanced-learn, Seaborn

---

### [Flask ML Website](https://github.com/abzanganeh/flask_ml_website)  
A full-stack web application integrating a trained ML model into a Flask-based interface.

**Implementation Highlights:**
- Built responsive UI for user input and real-time prediction output
- Deployed classification model with production-ready error handling
- Demonstrated end-to-end ML integration from training to deployment
- Implemented proper API design with request validation

**Technical Stack**: Python, Flask, HTML/CSS/JavaScript, Scikit-learn

---

### [Signal Strength Classification](https://github.com/abzanganeh/signal_strength)  
Classified signal strength data using supervised learning techniques.

**Implementation Highlights:**
- Cleaned and transformed raw signal data with robust preprocessing pipelines
- Applied SVM and k-NN classifiers with hyperparameter tuning
- Evaluated model performance using cross-validation and proper metrics
- Implemented data validation and feature standardization

**Technical Stack**: Python, Scikit-learn, Pandas, NumPy

## Professional Background

I've contributed to back-end systems, mobile SDKs, and ML-integrated platforms using Python, Java, and React. My experience includes CI/CD integration with GitHub Actions and Jenkins, and deploying ML-driven risk engines in identity security environments. Prior to my technical career in the U.S., I led strategic modeling and infrastructure planning for multimillion-dollar ventures in fintech and manufacturing.
