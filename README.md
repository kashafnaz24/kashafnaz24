<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kashaf Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background: #0f0f0f;
      color: #ffffff;
    }
    header {
      padding: 40px;
      text-align: center;
      background: #161616;
    }
    header h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 18px;
      opacity: 0.8;
    }

    .section {
      max-width: 900px;
      margin: 50px auto;
      padding: 20px;
    }

    h2 {
      margin-bottom: 20px;
      border-left: 5px solid #ff4df0;
      padding-left: 10px;
      font-size: 28px;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 20px;
    }

    .skill-box {
      background: #1c1c1c;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      font-size: 18px;
      transition: 0.3s;
    }

    .skill-box:hover {
      background: #292929;
      transform: translateY(-5px);
    }

    .projects {
      display: grid;
      gap: 20px;
    }

    .project-card {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
      transition: 0.3s;
    }

    .project-card:hover {
      background: #292929;
      transform: translateY(-5px);
    }

    footer {
      text-align: center;
      padding: 30px;
      margin-top: 50px;
      background: #161616;
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <header>
    <h1>Kashaf Naz</h1>
    <p>Frontend Developer • Full-Stack Learner • AI & Web3 Enthusiast</p>
  </header>

  <section class="section">
    <h2>About Me</h2>
    <p>
      I'm an AI & Web Development student at GI-AIWMD and SMIT. I build modern,
      clean and responsive websites using React, Next.js and Tailwind CSS.
      Currently learning Python, AI with OpenAI SDK and Web3.
    </p>
  </section>

  <section class="section">
    <h2>Skills</h2>
    <div class="skills-grid">
      <div class="skill-box">HTML</div>
      <div class="skill-box">CSS</div>
      <div class="skill-box">Tailwind</div>
      <div class="skill-box">JavaScript</div>
      <div class="skill-box">TypeScript</div>
      <div class="skill-box">React</div>
      <div class="skill-box">Next.js</div>
      <div class="skill-box">Node.js</div>
      <div class="skill-box">MongoDB</div>
      <div class="skill-box">Firebase</div>
      <div class="skill-box">Python</div>
      <div class="skill-box">AI / OpenAI SDK</div>
    </div>
  </section>

  <section class="section">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>🔥 Project 1</h3>
        <p>Short description about your project.</p>
      </div>
      <div class="project-card">
        <h3>⚡ Project 2</h3>
        <p>Short description about your project.</p>
      </div>
      <div class="project-card">
        <h3>🌐 Project 3</h3>
        <p>Short description about your project.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Kashaf • All Rights Reserved</p>
  </footer>
</body>
</html>

