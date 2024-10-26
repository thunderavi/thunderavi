# 👋 Hi, I’m Avi Ranjan Prasad

🎓 **Information Science and Engineering Graduate**  
💻 **Full Stack Developer & Machine Learning Enthusiast**  
🌱 Currently exploring advanced machine learning and API integrations

---

![LinkedIn](https://img.shields.io/badge/LinkedIn-avi--ranjan--prasad-blue?logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/avi-ranjan-prasad-975842224/)
![GitHub](https://img.shields.io/badge/GitHub-thunderavi-black?logo=github&logoColor=white&link=https://github.com/thunderavi/)
![Email](https://img.shields.io/badge/Email-abhiranjanprasad0909%40gmail.com-red?logo=gmail&logoColor=white)

---

### 🌟 **Career Highlights**

- **Interned at EY**: Developed Django-based web applications with 30% system performance boost.
- **Princeton Smart Engineers**: Created dynamic, responsive web applications using JavaScript and PHP.

---

### 🚀 **Skills & Technologies**

| Programming Languages | Web Development | Machine Learning | Tools & Platforms |
|-----------------------|-----------------|------------------|-------------------|
| Java, Python, SQL     | Flask, HTML, CSS| Pandas, NumPy    | Git, AWS, Selenium|

---

✨ Let’s connect on [LinkedIn](https://www.linkedin.com/in/avi-ranjan-prasad-975842224/) or explore my projects on [GitHub](https://github.com/thunderavi) 🚀



---

### **Instructions for Setting Up Animations**

1. **GitHub Snake Game**: To set up the snake animation, create a `.github/workflows/snake.yml` file in your GitHub repository with the following configuration:

   ```yml
   name: Generate Snake

   on:
     schedule:
       - cron: "0 0 * * *"  # Runs every day at midnight
     workflow_dispatch:

   jobs:
     generate:
       runs-on: ubuntu-latest
       steps:
         - uses: Platane/snk@v2
           with:
             github_token: ${{ secrets.GITHUB_TOKEN }}
             svg_out_path: dist/github-contribution-grid-snake.svg

