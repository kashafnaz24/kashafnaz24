<!-- Save as index.html and push to GitHub -->
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Kashaf Naz — Portfolio</title>
<meta name="description" content="Kashaf Naz — Frontend Developer | React, Next.js, TypeScript, Web3 & AI learner" />
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0f1724; --panel:#0b1220; --muted:#94a3b8; --accent:#7c3aed; --glass:rgba(255,255,255,0.04);
    --card-grad: linear-gradient(135deg, rgba(124,58,237,0.12), rgba(99,102,241,0.06));
    color-scheme: light;
  }
  *{box-sizing:border-box}
  body{font-family:Inter,system-ui,Arial; margin:0; background:linear-gradient(180deg,#071021 0%, #081026 60%); color:#e6eef8; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale;}
  .container{max-width:1000px; margin:40px auto; padding:28px;}
  header{display:flex;gap:18px;align-items:center}
  .logo{width:64px;height:64px;border-radius:12px;background:var(--card-grad);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);font-size:22px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
  h1{margin:0;font-size:28px}
  .sub{color:var(--muted);margin-top:6px}
  .hero{display:grid;grid-template-columns:1fr 320px;gap:28px;margin-top:26px}
  .card{background:var(--panel);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6);}
  .about p{color:var(--muted);line-height:1.6}
  .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
  .chip{background:var(--glass);padding:8px 10px;border-radius:999px;font-size:13px;color:#dbeafe}
  .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin-top:16px}
  .proj{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:14px;border-radius:10px}
  .proj h4{margin:0 0 6px 0}
  .btn{display:inline-block;padding:8px 12px;border-radius:8px;background:var(--accent);color:white;text-decoration:none;font-weight:600}
  .footer{margin-top:28px;color:var(--muted);font-size:13px}
  /* Responsive */
  @media(max-width:880px){
    .hero{grid-template-columns:1fr; }
    .projects{grid-template-columns:1fr}
  }
  /* small utilities */
  .row{display:flex;gap:8px;align-items:center}
  .muted{color:var(--muted)}
  a.badge{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.03);color:var(--muted);text-decoration:none;font-size:13px}
</style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo" aria-hidden>KN</div>
      <div>
        <h1>Kashaf Naz <span class="muted">• Frontend Developer</span></h1>
        <div class="sub">React · Next.js · TypeScript · Tailwind · Node · MongoDB · Firebase · AI (learning)</div>
      </div>
    </header>

    <section class="hero">
      <div>
        <div class="card about">
          <h2 style="margin-top:0">About Me</h2>
          <p>Hi — I'm <strong>Kashaf</strong>. I build modern, responsive websites and web apps using React, Next.js and TypeScript.
          I’m currently learning Python, the OpenAI SDK and Web3 technologies. I study at GI-AIWMD & SMIT.</p>

          <div style="margin-top:14px">
            <a class="btn" href="#projects">View Projects</a>
            <a class="badge" href="mailto:kashafnazk389@gmail.com">✉️ Email</a>
            <a class="badge" href="https://github.com/kashafnaz24" target="_blank">GitHub</a>
          </div>

          <div style="margin-top:18px">
            <strong>Skills</strong>
            <div class="skills">
              <span class="chip">HTML5</span>
              <span class="chip">CSS3</span>
              <span class="chip">Tailwind</span>
              <span class="chip">JavaScript</span>
              <span class="chip">TypeScript</span>
              <span class="chip">React</span>
              <span class="chip">Next.js</span>
              <span class="chip">Node.js</span>
              <span class="chip">MongoDB</span>
              <span class="chip">Firebase</span>
            </div>
          </div>
        </div>

        <div style="margin-top:14px" class="card">
          <h3 style="margin:0 0 8px 0">Experience & Learning</h3>
          <p class="muted" style="margin:0 0 8px 0">Student at GI-AIWMD & SMIT • Projects: websites, forms, UI components • Currently focused on AI & Web3</p>
          <div class="row" style="margin-top:8px">
            <a class="badge" href="#contact">Hire / Collaborate</a>
            <a class="badge" href="#projects">See Work</a>
          </div>
        </div>
      </div>

      <aside>
        <div class="card" style="position:sticky;top:28px">
          <h3 style="margin:0 0 8px 0">Contact</h3>
          <p class="muted" style="margin:0 0 8px 0">Email</p>
          <p style="margin:0 0 12px"><strong>kashafnazk389@gmail.com</strong></p>
          <p class="muted" style="margin:0 0 8px 0">Location</p>
          <p style="margin:0 0 12px"><strong>Karachi, Pakistan</strong></p>
          <p class="muted" style="margin:0 0 8px 0">Available For</p>
          <p style="margin:0 0 0"><strong>Freelance • Internships • Open-source</strong></p>
        </div>
      </aside>
    </section>

    <section id="projects" style="margin-top:28px">
      <h2>Projects</h2>
      <div class="projects">
        <div class="proj">
          <h4>Portfolio Homepage</h4>
          <p class="muted">React / Next.js / Tailwind — Personal portfolio and projects showcase.</p>
          <div style="margin-top:10px"><a class="btn" href="#">View Repo</a></div>
        </div>

        <div class="proj">
          <h4>Interactive Forms</h4>
          <p class="muted">Accessible form components with validation — built with React + TypeScript.</p>
          <div style="margin-top:10px"><a class="btn" href="#">View Repo</a></div>
        </div>

        <div class="proj">
          <h4>Analog Clock (JS)</h4>
          <p class="muted">Vanilla JS & CSS responsive clock — UI component practice.</p>
        </div>

        <div class="proj">
          <h4>Node + Firebase Auth</h4>
          <p class="muted">Auth flow and Firestore integration for a simple web app.</p>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap">
        <div>© <strong>Kashaf Naz</strong> — Built with ❤️</div>
        <div style="display:flex;gap:10px"><a class="badge" href="https://github.com/kashafnaz24">GitHub</a><a class="badge" href="mailto:kashafnazk389@gmail.com">Email</a></div>
      </div>
    </footer>
  </div>
</body>
</html>

