# Hello, I'm Chamidu! 👋

[![Profile Views](https://komarev.com/ghpvc/?username=Chamidu0423&color=blueviolet)](https://github.com/Chamidu0423)
[![GitHub Followers](https://img.shields.io/github/followers/Chamidu0423?style=social)](https://github.com/Chamidu0423)

## 📊 GitHub Stats

<div align="center">
  
  ![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=Chamidu0423&show_icons=true&theme=radical)
  
  ![Streak Stats](https://github-readme-streak-stats.herokuapp.com/?user=Chamidu0423&theme=radical)
  
  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Chamidu0423&layout=compact&theme=radical)

</div>

## 🛠 Tech Stack

```javascript
const myTechStack = {
  languages: ["JavaScript", "Python", "HTML/CSS", "Java"],
  frameworks: ["React", "Node.js", "Express"],
  databases: ["MongoDB", "MySQL"],
  tools: ["Git", "VS Code", "Docker"],
  currentlyLearning: ["TypeScript", "AWS"]
};
🌟 Featured Projects
<div id="featured-repos" align="center"> <!-- Projects will load here automatically --> </div>
📫 Connect With Me
Gmail
LinkedIn
Twitter

<script> // Fetch and display pinned repositories async function loadRepos() { try { const response = await fetch('https://api.github.com/users/Chamidu0423/repos?sort=updated&per_page=6'); const repos = await response.json(); const reposContainer = document.getElementById('featured-repos'); let html = ''; repos.forEach(repo => { html += ` <a href="${repo.html_url}"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=Chamidu0423&repo=${repo.name}&theme=radical" alt="${repo.name}" /> </a> `; }); reposContainer.innerHTML = html; } catch (error) { console.error('Error loading repositories:', error); } } // Call the function when page loads loadRepos(); </script>
