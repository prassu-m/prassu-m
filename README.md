# 💫 About Me:
🎯 I’m a hands-on Data Engineer and Cloud Data Professional focused on building scalable data pipelines, high-performance analytics platforms, and automation systems that drive real business impact.

🧠 I work across distributed systems, real-time streaming, and enterprise cloud environments — solving complex data problems with a strong focus on scalability, reliability, and performance, not just writing code.

⚡ Passionate about:

Large-scale data engineering & distributed systems
Cloud-native data architectures (GCP / AWS / Azure)
Real-time streaming & analytics pipelines
Data modeling, ETL/ELT optimization, and automation
AI + Data Engineering integration for smarter systems


## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/https://discord.gg/G6djH38GuF) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)]([https://www.linkedin.com/in/prassu-m/](https://www.linkedin.com/in/prasannam01/))  [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:prasannalakshmim01@gmail.com) 

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Technical Toolkit</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet" />
<style>
  :root {
    --bg: #0f1117;
    --card-bg: #161922;
    --border: #262a36;
    --text: #e2e4ea;
    --text-muted: #8b8fa3;
    --accent-blue: #4f8ff7;
    --accent-green: #34d399;
    --accent-orange: #f59e0b;
    --accent-purple: #a78bfa;
    --accent-pink: #f472b6;
    --accent-cyan: #22d3ee;
    --radius: 12px;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--bg);
    color: var(--text);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    padding: 40px 20px;
  }

  .container {
    max-width: 960px;
    width: 100%;
  }

  /* ── Header ── */
  .header {
    margin-bottom: 32px;
  }

  .header h1 {
    font-family: 'JetBrains Mono', monospace;
    font-size: 28px;
    font-weight: 700;
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 8px;
  }

  .header h1 .icon {
    font-size: 26px;
  }

  .tagline {
    font-size: 15px;
    color: var(--text-muted);
    padding-left: 2px;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .tagline strong {
    color: var(--text);
    font-weight: 600;
  }

  /* ── Grid Table ── */
  .toolkit-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    overflow: hidden;
    background: var(--card-bg);
  }

  .col-header {
    padding: 16px 20px;
    font-family: 'JetBrains Mono', monospace;
    font-weight: 700;
    font-size: 14px;
    letter-spacing: 0.02em;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 8px;
    background: rgba(255,255,255,0.02);
  }

  .col-header:not(:last-child) {
    border-right: 1px solid var(--border);
  }

  .col-header .emoji { font-size: 16px; }

  .cell {
    padding: 18px 20px;
    font-size: 14px;
    line-height: 1.7;
    color: var(--text-muted);
  }

  .cell:not(:last-child) {
    border-right: 1px solid var(--border);
  }

  .cell:not(:nth-last-child(-n+4)) {
    border-bottom: 1px solid var(--border);
  }

  .cell span {
    display: inline;
  }

  .cell .tag {
    color: var(--text);
    font-weight: 500;
    transition: color 0.2s;
  }

  .cell .tag:hover {
    color: var(--accent-blue);
    cursor: default;
  }

  /* ── Badges Section ── */
  .badges-section {
    margin-top: 40px;
  }

  .badges-section h2 {
    font-family: 'JetBrains Mono', monospace;
    font-size: 20px;
    font-weight: 700;
    margin-bottom: 18px;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .badges-wrap {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    height: 28px;
    border-radius: 4px;
    overflow: hidden;
    font-size: 12px;
    font-family: 'JetBrains Mono', monospace;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.03em;
    cursor: default;
    transition: transform 0.15s, box-shadow 0.15s;
  }

  .badge:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.4);
  }

  .badge .badge-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
    padding: 0 8px;
    font-size: 14px;
  }

  .badge .badge-label {
    padding: 0 10px;
    height: 100%;
    display: flex;
    align-items: center;
    color: #fff;
  }

  /* ── Badge Colors ── */
  .b-python    { background: #3776AB; }
  .b-python .badge-icon { background: #306998; }
  .b-sql       { background: #336791; }
  .b-sql .badge-icon { background: #2a5578; }
  .b-pyspark   { background: #E25A1C; }
  .b-pyspark .badge-icon { background: #c44e18; }
  .b-scala     { background: #DC322F; }
  .b-scala .badge-icon { background: #b52926; }
  .b-azure     { background: #0078D4; }
  .b-azure .badge-icon { background: #0063b0; }
  .b-aws       { background: #FF9900; }
  .b-aws .badge-icon { background: #de8500; }
  .b-snowflake { background: #29B5E8; }
  .b-snowflake .badge-icon { background: #219bc5; }
  .b-databricks{ background: #FF3621; }
  .b-databricks .badge-icon { background: #d42d1b; }
  .b-spark     { background: #E6522C; }
  .b-spark .badge-icon { background: #c44524; }
  .b-kafka     { background: #231F20; }
  .b-kafka .badge-icon { background: #111; }
  .b-airflow   { background: #017CEE; }
  .b-airflow .badge-icon { background: #0166c5; }
  .b-dbt       { background: #FF694B; }
  .b-dbt .badge-icon { background: #d6583e; }
  .b-powerbi   { background: #F2C811; color: #000; }
  .b-powerbi .badge-icon { background: #d4b00f; }
  .b-powerbi .badge-label { color: #000; }
  .b-docker    { background: #2496ED; }
  .b-docker .badge-icon { background: #1d7ec5; }
  .b-k8s       { background: #326CE5; }
  .b-k8s .badge-icon { background: #2958bf; }
  .b-jenkins   { background: #D24939; }
  .b-jenkins .badge-icon { background: #b03d2f; }
  .b-git       { background: #F05032; }
  .b-git .badge-icon { background: #cc4429; }
  .b-postgres  { background: #4169E1; }
  .b-postgres .badge-icon { background: #3557be; }
  .b-mongodb   { background: #47A248; }
  .b-mongodb .badge-icon { background: #3b883c; }
  .b-delta     { background: #003366; }
  .b-delta .badge-icon { background: #002244; }
  .b-jira      { background: #0052CC; }
  .b-jira .badge-icon { background: #0043a8; }
  .b-terraform { background: #7B42BC; }
  .b-terraform .badge-icon { background: #65369b; }
  .b-tableau   { background: #E97627; }
  .b-tableau .badge-icon { background: #c5631f; }

  /* ── Copy Section ── */
  .copy-section {
    margin-top: 40px;
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    overflow: hidden;
  }

  .copy-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 20px;
    border-bottom: 1px solid var(--border);
    background: rgba(255,255,255,0.02);
  }

  .copy-header span {
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    color: var(--text-muted);
  }

  .copy-btn {
    background: var(--accent-blue);
    border: none;
    color: #fff;
    padding: 6px 14px;
    border-radius: 6px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    font-weight: 600;
    cursor: pointer;
    transition: background 0.2s, transform 0.1s;
  }

  .copy-btn:hover { background: #3d7de0; }
  .copy-btn:active { transform: scale(0.96); }

  .code-block {
    padding: 16px 20px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    line-height: 1.6;
    color: var(--text-muted);
    white-space: pre-wrap;
    word-break: break-all;
    max-height: 260px;
    overflow-y: auto;
  }

  /* ── Responsive ── */
  @media (max-width: 768px) {
    .toolkit-grid {
      grid-template-columns: repeat(2, 1fr);
    }
    .col-header:nth-child(2) { border-right: none; }
    .col-header:nth-child(4) { border-right: none; }
    .cell:nth-child(even) { border-right: none; }
  }

  @media (max-width: 480px) {
    .toolkit-grid {
      grid-template-columns: 1fr;
    }
    .col-header, .cell { border-right: none !important; }
  }

  /* ── Animations ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(16px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .header           { animation: fadeUp 0.5s ease both; }
  .toolkit-grid     { animation: fadeUp 0.5s ease 0.1s both; }
  .badges-section   { animation: fadeUp 0.5s ease 0.2s both; }
  .copy-section     { animation: fadeUp 0.5s ease 0.3s both; }
</style>
</head>
<body>
<div class="container">

  <!-- Header -->
  <div class="header">
    <h1><span class="icon">🛠</span> Technical Toolkit</h1>
    <p class="tagline">💡 I focus on <strong>systems that are scalable, observable, and reliable.</strong></p>
  </div>

  <!-- Grid Table -->
  <div class="toolkit-grid">
    <!-- Column Headers -->
    <div class="col-header"><span class="emoji">🧠</span> Core Skills</div>
    <div class="col-header"><span class="emoji">☁️</span> Cloud &amp; Platform</div>
    <div class="col-header"><span class="emoji">⚙️</span> Engineering</div>
    <div class="col-header"><span class="emoji">📊</span> Analytics</div>

    <!-- Row 1 -->
    <div class="cell">
      <span class="tag">Data Engineering</span>, <span class="tag">Big Data</span>, <span class="tag">Distributed Systems</span>
    </div>
    <div class="cell">
      <span class="tag">Azure</span>, <span class="tag">AWS</span>, <span class="tag">Snowflake</span>, <span class="tag">Databricks</span>
    </div>
    <div class="cell">
      <span class="tag">Spark</span>, <span class="tag">Kafka</span>, <span class="tag">Airflow</span>, <span class="tag">dbt</span>, <span class="tag">Delta Lake</span>
    </div>
    <div class="cell">
      <span class="tag">Power BI</span>, <span class="tag">Tableau</span>, <span class="tag">Grafana</span>, <span class="tag">QuickSight</span>
    </div>

    <!-- Row 2 -->
    <div class="cell">
      <span class="tag">Python</span>, <span class="tag">SQL</span>, <span class="tag">PySpark</span>, <span class="tag">Scala</span>
    </div>
    <div class="cell">
      <span class="tag">Kubernetes</span>, <span class="tag">Terraform</span>, <span class="tag">Docker</span>
    </div>
    <div class="cell">
      <span class="tag">CI/CD</span>, <span class="tag">Jenkins</span>, <span class="tag">GitHub Actions</span>, <span class="tag">ADF</span>
    </div>
    <div class="cell">
      <span class="tag">Data Modeling</span>, <span class="tag">ELT/ETL</span>, <span class="tag">KPI Systems</span>
    </div>
  </div>

  <!-- Badges -->
  <div class="badges-section">
    <h2><span>💻</span> Tech Stack</h2>
    <div class="badges-wrap">
      <div class="badge b-python"><span class="badge-icon">🐍</span><span class="badge-label">Python</span></div>
      <div class="badge b-sql"><span class="badge-icon">🗃</span><span class="badge-label">SQL</span></div>
      <div class="badge b-pyspark"><span class="badge-icon">⚡</span><span class="badge-label">PySpark</span></div>
      <div class="badge b-scala"><span class="badge-icon">🔴</span><span class="badge-label">Scala</span></div>
      <div class="badge b-azure"><span class="badge-icon">☁️</span><span class="badge-label">Azure</span></div>
      <div class="badge b-aws"><span class="badge-icon">☁️</span><span class="badge-label">AWS</span></div>
      <div class="badge b-snowflake"><span class="badge-icon">❄️</span><span class="badge-label">Snowflake</span></div>
      <div class="badge b-databricks"><span class="badge-icon">🧱</span><span class="badge-label">Databricks</span></div>
      <div class="badge b-spark"><span class="badge-icon">🔥</span><span class="badge-label">Apache Spark</span></div>
      <div class="badge b-kafka"><span class="badge-icon">📨</span><span class="badge-label">Kafka</span></div>
      <div class="badge b-airflow"><span class="badge-icon">🌀</span><span class="badge-label">Airflow</span></div>
      <div class="badge b-dbt"><span class="badge-icon">🔧</span><span class="badge-label">dbt</span></div>
      <div class="badge b-delta"><span class="badge-icon">Δ</span><span class="badge-label">Delta Lake</span></div>
      <div class="badge b-powerbi"><span class="badge-icon">📊</span><span class="badge-label">Power BI</span></div>
      <div class="badge b-tableau"><span class="badge-icon">📈</span><span class="badge-label">Tableau</span></div>
      <div class="badge b-docker"><span class="badge-icon">🐳</span><span class="badge-label">Docker</span></div>
      <div class="badge b-k8s"><span class="badge-icon">☸️</span><span class="badge-label">Kubernetes</span></div>
      <div class="badge b-jenkins"><span class="badge-icon">🤖</span><span class="badge-label">Jenkins</span></div>
      <div class="badge b-git"><span class="badge-icon">🔀</span><span class="badge-label">Git</span></div>
      <div class="badge b-postgres"><span class="badge-icon">🐘</span><span class="badge-label">PostgreSQL</span></div>
      <div class="badge b-mongodb"><span class="badge-icon">🍃</span><span class="badge-label">MongoDB</span></div>
      <div class="badge b-jira"><span class="badge-icon">📋</span><span class="badge-label">Jira</span></div>
      <div class="badge b-terraform"><span class="badge-icon">🏗</span><span class="badge-label">Terraform</span></div>
    </div>
  </div>

  <!-- Copyable Markdown -->
  <div class="copy-section">
    <div class="copy-header">
      <span>📋 shields.io markdown (for GitHub README)</span>
      <button class="copy-btn" onclick="copyMarkdown()">Copy</button>
    </div>
    <div class="code-block" id="markdown-block"># 🛠 Technical Toolkit

| 🧠 Core Skills | ☁️ Cloud &amp; Platform | ⚙️ Engineering | 📊 Analytics |
|---|---|---|---|
| Data Engineering, Big Data, Distributed Systems | Azure, AWS, Snowflake, Databricks | Spark, Kafka, Airflow, dbt, Delta Lake | Power BI, Tableau, Grafana, QuickSight |
| Python, SQL, PySpark, Scala | Kubernetes, Terraform, Docker | CI/CD, Jenkins, GitHub Actions, ADF | Data Modeling, ELT/ETL, KPI Systems |

💡 I focus on **systems that are scalable, observable, and reliable.**

# 💻 Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&amp;logo=python&amp;logoColor=ffdd54) ![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white) ![PySpark](https://img.shields.io/badge/pyspark-%23E25A1C.svg?style=for-the-badge&amp;logo=apachespark&amp;logoColor=white) ![Scala](https://img.shields.io/badge/scala-%23DC322F.svg?style=for-the-badge&amp;logo=scala&amp;logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&amp;logo=microsoftazure&amp;logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&amp;logo=amazon-aws&amp;logoColor=white) ![Snowflake](https://img.shields.io/badge/snowflake-%2329B5E8.svg?style=for-the-badge&amp;logo=snowflake&amp;logoColor=white) ![Databricks](https://img.shields.io/badge/databricks-%23FF3621.svg?style=for-the-badge&amp;logo=databricks&amp;logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&amp;logo=apachespark&amp;logoColor=black) ![Kafka](https://img.shields.io/badge/kafka-%23231F20.svg?style=for-the-badge&amp;logo=apachekafka&amp;logoColor=white) ![Airflow](https://img.shields.io/badge/airflow-%23017CEE.svg?style=for-the-badge&amp;logo=apacheairflow&amp;logoColor=white) ![dbt](https://img.shields.io/badge/dbt-%23FF694B.svg?style=for-the-badge&amp;logo=dbt&amp;logoColor=white) ![Delta Lake](https://img.shields.io/badge/delta%20lake-%23003366.svg?style=for-the-badge&amp;logo=delta&amp;logoColor=white) ![Power BI](https://img.shields.io/badge/power%20bi-F2C811?style=for-the-badge&amp;logo=powerbi&amp;logoColor=black) ![Tableau](https://img.shields.io/badge/tableau-%23E97627.svg?style=for-the-badge&amp;logo=tableau&amp;logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&amp;logo=docker&amp;logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&amp;logo=kubernetes&amp;logoColor=white) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&amp;logo=jenkins&amp;logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&amp;logo=git&amp;logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&amp;logo=mongodb&amp;logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&amp;logo=jira&amp;logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%237B42BC.svg?style=for-the-badge&amp;logo=terraform&amp;logoColor=white)</div>
  </div>

</div>

<script>
function copyMarkdown() {
  const block = document.getElementById('markdown-block');
  // Decode HTML entities for the clipboard
  const temp = document.createElement('textarea');
  temp.innerHTML = block.textContent;
  const text = temp.value;

  navigator.clipboard.writeText(text).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.textContent = 'Copied!';
    btn.style.background = '#34d399';
    setTimeout(() => {
      btn.textContent = 'Copy';
      btn.style.background = '';
    }, 2000);
  });
}
</script>
</body>
</html>

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=prassu-m&theme=default_repocard&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=prassu-m&theme=default_repocard&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=prassu-m&theme=default_repocard&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=prassu-m&theme=onedark&no-frame=false&no-bg=true&margin-w=4)

---
[![](https://visitcount.itsvg.in/api?id=prassu-m&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
