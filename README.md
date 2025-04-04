<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">
</head>
<style>
body {
  min-height: 100vh;
  font-family: "JetBrains Mono", monospace;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}
main {
  margin: 32px 0;
}
.social, .support, h1, h2, h3 {
  text-align: center;
}
.tech_icons {
  text-align: center;
  display: flex;
  flex-wrap: wrap;
  gap: 4px;
  justify-content: center;
}
.github_header_image_dev {
  text-align: center;
  margin: 0 auto;
  padding: 1px;
  border-radius: 16px;
  position: relative;
}
@property --angle {
  syntax: "<angle>";
  initial-value: 0deg;
  inherits: false;
}
.github_header_image_dev::after, .github_header_image_dev::before {
  content: '';
  position: absolute;
  height: 100%;
  width: 100%;
  background-image: conic-gradient(from var(--angle), #ff4545, #00ff99, #006aff, #ff0095, #ff4545);
  top: 50%;
  left: 50%;
  translate: -50% -50%;
  z-index: -1;
  padding: 1px;
  border-radius: 16px;
  animation: 7s spin linear infinite;
}
.github_header_image_dev::before {
  filter: blur(3rem);
  opacity: 0.5;
}
@keyframes spin {
  from {
    --angle: 0deg;
  }
  to {
    --angle: 360deg;
  }
}
</style>
<body>
<header>
  <div class="github_header_image_dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./img/header_main_image/compressed/github_header_image_dev_dark_compressed.png">
      <source media="(prefers-color-scheme: light)" srcset="./img/header_main_image/compressed/github-header-image_dev_light_compressed.png">
      <img alt="github-snake" src="./img/header_main_image/compressed/github_header_image_dev_dark_compressed.png">
    </picture>
  </div>
  <br>
  <h1>👋 Hi there! I'm a JavaScript developer passionate about building modern web applications and scalable solutions. My expertise lies in crafting interactive user interfaces and robust backend systems.</h1>
  <h2>⚡ Passionate fullstack web developer, creating robust and scalable web applications. Skilled in both front-end and back-end technologies, with a keen eye for user experience and performance optimization.</h2>
  <h2>🚀 Open to collaborations, open-source contributions, and interesting challenges. Feel free to reach out for technical discussions or potential opportunities! Connect with me:</h3>
  <div class="social">
    <a href="https://twitter.com/ArchDeadShadow" target="_blank"><img src="https://img.shields.io/badge/  Twitter-000000?style=flat-square&logo=X&logoColor=white" height="28" style="margin-right: 4px"></a>
    <a href="https://www. instagram.com/archdeadshadow" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square& logo=instagram&logoColor=white" height="28" style="margin-right: 4px"></a>
    <a href="https://www.linkedin.com/in/sergey-r-a52219230" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&  logo=linkedin&logoColor=white" height="28" style="margin-right: 4px"></a>
  </div>
</header>
<main>
  <h1>🦉 Skills</h1>

### 💻 Technical Toolkit

- **Languages**: JavaScript (ES6+), HTML5, CSS3
- **Frontend**: React.js (Hooks, Context API, React Router)
- **Backend**: Node.js, Express.js
- **Databases**: MongoDB (Mongoose ODM, database design)
- **Tools**: Git, REST APIs, Webpack, npm/yarn

### 😎 What I Do Best

- Develop responsive SPAs with React
- Create RESTful APIs using Node.js/Express
- Design efficient database architectures with MongoDB
- Implement full-stack solutions from concept to deployment

### 📌 Current Focus

Sharpening my skills in performance optimization and exploring TypeScript integration. Always learning new patterns and best practices!

### 🗂️ Featured Projects

Check out my repositories below to see examples of:

- Full-stack **_MERN_** applications
- Reusable React components
- API development projects
- Database optimization techniques
</main>
<footer>
  <div class="snake_game_contribution_calendar" align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./img/snake_game_contribution_calendar/github-snake-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="./img/snake_game_contribution_calendar/github-snake.svg">
      <img alt="github-snake" src="./img/snake_game_contribution_calendar/github-snake-dark.svg">
    </picture>
  </div>
  <br>
  <div class="tech_icons" align="center">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1C?logo=javascript&logoColor=white" height="28" alt="JavaScript" style="margin-right: 4px">
    <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" height="28" alt="React" style="margin-right: 4px">
    <img src="https://img.shields.io/badge/Node.js-8CC84B?logo=node.js&logoColor=white" height="28" alt="Node.js" style="margin-right: 4px">
    <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white" height="28" alt="Express" style="margin-right: 4px">
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white" height="28" alt="MongoDB" style="margin-right: 4px">
    <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" height="28" alt="Docker" style="margin-right: 4px">
  </div>
  <br>
  <div class="support">
    <h3>💸 Support Me</h3>
    <p><a href="https://www.paypal.com/donate/?hosted_button_id=QCEZHJJG8HRD8" target="_blank"><img src="https://img.shields.io/badge/PayPal-00457C?style=flat-square&logo=paypal&logoColor=white" height="28" style="margin-right: 4px"></a></p>
  </div>
</footer>
</body>
</html>
