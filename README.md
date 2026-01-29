<div align="center">


</div>

<div align="center">
  <h2>⚡ Building the Future with AI & Data</h2>
  <p><i>From Neural Networks to Production Systems</i></p>
</div>

<br>

<div align="center">

<a href="https://www.linkedin.com/in/japjot-singhb/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:bhatiajapjotjpr@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://japjot.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
</a>
<a href="https://github.com/JXPJXT">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

---

## 👋 About Me

I'm an AI/ML engineer passionate about building intelligent systems that solve real-world problems. Currently working with **Large Language Models**, **Agentic AI architectures**, and **cloud-scale data pipelines**. I love turning complex challenges into production-ready solutions.

```python
class JapjotSingh:
    def __init__(self):
        self.name = "Japjot Singh Bhatia"
        self.role = "AI/ML Engineer"
        self.location = "India 🇮🇳"
        self.education = "B.Tech CSE @ LPU (CGPA: 8.14)"
        
    def current_focus(self):
        return {
            "learning": "Agentic AI & LLM fine-tuning",
            "building": "Production ML systems",
            "exploring": "Multi-agent architectures"
        }
    
    def tech_stack(self):
        return ["Python", "Java", "SQL", "TensorFlow", "FastAPI", 
                "Docker", "Kubernetes", "AWS", "Azure"]
```

---

## 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**AI/ML**  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=000)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Web & APIs**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Cloud & DevOps**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

**Databases & Tools**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 🤖 [AI-Based Smart Allocation Engine](https://github.com/JXPJXT) 
**Nominated for SIH 2024 Nationals** • *React, TypeScript, Python, Sentence-BERT, ILP*

Built an AI-driven system that matches interns to projects based on skills using NLP and optimization algorithms. First software team from my university nominated to Smart India Hackathon Nationals.

- **NLP Engine**: Used Sentence-BERT for semantic similarity scoring between skills and job requirements
- **Fair Allocation**: Implemented Integer Linear Programming to ensure balanced, transparent assignments
- **Full-Stack**: React + TypeScript frontend with Python FastAPI backend and Supabase database
- **CI/CD**: Automated deployment pipeline with GitHub Actions

<details>
<summary>🔍 Technical Deep Dive</summary>

```python
# Core allocation algorithm
def allocate_interns(interns, projects):
    # Step 1: Generate embeddings for skills
    skill_embeddings = model.encode(intern_skills)
    project_embeddings = model.encode(project_requirements)
    
    # Step 2: Calculate similarity matrix
    similarity = cosine_similarity(skill_embeddings, project_embeddings)
    
    # Step 3: Optimize with ILP
    allocation = solve_ilp(similarity_matrix, constraints)
    
    return allocation
```

**Key Features:**
- 92% accuracy in skill-role matching
- Real-time allocation updates
- Role-based access control
- Automated workflow pipelines

</details>

---

### 📰 [Fake News Detection System](https://github.com/JXPJXT)
**Deep Learning Classifier** • *Python, BERT, LSTM, FastAPI, AWS*

Hybrid deep learning model combining LSTM and BERT for detecting fake news articles with **95.96% accuracy**.

- **Dataset**: Trained on 72,000+ articles from WELFake dataset
- **Model**: Hybrid LSTM + BERT architecture for sequential + contextual understanding
- **Pipeline**: Databricks for data processing, Airflow for ETL orchestration
- **Deployment**: Production API on AWS EC2 with Kubernetes auto-scaling

<details>
<summary>🔍 Architecture Details</summary>

**Model Architecture:**
```
Input Text → BERT Embeddings → LSTM Layer → Dense Layers → Binary Classification
                    ↓
            Attention Mechanism
```

**Performance Metrics:**
- Accuracy: 95.96%
- Dataset: 72,000+ articles
- Latency: <100ms per request

**Tech Stack:**
- Training: TensorFlow + HuggingFace Transformers
- Data Processing: Databricks + Apache Spark
- API: FastAPI with async endpoints
- Deployment: Docker + Kubernetes on AWS EC2

</details>

---

### 📈 [AI-Powered Stock Analysis Agent](https://github.com/JXPJXT)
**Multi-Agent System** • *Python, Google ADK, LLMs, APIs*

Autonomous agent system that combines real-time market data with LLM-driven analysis for stock recommendations.

- **Agent Architecture**: Multi-agent system with specialized capabilities
- **LLM Integration**: Google's ADK for tool orchestration and reasoning
- **Data Sources**: Alpha Vantage API for real-time prices, news sentiment analysis
- **Features**: Ticker discovery, trend analysis, confidence scoring

<details>
<summary>🔍 Agent Workflow</summary>

```python
# Agent orchestration
async def analyze_stock(ticker: str):
    # Fetch market data
    market_data = await market_agent.get_price_data(ticker)
    
    # Analyze sentiment from news
    sentiment = await sentiment_agent.analyze_news(ticker)
    
    # LLM-powered insights
    analysis = await llm_agent.generate_insights(
        market_data, sentiment
    )
    
    return {
        "ticker": ticker,
        "recommendation": analysis.recommendation,
        "confidence": analysis.confidence_score,
        "reasoning": analysis.explanation
    }
```

**System Features:**
- 3 autonomous agents with specialized capabilities
- LLM-powered reasoning with tool orchestration
- Error-aware data handling
- Dockerized deployment with rate limiting

</details>

---

## 💼 Experience

### 💠 Data Intern @ Futurense Technologies
*Jun 2025 - Aug 2025*

- **Data Engineering**: Built Python ETL pipelines to clean and standardize 100K+ marketing records for funnel analysis
- **Analytics Dashboard**: Created multi-page Power BI dashboard revealing 35% drop-off in conversion funnel
- **Strategic Impact**: Recommended shift from CPL to CPE-based budgeting, improving lead quality by 40%

**Tools Used:** Python (Pandas, NumPy), Power BI, SQL

---

## 🏆 Certifications & Achievements

<table align="center">
<tr>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/oracle-logo.png" width="60"/><br>
<b>OCI AI Foundations</b><br>
<sub>Oracle • Oct 2025</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/oracle-logo.png" width="60"/><br>
<b>OCI Data Science</b><br>
<sub>Oracle • Oct 2025</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/azure-1.png" width="60"/><br>
<b>Azure Data Fundamentals</b><br>
<sub>Microsoft • Nov 2024</sub>
</td>
<td align="center" width="25%">
<img src="https://img.icons8.com/color/96/000000/trophy.png" width="60"/><br>
<b>SIH 2025 Nominee by University</b><br>
<sub>National Level</sub>
</td>
</tr>
</table>

**Competitive Programming:**
- 💻 **500+ Problems** solved on LeetCode (DSA focused)
- ⭐ **5-Star Gold** ranking on HackerRank (Java, Python, SQL)
- 🎓 **8.14 CGPA** in B.Tech Computer Science Engineering

---

## 📊 GitHub Stats

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=JXPJXT&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7f7&icon_color=00f7f7&text_color=c9d1d9" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=JXPJXT&theme=tokyonight&hide_border=true&background=0d1117&stroke=00f7f7&ring=00f7f7&fire=00f7f7&currStreakLabel=00f7f7" />
</div>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JXPJXT&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7f7&text_color=c9d1d9" />
</div>

---

<div align="center">

## 🤝 Let's Connect

<a href="https://www.linkedin.com/in/japjot-singhb/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:bhatiajapjotjpr@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://japjot.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
</a>
<a href="https://github.com/JXPJXT">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br><br>

```ascii
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│     "Building intelligent systems that make a difference"       │
│                                                                 │
│                      - Japjot Singh Bhatia                      │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

<img src="https://komarev.com/ghpvc/?username=JXPJXT&color=00f7f7&style=flat-square&label=Profile+Views" alt="Profile Views" />

<br>

**⚡ Open to collaborations on AI/ML projects and research opportunities**

---

<sub>⭐ If you find my work interesting, drop a star on my repositories!</sub>

</div>
