# Alexey Tyurin - GenAI Engineer Portfolio

## 👨‍💻 About Me

**LinkedIn:** [https://www.linkedin.com/in/alexey-tyurin-36893287/](https://www.linkedin.com/in/alexey-tyurin-36893287/)

I am a GenAI engineer specializing in optimization, autonomy, and security of Agentic AI solutions. With deep expertise in machine learning, AI agent development, and production-ready AI systems, I focus on building scalable, secure, and cost-effective AI solutions that deliver real business value.

### 🚀 Skills and Interests

- **AI/ML Technologies:** Agentic AI, Large Language Models (LLMs), Small Language Models (SLMs), Fine-tuning, Multi-agent Systems
- **AI Frameworks:** LangGraph, LangChain, OpenAI GPT, Google ADK, Google A2A Protocol, Model Context Protocol (MCP)
- **Specialized Areas:** Content Moderation, Prompt Security, AI Agent Orchestration, Imbalanced Dataset Handling
- **Cloud Platforms:** Google Cloud Platform (Vertex AI), Cloud Run, Docker, Kubernetes
- **Programming:** Python, Java, JavaScript, SQL
- **Research Focus:** Autonomous AI systems, AI safety, production optimization, cost-effective AI deployment

---

## 🏆 Featured Projects

### 1. A2A Double Validation - POC for Multi-Agent autonomous System
**Repository:** [https://github.com/alexey-tyurin/a2a-double-validation](https://github.com/alexey-tyurin/a2a-double-validation)

#### 📋 Description
A sophisticated multi-agent system for query processing with comprehensive safety verification and critique, built using Google's A2A protocol, Google ADK, Llama Prompt Guard 2, Gemma 3, and Gemini 2.0 Flash.

#### 💼 Why This Project Matters
- **Business Value:** Enables autonomous AI agents to operate safely in production without constant human supervision, reducing operational costs while maintaining security standards
- **Breadth & Depth:** Integrates multiple cutting-edge AI technologies (A2A protocol, ADK, multiple LLMs) in a cohesive system architecture
- **Scalability:** Designed for cloud deployment with Google Cloud Run, supporting enterprise-scale operations
- **Production Ready:** Includes comprehensive deployment scripts, monitoring, and security features for real-world use

#### 🔧 Key Features
- **Double Validation Architecture:** Input validation with Llama Prompt Guard 2 and output validation with Gemini 2.0 Flash
- **Multi-Agent Coordination:** Four specialized agents (Manager, Safeguard, Processor, Critic) working in harmony
- **Google A2A Protocol:** Standardized inter-agent communication for reliability and scalability
- **Cloud-Native Deployment:** Complete GCP deployment with Cloud Run, Secret Manager, and automated scaling
- **Security-First Design:** Built-in prompt injection protection and content safety measures

#### 🛠️ Technologies Overview
- **AI Models:** Llama Prompt Guard 2 (86M parameters), Gemma 3, Gemini 2.0 Flash
- **Frameworks:** Google Agent Development Kit (ADK), Google A2A Protocol
- **Infrastructure:** Google Cloud Platform, Cloud Run, Secret Manager, Container Registry
- **Languages:** Python, Shell scripting

#### 💻 Tech Stack
```
Backend: Python, FastAPI, Google ADK
AI/ML: Llama Prompt Guard 2, Gemma 3, Gemini 2.0 Flash
Cloud: Google Cloud Run, Vertex AI, Secret Manager
Communication: A2A Protocol, HTTP/REST APIs
Deployment: Docker, Cloud Build, Infrastructure as Code
```

#### 📸 Screenshots
![Architecture](screenshots/a2a_arch.png)


*Screenshots are available in my article - show agent interaction flows, cloud deployment dashboard, 
local and cloud run and tests results:*
https://www.aiacceleratorinstitute.com/how-to-build-autonomous-ai-agent-with-google-a2a-protocol/

---

### 2. Fine-Tuning GPT for Hospitality - Cost-Effective AI Optimization
**Repository:** [https://github.com/alexey-tyurin/fine-tuning-gpt](https://github.com/alexey-tyurin/fine-tuning-gpt)

#### 📋 Description
A comprehensive project demonstrating how to fine-tune GPT-4o-mini models for hospitality chatbot intent classification, achieving higher accuracy than GPT-4.1 while significantly reducing costs and improving response times.

#### 💼 Why This Project Matters
- **Business Value:** Achieved 60% accuracy vs GPT-4.1's 52% while reducing operational costs by up to 90% through smaller, specialized models
- **Breadth & Depth:** Covers complete ML pipeline from dataset creation to production deployment with real-world performance metrics
- **Scalability:** Demonstrates how domain-specific fine-tuning scales better than general-purpose large models for specific use cases
- **Production Ready:** Includes comprehensive evaluation metrics, deployment guides, and cost analysis for business decision-making

#### 🔧 Key Features
- **Domain-Specific Optimization:** Specialized for hospitality industry with 40 common intent classifications
- **Superior Performance:** 60% accuracy on ambiguous queries vs 52% for GPT-4.1
- **Cost Efficiency:** Significant cost reduction through optimized model size and inference speed
- **Comprehensive Evaluation:** Detailed performance comparison across multiple model variants
- **Synthetic Data Generation:** Using LLM generated datasets with comprehensive set of hospitality intents   
- **HuggingFace Integration:** Created and published datasets for community use and research

#### 🛠️ Technologies Overview
- **AI Models:** GPT-4o-mini, GPT-4.1, GPT-3.5-turbo (comparative analysis)
- **Fine-tuning:** OpenAI Fine-tuning API, Supervised Fine-Tuning (SFT)
- **Datasets:** Custom hospitality intent classification datasets (400 training, 100 evaluation samples)
- **Platforms:** OpenAI API, HuggingFace Hub

#### 💻 Tech Stack
```
AI/ML: OpenAI GPT models, Fine-tuning API
Data: Custom hospitality datasets, HuggingFace Hub
Development: Python, Jupyter Notebooks
Evaluation: Custom metrics, performance benchmarking
Deployment: API integration, cost optimization
```

#### 📸 Screenshots

![Fine-tuning Accuracy Improvement](screenshots/SFT_evals_final.png)

*Screenshots are available in repository and my Medium article
https://medium.com/@altyurin3/fine-tuning-gpt-4o-mini-for-hospitality-chatbots-outperforming-gpt-4-1-at-a-fraction-of-the-cost-1f56e72e9ce0 - show performance comparisons, cost analysis, and fine-tuning results*

---

### 3. AI Agent with MCP - Content Moderation System
**Repository:** [https://github.com/alexey-tyurin/ai-agent-mcp](https://github.com/alexey-tyurin/ai-agent-mcp)

#### 📋 Description
A production-ready content moderation system leveraging OpenAI's moderation API through Google's Agent Development Kit (ADK) and Model Context Protocol (MCP), providing seamless content safety for AI applications.

#### 💼 Why This Project Matters
- **Business Value:** Provides free, scalable content moderation using OpenAI's API, protecting platforms from harmful content while maintaining user experience
- **Breadth & Depth:** Demonstrates cross-vendor AI integration (Google ADK + OpenAI + Llama) with dual transport protocols
- **Scalability:** Supports both local development and cloud deployment with comprehensive scaling options
- **Production Ready:** Complete deployment guides for cloud, on-premises, and hybrid environments

#### 🔧 Key Features
- **Cross-Vendor Integration:** Seamlessly combines Google ADK, OpenAI moderation API, and Llama models
- **Dual Transport Support:** Both Server-Sent Events (SSE) and Standard I/O (STDIO) protocols
- **Real-World Applications:** Educational platforms, customer service, content generation, healthcare chatbots
- **Comprehensive Testing:** Automated test scripts for all system components
- **Flexible Deployment:** Cloud, on-premises, edge, and hybrid deployment options

#### 🛠️ Technologies Overview
- **AI Integration:** OpenAI Moderation API, Google ADK, Llama models
- **Protocols:** Model Context Protocol (MCP), Server-Sent Events, Standard I/O
- **Architecture:** Microservices, containerized deployment, modular design

#### 💻 Tech Stack
```
Backend: Python, Google ADK, MCP
AI/ML: OpenAI Moderation API, Llama models
Protocols: MCP, SSE, STDIO
Deployment: Docker, Cloud platforms, Edge computing
Testing: Automated test suites, integration testing
```

#### 📸 Screenshots
![SSE Transport Architecture](screenshots/mcp-SSE-arch.png)
*Screenshots are available in repository and my Medium article in Google Cloud - Community https://medium.com/google-cloud/building-a-production-ready-ai-content-moderation-system-with-google-adk-and-model-context-protocol-8a3cf4a798f9 - show SSE and STDIO implementations, testing results, and deployment architectures*


---

### 4. AI Agent - ArXiv Research Paper Intelligence
**Repository:** [https://github.com/alexey-tyurin/ai-agent](https://github.com/alexey-tyurin/ai-agent)

#### 📋 Description
An intelligent agent that searches, analyzes, and ranks arXiv research papers using LangGraph, LangChain, OpenAI GPT-4, and DuckDuckGo, providing researchers with automated literature review capabilities.

#### 💼 Why This Project Matters
- **Business Value:** Automates time-consuming research tasks, enabling researchers and organizations to stay current with rapidly evolving AI/ML literature
- **Breadth & Depth:** Combines web scraping, natural language processing, and intelligent ranking algorithms in a cohesive research tool
- **Scalability:** Agent-based architecture allows for easy extension to other research domains and databases
- **Production Ready:** Robust error handling, rate limiting, and scalable architecture for research institutions

#### 🔧 Key Features
- **Automated Literature Review:** Intelligent search and analysis of arXiv research papers
- **Intelligent Ranking:** AI-powered relevance scoring and paper prioritization
- **Agent Architecture:** LangGraph-based workflow for complex research tasks
- **Research Optimization:** Saves researchers significant time in literature discovery

#### 🛠️ Technologies Overview
- **AI Frameworks:** LangGraph, LangChain for agent orchestration
- **AI Models:** OpenAI GPT-4 for analysis and ranking
- **Data Sources:** arXiv API, DuckDuckGo search integration
- **Architecture:** Agent-based system with workflow management

#### 💻 Tech Stack
```
AI/ML: OpenAI GPT-4, LangChain, LangGraph
Data Sources: arXiv API, DuckDuckGo Search
Backend: Python, async processing
Architecture: Agent-based workflows, microservices
APIs: RESTful APIs, rate limiting, error handling
```

#### 📸 Screenshots
![Final results with updated intent](screenshots/ai-agent-5.png)
*Screenshots are available in repository - show research paper analysis, ranking results, and agent workflow visualizations*

---

### 5. Imbalanced Datasets - Machine Learning Optimization
**Repository:** [https://github.com/alexey-tyurin/imbalanced_datasets](https://github.com/alexey-tyurin/imbalanced_datasets)

#### 📋 Description
A comprehensive study and implementation of techniques for handling imbalanced datasets in machine learning, covering various sampling methods, algorithm modifications, and evaluation strategies.

#### 💼 Why This Project Matters
- **Business Value:** Addresses one of the most common real-world ML challenges, improving model performance on minority classes in critical applications like fraud detection and medical diagnosis
- **Breadth & Depth:** Comprehensive coverage of data-level, algorithm-level, and hybrid approaches to class imbalance
- **Scalability:** Techniques applicable across different domains and dataset sizes
- **Production Ready:** Practical implementations with performance comparisons and best practice recommendations

#### 🔧 Key Features
- **Comprehensive Techniques:** Oversampling, undersampling, ensemble methods, cost-sensitive learning
- **Performance Analysis:** Detailed comparison of different approaches with real datasets
- **Best Practices:** Guidelines for choosing appropriate techniques based on dataset characteristics
- **Jupyter Implementations:** Interactive notebooks for experimentation and learning
- **Real-World Applications:** Examples from healthcare, finance, and other critical domains

#### 🛠️ Technologies Overview
- **ML Libraries:** scikit-learn, imbalanced-learn, pandas, numpy
- **Techniques:** SMOTE, Random Undersampling, Ensemble methods, Cost-sensitive algorithms
- **Evaluation:** Precision, Recall, F1-score, AUC-ROC, Precision-Recall curves

#### 💻 Tech Stack
```
ML/Data Science: Python, scikit-learn, imbalanced-learn
Data Processing: pandas, numpy, matplotlib, seaborn
Techniques: SMOTE, Random/Tomek sampling, Ensemble methods
Evaluation: Custom metrics, cross-validation, statistical testing
Visualization: matplotlib, seaborn, plotly
```

#### 📸 Screenshots
![Mean Recall for XGBoost for diabetic dataset](screenshots/imbalanced_datasets-xgboost.png)

*Screenshots are available in Jupyter Notebook imbalanced_datasets_notebook.ipynb in repository - show performance comparisons, sampling technique visualizations, and evaluation metrics*

---

## 📊 Project Statistics

- **Total Projects:** 5 major projects including POCs optimized for production
- **GitHub Stars:** 11 across repositories
- **Technologies Used:** 15+ AI/ML frameworks and tools
- **Cloud Platforms:** Google VertexAI Cloud Platform, OpenAI API, Meta, HuggingFace with multi-cloud expertise
- **Programming Languages:** Python (primary), JavaScript, SQL, Shell scripting
- **AI Models Integrated:** GPT-4, GPT-4o-mini, Gemini 2.0 Flash, Gemma 3, Llama, Llama Prompt Guard 2

## 🎯 Key Achievements

- **Cost Optimization:** Achieved 90% cost reduction while improving accuracy through strategic fine-tuning
- **Security Innovation:** Pioneered double validation architecture for AI agent safety
- **Cross-Platform Integration:** Successfully integrated multiple AI vendors (OpenAI, Google, Meta) in unified systems
- **Production Deployment:** Delivered cloud-native solutions with comprehensive CI/CD and monitoring
- **Open Source Contribution:** Created and published datasets and POCs for GenAI community benefit

## 📈 Impact Metrics

- **Performance Improvements:** 130% accuracy improvement over the base model through specialized model optimization
- **Cost Savings:** Up to 90% reduction in operational costs through efficient architecture

---

## 📞 Contact Information

**Email:** altyurin3@gmail.com  
**LinkedIn:** [https://www.linkedin.com/in/alexey-tyurin-36893287/](https://www.linkedin.com/in/alexey-tyurin-36893287/)  
**GitHub:** [https://github.com/alexey-tyurin](https://github.com/alexey-tyurin)

*Available for consulting, collaboration, and full-time opportunities in GenAI, AI agent development, and production AI systems.*