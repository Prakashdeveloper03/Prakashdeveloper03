![header](assets/header.png)

<h1 align="center"> வணக்கம் (Vanakkam), I am Siva Prakash </h1>
<p align="center">
 <img src="https://readme-typing-svg.demolab.com?lines=Machine%20Learning;Backend%20Development;Always%20learning&width=450&height=75&font=Ubuntu+Mono&weight=1000&pause=75&color=3ce3ce&center=true&size=19">
</p>
<h3 align="center">I'm an Tech Enthusiast from India ❤️</h3><br>
<p align="center">I am a self motivated student currently pursuing a Master of Computer Applications at the College of Engineering, Guindy. Discovered my passion for crafting data-driven applications, I naturally gravitated towards the dynamic realm of software engineering. Presently, I am engaged in self-paced mini-projects focusing on both machine learning and backend development, honing my skills and expanding my knowledge in these fields.</p><br>

<p align="center">
  <img src="https://img.shields.io/badge/PRs-Welcome-white?style=flat&amp;logo=github&amp;color=3ce3cf" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/Name-Siva_Prakash-white?color=3ce3ce" alt="name">
  <img src="https://img.shields.io/badge/Age-22-3ce3ce" alt="age">
  <img src="https://img.shields.io/badge/Focus-Machine_Learning-3ce3ce" alt="focus">
  <img src="https://img.shields.io/badge/Living-Chennai-3ce3ce" alt="living">
  <img src="https://komarev.com/ghpvc/?username=Prakashdeveloper03&amp;labelColor=black&amp;label=Profile+Views&amp;color=3ce3ce" alt="Visitors count">
  <img src="https://img.shields.io/github/last-commit/Prakashdeveloper03/Prakashdeveloper03?logo=markdown&amp;label=Last+Update&amp;color=3ce3ce&amp" alt="Last Commit">
</p>

<h2>😉 About Me : </h2>

- 🔭 I’m currently working on **Deep Learning**
- 🌱 I’m currently learning **Computer Vision**
- 👯 I’m looking to collaborate on **Machine Learning**
- 😄 Pronouns : **Siva/Prakash**
- ⚡ Fun fact : **I listen to music atleast 30 mins/day**

## ⚡ Recent Activity :

<!--START_SECTION:activity-->

1. ❗ Opened issue [#5](https://github.com/Prakashdeveloper03/Prakashdeveloper03.github.io/issues/5) in [Prakashdeveloper03/Prakashdeveloper03.github.io](https://github.com/Prakashdeveloper03/Prakashdeveloper03.github.io)
2. 🎉 Merged PR [#4](https://github.com/Prakashdeveloper03/Prakashdeveloper03.github.io/pull/4) in [Prakashdeveloper03/Prakashdeveloper03.github.io](https://github.com/Prakashdeveloper03/Prakashdeveloper03.github.io)
3. 💪 Opened PR [#4](https://github.com/Prakashdeveloper03/Prakashdeveloper03.github.io/pull/4) in [Prakashdeveloper03/Prakashdeveloper03.github.io](https://github.com/Prakashdeveloper03/Prakashdeveloper03.github.io)
4. 🎉 Merged PR [#5](https://github.com/Prakashdeveloper03/CareerBot/pull/5) in [Prakashdeveloper03/CareerBot](https://github.com/Prakashdeveloper03/CareerBot)
5. 💪 Opened PR [#5](https://github.com/Prakashdeveloper03/CareerBot/pull/5) in [Prakashdeveloper03/CareerBot](https://github.com/Prakashdeveloper03/CareerBot)
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
  <a href="mailto:thalapathysp25@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/prakashdeveloper"><img src="https://img.shields.io/badge/Linkedin-0e76a8?logo=linkedin&logoColor=white"/></a>
  <a href="https://www.hackerrank.com/prakashdeveloper"><img src="https://img.shields.io/badge/Hackerrank-25A162?logo=hackerrank&logoColor=white"/></a>
  <a href="https://leetcode.com/Prakashdeveloper03/"><img src="https://img.shields.io/badge/LeetCode-FFA116?logo=LeetCode&logoColor=white"/></a>
  <a href="https://auth.geeksforgeeks.org/user/prakashdeveloper03/practice"><img src="https://img.shields.io/badge/GeeksforGeeks-298D46?logo=geeksforgeeks&logoColor=white"/></a>
  <a href="https://prakashdeveloper03.github.io/"><img src="https://img.shields.io/badge/Website-202020?logo=About.me&logoColor=white"/></a>
</p>

<h2 align="left">🚀 Languages and Tools :</h2>

### ⚡ Programming languages

<p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
    <img alt="C++" src="https://img.shields.io/badge/C++-9C033A?logo=c%2B%2B&logoColor=white">
    <img alt="Typescript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=white">
</p>

### 🕸️ Frontend Development

<p>
    <img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white">
    <img alt="Sass" src="https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white">
    <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?logo=bootstrap&logoColor=white">
    <img alt="Tailwindcss" src="https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white">
    <img alt="React" src="https://img.shields.io/badge/React-20232A.svg?logo=react&logoColor=61DAFB">
    <img alt="Markdown" src="https://img.shields.io/badge/Markdown-202020?logo=markdown&logoColor=white">
</p>

### 💥 Backend Development

<p>
    <img alt="Django" src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white">
    <img alt="Flask" src="https://img.shields.io/badge/Flask-202020?logo=Flask&logoColor=white">
    <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-109989?logo=fastapi&logoColor=white">
    <img alt="Express.js" src="https://img.shields.io/badge/Express_JS-202020?logo=express&logoColor=white">
    <img alt="Node.js" src="https://img.shields.io/badge/Node_JS-339933?logo=nodedotjs&logoColor=white">
</p>

### 🧩 Data Science and Machine Learning

<p>
    <img alt="NumPy" src="https://img.shields.io/badge/Numpy-777BB4?logo=numpy&logoColor=white">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-2C2D72?logo=pandas&logoColor=white">
    <img alt="ScikitLearn" src="https://img.shields.io/badge/ScikitLearn-0078D7?logo=scikit-learn&logoColor=white">
    <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8.svg?logo=OpenCV&logoColor=white">
    <img alt="Keras" src="https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white">
    <img alt="Tensorflow" src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white">
    <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=PyTorch&logoColor=white">
    <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
</p>

### 🗄️ Databases and Cloud

<p>
    <img alt="PostgreSQL" src ="https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white">
    <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white">
    <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
    <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white">
    <img alt="Google Cloud" src="https://img.shields.io/badge/Google%20Cloud-4285F4?logo=Google-Cloud&logoColor=white">
</p>

### 💻 Workspace and Tools

<p>
    <img alt="Windows" src="https://img.shields.io/badge/Windows-%230079d5?logo=windows%2011&logoColor=white">
    <img alt="Ubundu" src="https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white">
    <img alt="Fedora" src="https://img.shields.io/badge/Fedora-51A2DA.svg?logo=Fedora&logoColor=white">
    <img alt="Git" src="https://img.shields.io/badge/Git-F05033?logo=git&logoColor=white">
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2CA5E0?logo=docker&logoColor=white">
    <img alt="Sublime text" src="https://img.shields.io/badge/Sublime_Text-%23575757?logo=sublime-text&logoColor=important">
    <img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7?logo=visual-studio-code&logoColor=white">
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
    <img width="50%" alt="languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prakashdeveloper03&hide=jupyter%20notebook,sql,java,astro,ruby,go,mdx,vue,c,css,scala,c%23,html,elixir,xml,sass,Procfile,shell,ejs,r,scss,sass,tex,markdown&langs_count=4&layout=compact&theme=radical&show_icons=true&hide_border=true"/>
  </p>
  <br/>
</details>

<details open>
  <summary>GitHub Trophy Stats</summary>
  <br/>
  <p align="center">
    <img width="98%" alt="trophy stats" src="https://github-profile-trophy.vercel.app/?username=Prakashdeveloper03&theme=radical&no-frame=true&title=Issues,Stars,Commit,Repositories,PullRequest,MultiLanguage,Followers,Reviews" />
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
