<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reazonvan - Профиль</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
  <style>
    body {
      background-color: #121212;
      color: #FFFFFF;
      font-family: 'Fira Code', monospace;
    }
    .skill-icon {
      transition: transform 0.4s ease-in-out;
    }
    .skill-icon:hover {
      transform: rotate(360deg) scale(1.2);
    }
    .project-btn {
      transition: all 0.3s ease;
    }
    .project-btn:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(255, 0, 255, 0.4);
    }
    .glow {
      box-shadow: 0 0 15px #FF00FF, 0 0 30px #00FFFF;
    }
    .spinner {
      border: 4px solid #f3f3f3;
      border-top: 4px solid #FF00FF;
      border-radius: 50%;
      width: 30px;
      height: 30px;
      animation: spin 1s linear infinite;
      margin: 0 auto;
    }
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    a img {
      transition: transform 0.3s ease, opacity 0.3s ease;
    }
    a img:hover {
      transform: scale(1.1);
      opacity: 0.8;
    }
    .parallax {
      background-image: url('https://capsule-render.vercel.app/api?type=wave&color=gradient&height=250§ion=header&text=Добро+пожаловать+в+мой+космос+вайбкодинга!&fontSize=40&fontColor=FFFFFF&animation=twinkling');
      height: 250px;
      background-attachment: fixed;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
    }
  </style>
</head>
<body>
  <div id="particles-js" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0;"></div>
  
  <div align="center" class="animate__animated animate__fadeIn">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=35&pause=1000&color=FF00FF¢er=true&vCenter=true&width=600&lines=Привет!+Я+Reazonvan+👾;Энтузиаст+ИИ+и+вайбкодинга+🚀" alt="Typing SVG" />
  </div>

  <div align="center">
    <div class="parallax"></div>
  </div>

  <div align="center" class="glow">
    <img src="https://github-profile-trophy.vercel.app/?username=reazonvan&theme=dracula&no-frame=true&margin-w=15&column=6" alt="Trophies" />
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">🌌 Кто я?</h3>
  <p align="center">Привет, я <strong>Reazonvan</strong> — энтузиаст ИИ и вайбкодинга, который создает проекты с помощью больших языковых моделей! 🌟 Я использую <strong>Cursor</strong> и <strong>GitHub Copilot</strong>, чтобы превращать идеи в код за считанные часы. Моя миссия — вдохновлять других на использование ИИ в программировании и делиться своим опытом.</p>
  <ul align="center">
    <li>🔭 Работаю над проектами автоматизации и генерации кода.</li>
    <li>🌱 Изучаю новые ИИ-инструменты и подходы к вайбкодингу.</li>
    <li>💡 Люблю экспериментировать с технологиями и делиться результатами.</li>
    <li>📫 Связаться со мной: <a href="mailto:email@example.com">email@example.com</a> или через <a href="https://x.com/yourusername">X</a>.</li>
  </ul>

  <div align="center">
    <img class="skill-icon" src="https://skillicons.dev/icons?i=python,js,html,css,git,github,vscode,notion" alt="Skills" />
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">🛸 Что такое вайбкодинг?</h3>
  <p align="center">Вайбкодинг — это магия, где я описываю задачу ИИ, а он генерирует код, который я затем дорабатываю. Это позволяет мне создавать проекты быстрее и эффективнее! ✨ Мои любимые инструменты:</p>
  <ul align="center">
    <li>🛠️ <strong>Cursor</strong> — для генерации кода с нуля.</li>
    <li>🤖 <strong>GitHub Copilot</strong> — для автодополнения и идей.</li>
    <li>📝 <strong>Notion</strong> — для планирования и идей.</li>
  </ul>

  <div align="center">
    <img src="https://custom-icon-badges.demolab.com/badge/Использую-Cursor-FF00FF?style=for-the-badge&logo=cursor&logoColor=white" alt="Cursor Badge" />
    <img src="https://custom-icon-badges.demolab.com/badge/Использую-GitHub%20Copilot-00FFFF?style=for-the-badge&logo=github&logoColor=black" alt="GitHub Copilot Badge" />
    <img src="https://custom-icon-badges.demolab.com/badge/Планирую-Notion-FFFFFF?style=for-the-badge&logo=notion&logoColor=black" alt="Notion Badge" />
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">🚀 Мои проекты вайбкодинга</h3>
  <p align="center">Вот несколько проектов, созданных с помощью ИИ:</p>
  <ul align="center">
    <li><a href="https://github.com/reazonvan/podcast-transcriber">Podcast Transcriber</a> 🎙️ — Инструмент для транскрипции подкастов.</li>
    <li><a href="https://github.com/reazonvan/chatbot-generator">Chatbot Generator</a> 🤖 — Генератор чат-ботов.</li>
    <li><a href="https://github.com/reazonvan/weather-app">Weather App</a> ☀️ — Простое приложение для прогноза погоды.</li>
  </ul>
  <div align="center">
    <a href="https://github.com/reazonvan?tab=repositories" class="project-btn">
      <img src="https://custom-icon-badges.demolab.com/badge/Посмотреть%20все%20проекты-🌟-FF00FF?style=for-the-badge&logo=sparkles" alt="View All Projects" />
    </a>
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">🏆 Мои достижения</h3>
  <ul align="center">
    <li>🥇 Создал 10+ проектов с помощью вайбкодинга.</li>
    <li>🌟 Получил 50+ звезд на GitHub за мои проекты.</li>
    <li>📝 Написал статью о вайбкодинге на <a href="https://medium.com/@yourusername">Medium</a>.</li>
    <li>🤝 Внес вклад в 5 открытых проектов, связанных с ИИ.</li>
  </ul>

  <div align="center">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=reazonvan&repo=podcast-transcriber&theme=dracula" alt="Pinned Repo 1" />
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=reazonvan&repo=chatbot-generator&theme=dracula" alt="Pinned Repo 2" />
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">📈 Моя статистика</h3>
  <div align="center">
    <div class="spinner" id="stats-loader"></div>
    <img src="https://github-readme-stats.vercel.app/api?username=reazonvan&show_icons=true&theme=dracula&hide_border=true&include_all_commits=true" alt="GitHub Stats" onload="document.getElementById('stats-loader').style.display='none';" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=reazonvan&theme=dracula&hide_border=true" alt="GitHub Streak" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=reazonvan&layout=compact&theme=dracula&hide_border=true" alt="Top Languages" />
  </div>
  <div align="center">
    <img src="https://komarev.com/ghpvc/?username=reazonvan&color=FF00FF&style=flat-square" alt="Profile Views" />
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">🌐 Связаться со мной</h3>
  <div align="center">
    <a href="https://x.com/yourusername"><img src="https://custom-icon-badges.demolab.com/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
    <a href="https://linkedin.com/in/yourusername"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:email@example.com"><img src="https://custom-icon-badges.demolab.com/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </div>

  <h3 class="animate__animated animate__fadeIn" align="center">🎉 Fun Fact</h3>
  <p align="center">Я создал свой первый проект вайбкодинга всего за 3 часа, описав идею в 5 предложениях! ИИ сделал остальное. 🚀</p>
  <div align="center">
    <img src="https://media.giphy.com/media/3o7TKz2vFVpXSVfWxy/giphy.gif" width="200" alt="Coding GIF" />
  </div>

  <div align="center">
    <img src="https://capsule-render.vercel.app/api?type=wave&color=gradient&height=150§ion=footer&text=Спасибо+за+визит!+✨&fontSize=20&animation=twinkling" alt="Footer Banner" />
  </div>

  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      particles: {
        number: { value: 80 },
        color: { value: "#FF00FF" },
        shape: { type: "circle" },
        opacity: { value: 0.5 },
        size: { value: 3 },
        move: { speed: 6 }
      }
    });
  </script>
</body>
</html>
