# 👋 Hi, I'm Diyorbek

### 💻 Frontend Developer from Uzbekistan 🇺🇿

I’m a young developer passionate about building modern and responsive websites.

### 🚀 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,git,github,vscode" />
</p>

### 📌 About Me

* 🌱 Currently learning **Frontend Development**
* ⚛️ Working with **React**
* 💡 Interested in modern web technologies
* 🎯 Goal: Become a professional Full-Stack Developer
* 🇺🇿 Based in Uzbekistan

### 🛠️ Projects

* 🌐 **Portfolio Website**
* 🍔 **Fast Food Website**
* 📝 **Todo App**
* 🛒 **E-commerce Projects**

### 📊 GitHub Stats


### 🔥 Contribution



### 📫 Contact

🌐 Portfolio: https://abdurahmon-uzb.netlify.app/

💻 GitHub: https://github.com/Abdusaitov13


Maxsus Profil README (Profil interfeysiga kirish joyi)
GitHub'da foydalanuvchi nomingiz bilan bir xil repository yarating (masalan, foydalanuvchi nomingiz ali-dev bo'lsa, repo nomi ham ali-dev bo'ladi).

Uni Public qiling.

Add a README file katakchasiga belgi qo'ying.

Ushbu README.md fayliga quyidagi tayyor va chiroyli shablonni nusxalab joylang (tegishli joylarni o'zingizning ma'lumotlaringiz bilan almashtiring):

Markdown
# Hi there, I'm [Ismingiz] 👋

### 👨‍💻 About Me
- 🔭 I’m currently working on **[Loyiha nomi yoki Web Projects]**
- 🌱 I’m currently learning **[Texnologiyalar: masalan, React, Node.js]**
- 💬 Ask me about **HTML, CSS, JavaScript**
- 📬 How to reach me: **[Telegram link yoki Email]**

---

### 🛠️ Tech Stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)


name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            
      - name: Push Snake SVG to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

