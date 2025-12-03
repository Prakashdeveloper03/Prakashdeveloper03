![header](assets/header.png)

<h1 align="center"> வணக்கம் (Vanakkam), I am Siva Prakash </h1>
<p align="center">
 <img src="https://readme-typing-svg.demolab.com?lines=Machine%20Learning;Backend%20Development;Data%20Engineering;Always%20learning&width=450&height=75&font=Ubuntu+Mono&weight=1200&pause=75&color=3ce3ce&center=true&size=21">
</p>
<h3 align="center">I'm a Software Engineer from India ❤️</h3><br> <p align="center">I am a self-motivated professional holding a Master of Computer Applications. With a strong foundation in software engineering, I specialize in building scalable and efficient applications. My experience spans data engineering, backend development, machine learning, and working with various technologies to create robust software solutions. I am eager to apply my skills and expertise to solve complex challenges in a dynamic and fast-paced work environment.</p><br>

<p align="center">
  <img src="https://img.shields.io/badge/PRs-Welcome-white?style=flat&amp;logo=github&amp;color=3ce3cf" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/Name-Siva_Prakash-white?color=3ce3ce" alt="name">
  <img src="https://img.shields.io/badge/Age-23-3ce3ce" alt="age">
  <img src="https://img.shields.io/badge/Focus-Big_Data-3ce3ce" alt="focus">
  <img src="https://img.shields.io/badge/Living-Chennai-3ce3ce" alt="living">
  <img src="https://komarev.com/ghpvc/?username=Prakashdeveloper03&amp;labelColor=black&amp;label=Profile+Views&amp;color=3ce3ce" alt="Visitors count">
  <img src="https://img.shields.io/github/last-commit/Prakashdeveloper03/Prakashdeveloper03?logo=markdown&amp;label=Last+Update&amp;color=3ce3ce&amp" alt="Last Commit">
</p>

<h2>😉 About Me : </h2>

- 🔭 I’m currently working on **Data Engineering** & **MLOps**
- 🌱 I’m currently learning **Cloud Native Technologies** & **LLMOps**
- 👯 I’m looking to collaborate on **Open Source Data Tools**
- 💬 Ask me about **Python, Go, Distributed Systems, and ML**
- 😄 Pronouns : **He/Him**
- ⚡ Fun fact : **I listen to music at least 30 mins/day to fuel my coding sessions!**

## ⚡ Recent Activity :

<!--START_SECTION:activity-->

1. 🎉 Merged PR [#1](https://github.com/Prakashdeveloper03/Resume-Cli/pull/1) in [Prakashdeveloper03/Resume-Cli](https://github.com/Prakashdeveloper03/Resume-Cli)
2. 💪 Opened PR [#1](https://github.com/Prakashdeveloper03/Resume-Cli/pull/1) in [Prakashdeveloper03/Resume-Cli](https://github.com/Prakashdeveloper03/Resume-Cli)
3. 🎉 Merged PR [#1](https://github.com/Prakashdeveloper03/Freaks-Sheet/pull/1) in [Prakashdeveloper03/Freaks-Sheet](https://github.com/Prakashdeveloper03/Freaks-Sheet)
4. 💪 Opened PR [#1](https://github.com/Prakashdeveloper03/Freaks-Sheet/pull/1) in [Prakashdeveloper03/Freaks-Sheet](https://github.com/Prakashdeveloper03/Freaks-Sheet)
5. 🎉 Merged PR [#3](https://github.com/Prakashdeveloper03/Neetcode-150/pull/3) in [Prakashdeveloper03/Neetcode-150](https://github.com/Prakashdeveloper03/Neetcode-150)
<!--END_SECTION:activity-->

<h3>A little more about me...</h3>

```python
from fastapi import FastAPI, status
from pydantic import BaseModel
from typing import List, Dict

app = FastAPI(title="Siva Prakash's Portfolio API")

class Profile(BaseModel):
    name: str
    role: str
    location: str
    experience_years: int

@app.get("/me", response_model=Profile, status_code=status.HTTP_200_OK)
async def get_my_profile():
    """Returns my basic profile information."""
    return Profile(
        name="Siva Prakash",
        role="Software Engineer & Data Engineer",
        location="Chennai, India",
        experience_years=2
    )

@app.get("/tech-stack", status_code=status.HTTP_200_OK)
async def get_tech_stack() -> Dict[str, List[str]]:
    """Returns my categorized technical skills."""
    return {
        "languages": ["Python", "Go", "Bash"],
        "big_data": ["Spark", "Kafka", "Airflow", "Iceberg"],
        "ml_ops": ["MLflow", "Kubeflow", "DVC"],
        "cloud": ["AWS", "GCP", "Kubernetes"]
    }

@app.get("/contact", status_code=status.HTTP_200_OK)
async def get_contact_info():
    """Feel free to reach out!"""
    return {
        "linkedin": "https://linkedin.com/in/prakashdeveloper",
        "github": "https://github.com/Prakashdeveloper03"
    }
```

<h2 align="left">📱 Connect with Me :</h2>
<p>
  <a href="https://www.hackerrank.com/prakashdeveloper"><img src="https://img.shields.io/badge/Hackerrank-25A162?logo=hackerrank&logoColor=white"/></a>
  <a href="https://leetcode.com/Prakashdeveloper/"><img src="https://img.shields.io/badge/LeetCode-FFA116?logo=LeetCode&logoColor=white"/></a>
  <a href="https://auth.geeksforgeeks.org/user/prakashdeveloper03/practice"><img src="https://img.shields.io/badge/GeeksforGeeks-298D46?logo=geeksforgeeks&logoColor=white"/></a>
  <a href="https://prakashdeveloper03.github.io/"><img src="https://img.shields.io/badge/Website-202020?logo=About.me&logoColor=white"/></a>
</p>

<h2 align="left">🚀 Skills & Technologies :</h2>

### 🗣️ Languages

<p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
    <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white">
    <img alt="Java" src="https://custom-icon-badges.demolab.com/badge/Java-E34F26?logo=java&logoColor=white">
    <img alt="Bash" src="https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white">
</p>

### 📚 Data Science & ML

<p>
    <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white">
    <img alt="Scikit-Learn" src="https://img.shields.io/badge/Scikit_Learn-F7931E?logo=scikit-learn&logoColor=white">
    <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white">
    <img alt="Optuna" src="https://img.shields.io/badge/Optuna-202020?logo=optuna&logoColor=white">
    <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
    <img alt="Polars" src="https://img.shields.io/badge/Polars-CD792C?logo=polars&logoColor=white">
    <img alt="Dask" src="https://img.shields.io/badge/Dask-FD7900?logo=dask&logoColor=white">
</p>

### 🛠️ DevOps & Tools

<p>
    <img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-202020?logo=github&logoColor=white">
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
    <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white">
    <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white">
    <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black">
    <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white">
    <img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white">
    <img alt="Loki" src="https://img.shields.io/badge/Loki-F47F23?logo=grafana&logoColor=white">
    <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-202020?logo=opentelemetry&logoColor=white">
    <img alt="Jaeger" src="https://img.shields.io/badge/Jaeger-60D0E4?logo=jaeger&logoColor=white">
    <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white">
    <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white">
    <img alt="Istio" src="https://img.shields.io/badge/Istio-466BB0?logo=istio&logoColor=white">
    <img alt="ArgoCD" src="https://img.shields.io/badge/ArgoCD-EF7B4D?logo=argo&logoColor=white">
</p>

### 🔙 Backend & Frameworks

<p>
    <img alt="Gin" src="https://img.shields.io/badge/Gin-00ADD8?logo=go&logoColor=white">
    <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
    <img alt="Strawberry" src="https://img.shields.io/badge/Strawberry-FF1493?logo=graphql&logoColor=white">
    <img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white">
    <img alt="GORM" src="https://img.shields.io/badge/GORM-00ADD8?logo=go&logoColor=white">
    <img alt="JWT" src="https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white">
    <img alt="OAuth" src="https://img.shields.io/badge/OAuth-EB5424?logo=auth0&logoColor=white">
</p>

### 🗄️ Databases

<p>
    <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white">
    <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
    <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white">
        <img alt="TimescaleDB" src="https://img.shields.io/badge/TimescaleDB-EE4C2C?logo=Timescale&logoColor=white">
</p>

### ⛈️ Big Data

<p>
    <img alt="Airflow" src="https://img.shields.io/badge/Airflow-017CEE?logo=apache-airflow&logoColor=white">
    <img alt="BigQuery" src="https://img.shields.io/badge/BigQuery-669DF6?logo=google-bigquery&logoColor=white">
    <img alt="Spark" src="https://img.shields.io/badge/Spark-E25A1C?logo=apache-spark&logoColor=white">
    <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?logo=apache-kafka&logoColor=white">
</p>

### 🌩️ Cloud & AI Operations

<p>
    <img alt="GCP" src="https://img.shields.io/badge/Google_Cloud_Platform-4285F4?logo=google-cloud&logoColor=white">
    <img alt="DVC" src="https://img.shields.io/badge/DVC-945DD6?logo=dvc&logoColor=white">
    <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white">
    <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white">
    <img alt="Milvus" src="https://img.shields.io/badge/Milvus-00A1EA?logo=milvus&logoColor=white">
    <img alt="Ollama" src="https://img.shields.io/badge/Ollama-202020?logo=ollama&logoColor=white">
    <img alt="HuggingFace" src="https://img.shields.io/badge/HuggingFace-FFD21E?logo=huggingface&logoColor=black">
    <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white">
    <img alt="Google Gemini" src="https://img.shields.io/badge/Google%20Gemini-8E75B2?logo=google-gemini&logoColor=white">
    <img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?logo=anthropic&logoColor=white">
</p>

<h2>📈 Statistics and Languages :</h2>
<details open>
  <summary>GitHub Trophy Stats</summary>
  <br/>
  <p align="center">
    <img width="98%" alt="trophy stats" src="https://github-profile-trophy.vercel.app/?username=Prakashdeveloper03&theme=radical&no-frame=true&title=Issues,Stars,Commit,Experience,Repositories,PullRequest,MultiLanguage,Followers" />
  </p>
  <br/>
</details>

<details open>
  <summary>GitHub Contributions Graph</summary>
  <br/>
  <p align="center">
    <img width="98%" alt="contributions graph" src="https://github-readme-activity-graph.vercel.app/graph?username=Prakashdeveloper03&area=true&layout=compact&theme=redical&hide_border=true&radius=10" />
  </p>
</details>
