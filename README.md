<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Junaid Sami | Full Stack Developer</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #0f172a, #020617);
      color: #e5e7eb;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
    }

    .container {
      max-width: 1100px;
      width: 100%;
    }

    /* HERO */
    .hero {
      text-align: center;
      margin-bottom: 60px;
    }

    .hero h1 {
      font-size: 56px;
      font-weight: 700;
      margin-bottom: 10px;
    }

    .hero h1 span {
      background: linear-gradient(135deg, #38bdf8, #818cf8);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero h2 {
      font-size: 24px;
      font-weight: 500;
      opacity: 0.9;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 16px;
      opacity: 0.75;
      max-width: 650px;
      margin: 0 auto 30px;
      line-height: 1.6;
    }

    .btn {
      display: inline-block;
      padding: 14px 34px;
      border-radius: 999px;
      font-weight: 500;
      background: linear-gradient(135deg, #38bdf8, #818cf8);
      color: #020617;
      text-decoration: none;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      box-shadow: 0 15px 40px rgba(56,189,248,0.35);
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 20px 50px rgba(129,140,248,0.45);
    }

    /* GRID */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      margin-bottom: 50px;
    }

    .card {
      background: rgba(255,255,255,0.06);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255,255,255,0.12);
      border-radius: 18px;
      padding: 30px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.35);
    }

    .card h3 {
      font-size: 20px;
      margin-bottom: 18px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .card ul {
      list-style: none;
    }

    .card ul li {
      margin-bottom: 10px;
      font-size: 15px;
      opacity: 0.85;
    }

    /* TECH STACK */
    .tech {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
      gap: 20px;
      text-align: center;
    }

    .tech i {
      font-size: 32px;
      padding: 18px;
      border-radius: 14px;
      background: rgba(255,255,255,0.08);
      transition: transform 0.25s ease, box-shadow 0.25s ease;
      cursor: pointer;
    }

    .tech i:hover {
      transform: scale(1.15);
      box-shadow: 0 0 18px rgba(56,189,248,0.6);
    }

    /* FOOTER */
    .footer {
      text-align: center;
      font-size: 14px;
      opacity: 0.6;
      font-style: italic;
    }

    @media (max-width: 600px) {
      .hero h1 { font-size: 40px; }
      .hero h2 { font-size: 20px; }
    }
  </style>
</head>
<body>

  <div class="container">

    <!-- HERO -->
    <section class="hero">
      <h1>Hi 👋 I'm <span>Junaid Sami</span></h1>
      <h2>Full‑Stack Web Developer</h2>
      <p>I build scalable web applications, LMS, CMS & business systems with clean architecture and performance in mind.</p>
      <a href="#" class="btn">View Projects</a>
    </section>

    <!-- CONTENT GRID -->
    <section class="grid">

      <!-- ABOUT -->
      <div class="card">
        <h3>🧠 About Me</h3>
        <ul>
          <li>✅ 3+ years of professional experience</li>
          <li>🚀 30+ production-ready projects</li>
          <li>🌐 Multi-language & role-based systems</li>
          <li>💳 Stripe & payment gateway integrations</li>
          <li>⚡ Clean code & performance-focused</li>
        </ul>
      </div>

      <!-- TECH STACK -->
      <div class="card">
        <h3>⚙️ Tech Stack</h3>
        <div class="tech">
          <i class="fab fa-php" title="PHP"></i>
          <i class="fab fa-laravel" title="Laravel"></i>
          <i class="fab fa-react" title="React"></i>
          <i class="fab fa-vuejs" title="Vue"></i>
          <i class="fab fa-node-js" title="Node.js"></i>
          <i class="fab fa-aws" title="AWS"></i>
          <i class="fab fa-git-alt" title="Git"></i>
          <i class="fab fa-github" title="GitHub"></i>
        </div>
      </div>

    </section>

    <!-- FOOTER -->
    <div class="footer">
      ⚡ Turning complex ideas into simple, powerful solutions.
    </div>

  </div>

</body>
</html>
