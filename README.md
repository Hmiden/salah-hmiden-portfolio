<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Salah Hmiden — Cloud & DevOps</title>

  <!-- Optionnel : Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg: #0f1724;
      --card: #0b1220;
      --muted: #98a0b3;
      --accent: #60a5fa;
      --accent-2: #7dd3fc;
      --text: #e6eef8;
      --glass: rgba(255,255,255,0.03);
      --radius: 12px;
      --max-width: 900px;
      --gap: 1rem;
    }

    /* Light mode support */
    @media (prefers-color-scheme: light){
      :root{
        --bg: #f5f7fb;
        --card: #ffffff;
        --muted: #6b7280;
        --accent: #2563eb;
        --accent-2: #06b6d4;
        --text: #0b1220;
        --glass: rgba(10,10,10,0.03);
      }
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg, var(--bg) 0%, color-mix(in srgb, var(--bg) 80%, transparent 20%));
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:2rem;
    }

    .card{
      width:100%;
      max-width:var(--max-width);
      background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);
      border-radius:var(--radius);
      padding:1.6rem;
      box-shadow: 0 8px 30px rgba(2,6,23,0.6);
      border: 1px solid rgba(255,255,255,0.03);
    }

    header{
      text-align:center;
      margin-bottom:1rem;
    }

    h1{
      margin:0;
      font-size:1.35rem;
      letter-spacing:-0.2px;
      display:flex;
      align-items:center;
      justify-content:center;
      gap:0.6rem;
      flex-wrap:wrap;
    }

    .subline{
      margin-top:0.45rem;
      color:var(--muted);
      font-size:0.95rem;
    }

    .meta a{
      color:var(--accent);
      text-decoration:none;
    }
    .meta a:hover{ text-decoration:underline; color:var(--accent-2) }

    hr.separator{
      border:0;
      height:1px;
      background:linear-gradient(90deg, rgba(255,255,255,0), rgba(255,255,255,0.03), rgba(255,255,255,0));
      margin:1.2rem 0;
      border-radius:4px;
    }

    section{
      margin-bottom:1rem;
    }

    .about{
      line-height:1.55;
      color:var(--text);
      font-size:0.98rem;
    }

    .grid-2{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:var(--gap);
    }

    /* Skills list */
    .skills{
      display:flex;
      flex-direction:column;
      gap:0.6rem;
    }

    .skill-title{
      font-weight:600;
      font-size:0.98rem;
      margin-bottom:0.25rem;
    }

    ul.tech{
      margin:0;
      padding-left:1.1rem;
      color:var(--muted);
      line-height:1.6;
    }

    /* Projects */
    .projects{
      display:grid;
      grid-template-columns: 1fr;
      gap:0.8rem;
    }
    .project{
      background:var(--glass);
      border-radius:10px;
      padding:0.8rem;
      border:1px solid rgba(255,255,255,0.02);
    }
    .project b{display:block; margin-bottom:0.2rem; font-weight:600;}
    .project .stack{color:var(--muted); font-size:0.92rem; margin-bottom:0.4rem}

    /* Certifications & Contact */
    .two-col{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap:var(--gap);
    }

    .list{
      margin:0;
      padding-left:1.05rem;
      color:var(--muted);
      line-height:1.6;
    }

    footer{
      text-align:center;
      margin-top:1rem;
      color:var(--muted);
      font-size:0.9rem;
    }

    /* Small screens */
    @media (max-width:720px){
      .grid-2, .two-col{ grid-template-columns: 1fr; }
      h1{ font-size:1.1rem }
      .card{ padding:1.1rem }
    }

    /* Print friendly */
    @media print{
      body{background:white; color:black}
      .card{box-shadow:none; border: none; background:transparent}
      a::after{ content: " (" attr(href) ")"; color: black; font-size: 10px; }
    }
  </style>
</head>
<body>
  <article class="card" role="article">
    <header>
      <h1>🚀 Salah Hmiden — Cloud & DevOps Engineering Student</h1>
      <div class="subline meta">📍 Tunis, Tunisia • 📫 <a href="mailto:salah.hmiden@esprit.tn">salah.hmiden@esprit.tn</a> • <a href="https://linkedin.com/in/salah-hmiden" target="_blank" rel="noopener">LinkedIn</a></div>
    </header>

    <hr class="separator">

    <section class="about">
      <strong>🌟 À propos de moi</strong>
      <p>Étudiant en <strong>Cloud & DevOps Engineering</strong>, passionné par l’automatisation, l’infrastructure cloud, la conteneurisation et l’observabilité. J’aime construire des plateformes fiables, scalables et monitorées en combinant <strong>CI/CD, Cloud, Docker/Kubernetes et Monitoring avancé</strong>. Actuellement à la recherche d’une <strong>alternance Cloud/DevOps</strong>.</p>
    </section>

    <section class="grid-2">
      <div>
        <strong>🛠️ Compétences Techniques</strong>
        <div class="skills">
          <div>
            <div class="skill-title">⚙️ DevOps & CI/CD</div>
            <ul class="tech">
              <li>Jenkins, GitLab CI/CD, SonarQube, Nexus</li>
              <li>Pipelines CI/CD & automatisation</li>
            </ul>
          </div>

          <div>
            <div class="skill-title">☁️ Cloud & Infrastructure</div>
            <ul class="tech">
              <li>OpenStack, AWS — Terraform, Ansible</li>
              <li>Linux, Networking, IaC</li>
            </ul>
          </div>

          <div>
            <div class="skill-title">🐳 Containers & Orchestration</div>
            <ul class="tech">
              <li>Docker, Kubernetes (pods, deployments, services)</li>
            </ul>
          </div>

          <div>
            <div class="skill-title">📊 Monitoring & Observabilité</div>
            <ul class="tech">
              <li>Prometheus, Grafana — alerting & logs</li>
            </ul>
          </div>
        </div>
      </div>

      <div>
        <strong>💻 Développement</strong>
        <ul class="tech">
          <li>Java, Spring Boot • Angular</li>
          <li>Python, Bash • MySQL, SQL</li>
        </ul>

        <div style="height:0.6rem"></div>

        <strong>🎓 Certifications</strong>
        <ul class="list">
          <li>AWS Cloud Foundations</li>
          <li>AWS Cloud Operations</li>
          <li>Jenkins – KodeKloud</li>
          <li>Scrum Fundamentals</li>
          <li>CCNA Routing & Switching</li>
        </ul>
      </div>
    </section>

    <hr class="separator">

    <section>
      <strong>🚀 Projets Principaux</strong>
      <div class="projects" style="margin-top:0.6rem">
        <div class="project">
          <b>1️⃣ CI/CD Pipeline End-to-End</b>
          <div class="stack">Stack : Jenkins, GitLab, Docker, SonarQube, Nexus, Spring Boot, Angular</div>
          <div>Build automatisé • Analyse qualité • Déploiement Dockerisé • Monitoring via Prometheus & Grafana</div>
        </div>

        <div class="project">
          <b>2️⃣ Monitoring & Observabilité</b>
          <div class="stack">Stack : Prometheus, Grafana, Docker</div>
          <div>Dashboards temps réel • Alerting • Supervision CPU/RAM/latence API</div>
        </div>

        <div class="project">
          <b>3️⃣ Cloud Infrastructure Automation — OpenStack</b>
          <div class="stack">Stack : Terraform, Ansible, OpenStack</div>
          <div>Provisioning automatique • Déploiement App + DB • Scripts Ansible</div>
        </div>

        <div class="project">
          <b>4️⃣ Plateforme Full-Stack Tutoriels</b>
          <div class="stack">Stack : Spring Boot, Angular, MySQL</div>
          <div>API REST sécurisée • Dashboard admin • CI/CD GitLab</div>
        </div>

        <div class="project">
          <b>5️⃣ Smart Irrigation System (IoT)</b>
          <div class="stack">Stack : STM32, LoRa, Python</div>
          <div>Réduction consommation d’eau • Transmission longue portée • Monitoring</div>
        </div>
      </div>
    </section>

    <hr class="separator">

    <section class="two-col">
      <div>
        <strong>📬 Contact</strong>
        <ul class="list">
          <li>Email : <a href="mailto:salah.hmiden@esprit.tn">salah.hmiden@esprit.tn</a></li>
          <li>LinkedIn : <a href="https://linkedin.com/in/salah-hmiden" target="_blank" rel="noopener">linkedin.com/in/salah-hmiden</a></li>
          <li>GitHub : <a href="https://github.com/Hmiden" target="_blank" rel="noopener">github.com/Hmiden</a></li>
        </ul>
      </div>

      <div>
        <strong>🔖 Remerciements</strong>
        <p style="color:var(--muted); margin:0.2rem 0 0 0">✨ Merci pour votre visite !</p>
      </div>
    </section>

    <footer>
      <small>Fichier généré — Salah Hmiden</small>
    </footer>
  </article>
</body>
</html>
