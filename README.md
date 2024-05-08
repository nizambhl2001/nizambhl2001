


## Hi! 👋🏻 I am MD. Nizam Uddin Tuhin ! 
![](https://visitor-badge.laobi.icu/badge?page_id=nizambhl2001.CharalambosIoannou)
[![Github](https://img.shields.io/github/followers/nizambhl2001?label=Follow&style=social)](https://github.com/CharalambosIoannou)

## 🙋🏻‍♂️~~ .NET & C# Programmer,


|      Project :octocat:   |     Issues :bug:   | Open PRs :bell:  | Closed PRs :fire:  | 


**MD. Nizam Uddin Tuhin ** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
   
- 🔭 I’m currently working on  <a href="https://www.isdb-bisew.org">**IsDB-BISEW Scholarship Program**</a>


- 🌱 I’m currently learning **asp.net using C Sharp** 


- 💬 Ask me about **react, vue and Angular**


- 📫 How to reach Contact me **nizamddin2001@gmail.com**




## ✉️ Find me on:


<p align="center">
 <a href="https://charalambosioannou.github.io/" target="_blank" rel="noopener noreferrer"> <img src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" alt="Python" height="40" style="vertical-align:top; margin:4px"> </a>
 <a href="https://linkedin.com/in/charalambosioannou" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" alt="Python" height="40" style="vertical-align:top; margin:4px"></a>
 <a href="mailto:cioannou1997@gmail.com"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" alt="Python" height="40" style="vertical-align:top; margin:4px"></a>
</p>

<br />

## 🧰 Languages and Tools:
<p align="center">
 <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" style="vertical-align:top; margin:4px" height="40"/>
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" style="vertical-align:top; margin:4px" height="40"/>
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" alt="Javascript" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" alt="VS Code" height="40" style="vertical-align:top; margin:4px">
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
 <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> 
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
</p>

# Blog posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

name: Latest blog post workflow
on:
  schedule:
    # Runs every hour
    - cron: '0 * * * *'
  workflow_dispatch:

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          feed_list: "https://dev.to/feed/charalambosioannou"











