![header](assets/header.png)

<h1 align="center"> வணக்கம் (Vanakkam), I am Siva Prakash </h1>
<p align="center">
 <img src="https://readme-typing-svg.demolab.com?lines=Machine%20Learning;Data%20Engineering;Backend%20Development;Always%20learning&width=450&height=75&font=Ubuntu+Mono&weight=1000&pause=75&color=3ce3ce&center=true&size=19">
</p>
<h3 align="center">I'm an Data Enthusiast from India ❤️</h3><br>
<p align="center">I am a self-motivated professional holding a Master of Computer Applications. With a strong focus on developing data-driven applications, I have cultivated expertise in software engineering. Currently, my work spans projects encompassing both backend development and data engineering domains. I am eager to apply my skills and experience to deliver impactful contributions within a dynamic and challenging work environment.</p><br>

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

- 🔭 I’m currently working on **Data Engineering**
- 🌱 I’m currently learning **Cloud Computing**
- 👯 I’m looking to collaborate on **Machine Learning**
- 😄 Pronouns : **Siva/Prakash**
- ⚡ Fun fact : **I listen to music atleast 30 mins/day**

## ⚡ Recent Activity :

<!--START_SECTION:activity-->

1. 🎉 Merged PR [#1](https://github.com/Prakashdeveloper03/Freaks-Sheet/pull/1) in [Prakashdeveloper03/Freaks-Sheet](https://github.com/Prakashdeveloper03/Freaks-Sheet)
2. 💪 Opened PR [#1](https://github.com/Prakashdeveloper03/Freaks-Sheet/pull/1) in [Prakashdeveloper03/Freaks-Sheet](https://github.com/Prakashdeveloper03/Freaks-Sheet)
3. 🔒 Closed issue [#1](https://github.com/Prakashdeveloper03/Practice-Pandas/issues/1) in [Prakashdeveloper03/Practice-Pandas](https://github.com/Prakashdeveloper03/Practice-Pandas)
4. ❗ Opened issue [#1](https://github.com/Prakashdeveloper03/Practice-Pandas/issues/1) in [Prakashdeveloper03/Practice-Pandas](https://github.com/Prakashdeveloper03/Practice-Pandas)
5. 🎉 Merged PR [#3](https://github.com/Prakashdeveloper03/Neetcode-150/pull/3) in [Prakashdeveloper03/Neetcode-150](https://github.com/Prakashdeveloper03/Neetcode-150)
<!--END_SECTION:activity-->

<h3>A little more about me...</h3>

```py
from fastapi import FastAPI, HTTPException, status
from datetime import datetime

app = FastAPI()

@app.get("/name", status_code=status.HTTP_200_OK)
async def get_name():
    return {"Name": "Siva Prakash"}

@app.get("/age", status_code=status.HTTP_200_OK)
async def get_age():
    birth_date = datetime(2001, 3, 10)
    current_year = datetime.now().year
    age = current_year - birth_date.year
    if datetime.now() < datetime(current_year, 3, 10):
        age -= 1
    return {"Age": age}

@app.get("/description", status_code=status.HTTP_200_OK)
async def get_description():
    return {"Description": ["Passionate", "Optimistic", "Energetic", "Team Player"]}

@app.get("/education", status_code=status.HTTP_200_OK)
async def get_education():
    education = [
        {"College": "College of Engineering, Guindy", "Year": [2022, 2023, 2024]},
        {"College": "Apollo arts and science college", "Year": [2019, 2020, 2021, 2022]},
        {"School": "Seventh Day Adventist Matriculation Higher Secondary School", "Year": [2017, 2018, 2019]}
    ]
    return education

if __name__ == "__main__":
    import uvicorn
    uvicorn.run(app, host="0.0.0.0", port=5000)
```

<h2 align="left">📱 Connect with Me :</h2>
<p>
  <a href="https://www.linkedin.com/in/prakashdeveloper"><img src="https://img.shields.io/badge/Linkedin-0e76a8?logo=linkedin&logoColor=white"/></a>
  <a href="https://www.hackerrank.com/prakashdeveloper"><img src="https://img.shields.io/badge/Hackerrank-25A162?logo=hackerrank&logoColor=white"/></a>
  <a href="https://leetcode.com/Prakashdeveloper/"><img src="https://img.shields.io/badge/LeetCode-FFA116?logo=LeetCode&logoColor=white"/></a>
  <a href="https://auth.geeksforgeeks.org/user/prakashdeveloper03/practice"><img src="https://img.shields.io/badge/GeeksforGeeks-298D46?logo=geeksforgeeks&logoColor=white"/></a>
  <a href="https://prakashdeveloper03.github.io/"><img src="https://img.shields.io/badge/Website-202020?logo=About.me&logoColor=white"/></a>
</p>

<h2 align="left">🚀 Languages and Tools :</h2>

### ⚡ Programming languages

<p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
    <img alt="Java" src="https://custom-icon-badges.demolab.com/badge/Java-E34F26?logo=java&logoColor=white">
    <img alt="C++" src="https://img.shields.io/badge/C++-9C033A?logo=c%2B%2B&logoColor=white">
</p>

### 💥 Backend Development

<p>
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=Spring-Boot&logoColor=white">
    <img alt="Django" src="https://img.shields.io/badge/Django-092E20.svg?logo=Django&logoColor=white">
    <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-109989?logo=fastapi&logoColor=white">
</p>

### 🧩 Machine Learning

<p>
    <img alt="NumPy" src="https://img.shields.io/badge/Numpy-777BB4?logo=numpy&logoColor=white">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-2C2D72?logo=pandas&logoColor=white">
    <img alt="ScikitLearn" src="https://img.shields.io/badge/ScikitLearn-0078D7?logo=scikit-learn&logoColor=white">
    <img alt="Keras" src="https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white">
    <img alt="Pytorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=PyTorch&logoColor=white">
    <img alt="Tensorflow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white">
    <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
</p>

### 🗄️ Databases & Cloud

<p>
    <img alt="PostgreSQL" src ="https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white">
    <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white">
    <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?logo=Redis&logoColor=white">
    <img alt="Cassandra" src="https://img.shields.io/badge/Cassandra-1287B1?logo=Apache-Cassandra&logoColor=white">
    <img alt="TimescaleDB" src="https://img.shields.io/badge/TimescaleDB-EE4C2C?logo=Timescale&logoColor=white">
    <img alt="Neo4J" src="https://img.shields.io/badge/Neo4j-4581C3?logo=Neo4j&logoColor=white">
    <img alt="Elasticsearch" src="https://img.shields.io/badge/Elasticsearch-005571?logo=Elasticsearch&logoColor=white">
    <img alt="Google Cloud" src="https://img.shields.io/badge/Google%20Cloud%20Platform-4285F4?logo=Google-Cloud&logoColor=white">
</p>

### ❄️ Data Engineering

<p>
    <img alt="Apache Spark" src="https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=Apache-Spark&logoColor=white">
    <img alt="Apache Hadoop" src="https://img.shields.io/badge/Apache%20Hadoop-225593?logo=Apache-Hadoop&logoColor=white">
    <img alt="Apache Airflow" src="https://img.shields.io/badge/Apache%20Airflow-017CEE?logo=Apache-Airflow&logoColor=white">
    <img alt="Apache Flink" src="https://img.shields.io/badge/Apache%20Flink-E6526F?logo=Apache-Flink&logoColor=white">
    <img alt="Apache Kafka" src="https://img.shields.io/badge/Apache%20Kafka-231F20?logo=Apache-Kafka&logoColor=white">
</p>

### ⛽ Devops

<p>
    <img alt="Git" src="https://img.shields.io/badge/Git-F05033?logo=git&logoColor=white">
    <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?logo=Jenkins&logoColor=white">
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2CA5E0?logo=docker&logoColor=white">
    <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?logo=Kubernetes&logoColor=white">
</p>

### 💻 Workspace and Tools

<p>
    <img alt="Ubundu" src="https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white">
    <img alt="Gradle" src="https://img.shields.io/badge/Gradle-575757?logo=Gradle&logoColor=white">
    <img alt="CMake" src="https://img.shields.io/badge/CMake-064F8C.svg?logo=CMake&logoColor=white">
    <img alt="Poetry" src="https://img.shields.io/badge/Poetry-60A5FA.svg?logo=Poetry&logoColor=white">
    <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?logo=Postman&logoColor=white">
    <img alt="Intellij" src="https://img.shields.io/badge/IntelliJ_IDEA-575757?logo=IntelliJ-IDEA&logoColor=white">
    <img alt="Neovim" src="https://img.shields.io/badge/Neovim-57A143?logo=Neovim&logoColor=white">
</p>

<h2>📈 Statistics and Languages :</h2>
<details open>
  <summary>GitHub Profile Stats</summary>
  <br/>
    <img width="46%" alt="stats" src="https://github-readme-stats.vercel.app/api?username=Prakashdeveloper03&theme=radical&show_icons=true&hide_border=true" />
    <img width="49%" alt="Prakashdeveloper03's streak" src="https://streak-stats.demolab.com/?user=Prakashdeveloper03&theme=radical&hide_border=true&date_format=j%20M%5B%20Y%5D"/>
  <br/>
</details>

<details open>
  <summary>GitHub Languages Stats</summary>
  <br/>
  <p align="center">
    <img alt="languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prakashdeveloper03&hide=jupyter%20notebook,elixir,sql,vue,ruby,css,c%23,go,html,xml,sass,ejs,r,scss,typescript,javascript,tex,markdown&langs_count=4&layout=compact&theme=radical&show_icons=true&hide_border=true"/>
  </p>
  <br/>
</details>

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
