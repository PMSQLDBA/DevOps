<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DevOps: Basics to Advanced | Complete Guide</title>
<style>
  :root {
    --bg:       #070E1A;
    --surface:  #0C1829;
    --card:     #101E33;
    --border:   #1A3050;
    --cyan:     #00C9FF;
    --amber:    #FFA500;
    --aws:      #FF9900;
    --azure:    #0089D6;
    --green:    #00E676;
    --red:      #FF5252;
    --purple:   #AB47BC;
    --text:     #D8E8F8;
    --muted:    #6A8FAF;
    --heading:  #FFFFFF;
    --badge-aws-bg: rgba(255,153,0,0.15);
    --badge-az-bg:  rgba(0,137,214,0.15);
  }
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.7;
    font-size: 15px;
  }

  /* ── NAV ── */
  nav {
    position: sticky; top: 0; z-index: 100;
    background: rgba(7,14,26,0.95);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--border);
    padding: 0 24px;
    display: flex; align-items: center; gap: 4px;
    flex-wrap: wrap;
    min-height: 52px;
  }
  nav .logo { color: var(--cyan); font-weight: 700; font-size: 16px; margin-right: 20px; white-space: nowrap; }
  nav a {
    color: var(--muted); text-decoration: none; font-size: 13px;
    padding: 6px 10px; border-radius: 6px; transition: all .2s; white-space: nowrap;
  }
  nav a:hover { color: var(--cyan); background: rgba(0,201,255,0.08); }

  /* ── CONTAINER ── */
  .container { max-width: 1200px; margin: 0 auto; padding: 0 24px; }

  /* ── HERO ── */
  .hero {
    background: linear-gradient(135deg, #070E1A 0%, #0A1E38 50%, #070E1A 100%);
    padding: 72px 24px 60px;
    text-align: center;
    border-bottom: 1px solid var(--border);
    position: relative; overflow: hidden;
  }
  .hero::before {
    content: '';
    position: absolute; inset: 0;
    background: radial-gradient(ellipse at 50% 0%, rgba(0,201,255,0.08) 0%, transparent 60%);
    pointer-events: none;
  }
  .hero-badge {
    display: inline-block; background: rgba(0,201,255,0.12);
    border: 1px solid rgba(0,201,255,0.3);
    color: var(--cyan); font-size: 12px; font-weight: 600;
    padding: 4px 14px; border-radius: 20px; margin-bottom: 20px;
    letter-spacing: 1px; text-transform: uppercase;
  }
  .hero h1 {
    font-size: clamp(32px, 5vw, 58px);
    font-weight: 800; color: var(--heading);
    margin-bottom: 16px; line-height: 1.15;
  }
  .hero h1 span { color: var(--cyan); }
  .hero p { font-size: 17px; color: var(--muted); max-width: 640px; margin: 0 auto 36px; }

  /* DevOps infinity loop */
  .infinity-loop {
    display: flex; justify-content: center; align-items: center;
    gap: 0; margin: 0 auto 8px; max-width: 860px; flex-wrap: wrap;
  }
  .loop-phase {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 8px; padding: 8px 14px;
    font-size: 12px; font-weight: 600; color: var(--cyan);
    white-space: nowrap; position: relative;
  }
  .loop-arrow { color: var(--border); font-size: 18px; padding: 0 4px; }
  .loop-phase.dev  { border-color: rgba(0,201,255,0.4); }
  .loop-phase.ops  { border-color: rgba(255,165,0,0.4); color: var(--amber); }
  .loop-phase.sec  { border-color: rgba(0,230,118,0.4); color: var(--green); }

  /* ── SECTIONS ── */
  section { padding: 64px 0; border-bottom: 1px solid var(--border); }
  section:last-of-type { border-bottom: none; }
  .section-label {
    font-size: 11px; font-weight: 700; letter-spacing: 2px;
    text-transform: uppercase; color: var(--cyan); margin-bottom: 10px;
  }
  h2 { font-size: clamp(24px, 3vw, 36px); font-weight: 700; color: var(--heading); margin-bottom: 12px; }
  h3 { font-size: 18px; font-weight: 600; color: var(--heading); margin-bottom: 8px; }
  .subtitle { color: var(--muted); font-size: 15px; margin-bottom: 36px; max-width: 700px; }
  p { margin-bottom: 12px; }

  /* ── CARDS ── */
  .card-grid { display: grid; gap: 20px; }
  .card-grid-2 { grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); }
  .card-grid-3 { grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); }
  .card-grid-4 { grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); }
  .card {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 12px; padding: 24px;
    transition: border-color .2s, transform .2s;
  }
  .card:hover { border-color: rgba(0,201,255,0.3); transform: translateY(-2px); }
  .card-icon { font-size: 28px; margin-bottom: 12px; }
  .card h3 { font-size: 16px; margin-bottom: 8px; }
  .card p { color: var(--muted); font-size: 14px; margin: 0; }
  .card.aws-card  { border-left: 3px solid var(--aws); }
  .card.azure-card { border-left: 3px solid var(--azure); }
  .card.green-card { border-left: 3px solid var(--green); }
  .card.cyan-card  { border-left: 3px solid var(--cyan); }

  /* ── TABLES ── */
  .table-wrap { overflow-x: auto; border-radius: 12px; border: 1px solid var(--border); }
  table { width: 100%; border-collapse: collapse; font-size: 14px; }
  thead th {
    background: #101E33;
    padding: 14px 16px; text-align: left;
    font-size: 12px; font-weight: 700; letter-spacing: 0.8px;
    text-transform: uppercase; color: var(--muted);
    border-bottom: 1px solid var(--border);
    white-space: nowrap;
  }
  tbody tr { border-bottom: 1px solid rgba(26,48,80,0.6); transition: background .15s; }
  tbody tr:last-child { border-bottom: none; }
  tbody tr:hover { background: rgba(0,201,255,0.04); }
  tbody td { padding: 13px 16px; vertical-align: top; }
  td.cat  { color: var(--muted); font-size: 12px; font-weight: 600; white-space: nowrap; }
  td.tool { font-weight: 600; color: var(--heading); white-space: nowrap; }
  td.desc { color: var(--text); line-height: 1.5; }
  td.use  { color: var(--muted); font-size: 13px; line-height: 1.5; }

  /* badges */
  .badge {
    display: inline-block; border-radius: 4px;
    padding: 2px 8px; font-size: 11px; font-weight: 700;
    text-transform: uppercase; letter-spacing: 0.5px; white-space: nowrap;
  }
  .badge-aws   { background: var(--badge-aws-bg); color: var(--aws); border: 1px solid rgba(255,153,0,0.3); }
  .badge-azure { background: var(--badge-az-bg);  color: var(--azure); border: 1px solid rgba(0,137,214,0.3); }
  .badge-both  { background: rgba(0,230,118,0.1); color: var(--green); border: 1px solid rgba(0,230,118,0.3); }
  .badge-free  { background: rgba(171,71,188,0.1); color: var(--purple); border: 1px solid rgba(171,71,188,0.3); }

  /* ── COMPARISON TABLE ── */
  .compare-table th:first-child { width: 160px; }
  .compare-table td.old { color: #FF6B6B; }
  .compare-table td.new { color: var(--green); }
  .compare-table .label { font-weight: 600; color: var(--heading); font-size: 13px; }

  /* ── LIFECYCLE ── */
  .lifecycle {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 2px;
    border: 1px solid var(--border); border-radius: 12px; overflow: hidden;
  }
  .lc-phase {
    background: var(--card); padding: 20px;
    display: flex; flex-direction: column; gap: 6px;
    border-right: 1px solid var(--border);
    position: relative;
  }
  .lc-phase:last-child { border-right: none; }
  .lc-num { font-size: 11px; color: var(--muted); font-weight: 700; letter-spacing: 1px; }
  .lc-name { font-size: 15px; font-weight: 700; color: var(--heading); }
  .lc-desc { font-size: 13px; color: var(--muted); line-height: 1.5; }
  .lc-tool { font-size: 12px; color: var(--cyan); margin-top: 4px; }
  .lc-phase:nth-child(1) .lc-name { color: #AB47BC; }
  .lc-phase:nth-child(2) .lc-name { color: #42A5F5; }
  .lc-phase:nth-child(3) .lc-name { color: #26C6DA; }
  .lc-phase:nth-child(4) .lc-name { color: #66BB6A; }
  .lc-phase:nth-child(5) .lc-name { color: #FFA726; }
  .lc-phase:nth-child(6) .lc-name { color: #EF5350; }
  .lc-phase:nth-child(7) .lc-name { color: #EC407A; }
  .lc-phase:nth-child(8) .lc-name { color: #7E57C2; }

  /* ── LEVELS ── */
  .levels { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
  .level { background: var(--card); border: 1px solid var(--border); border-radius: 12px; overflow: hidden; }
  .level-header { padding: 16px 20px; font-weight: 700; font-size: 15px; display: flex; align-items: center; gap: 10px; }
  .level-header.beginner { background: linear-gradient(135deg, #1B3A2F, #1E3A2A); color: var(--green); }
  .level-header.intermediate { background: linear-gradient(135deg, #1A3050, #1C3560); color: var(--cyan); }
  .level-header.advanced { background: linear-gradient(135deg, #2A1A40, #321A48); color: #AB47BC; }
  .level-body { padding: 16px 20px; }
  .level-body ul { list-style: none; display: flex; flex-direction: column; gap: 8px; }
  .level-body li { font-size: 13.5px; color: var(--text); display: flex; align-items: flex-start; gap: 8px; }
  .level-body li::before { content: '▸'; color: var(--muted); flex-shrink: 0; margin-top: 1px; }

  /* ── JOB MARKET ── */
  .market-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; }
  @media(max-width: 800px) { .market-grid { grid-template-columns: 1fr; } }
  .market-card { background: var(--card); border: 1px solid var(--border); border-radius: 12px; overflow: hidden; }
  .market-header {
    padding: 14px 20px; font-weight: 700; font-size: 15px;
    display: flex; align-items: center; gap: 10px;
  }
  .market-header.india { background: linear-gradient(135deg, #1A2A1A, #1C341C); color: #FF9933; }
  .market-header.usa   { background: linear-gradient(135deg, #1A1A2E, #1C1C3A); color: #4FC3F7; }
  .market-card .table-wrap { border: none; border-radius: 0; }
  .salary-high { color: var(--green); font-weight: 600; font-size: 13px; }
  .salary-low  { color: var(--amber); font-weight: 600; font-size: 13px; }
  .exp-tag { color: var(--muted); font-size: 12px; }

  /* ── ROADMAP ── */
  .roadmap { display: flex; flex-direction: column; gap: 0; position: relative; }
  .roadmap::before {
    content: ''; position: absolute; left: 20px; top: 24px; bottom: 24px;
    width: 2px; background: linear-gradient(to bottom, var(--cyan), var(--purple));
  }
  .rm-step { display: flex; gap: 24px; padding: 0 0 28px 0; position: relative; }
  .rm-dot {
    width: 42px; height: 42px; border-radius: 50%;
    background: var(--card); border: 2px solid var(--cyan);
    display: flex; align-items: center; justify-content: center;
    font-weight: 800; color: var(--cyan); font-size: 14px;
    flex-shrink: 0; z-index: 1;
  }
  .rm-dot.done   { border-color: var(--green); color: var(--green); }
  .rm-dot.purple { border-color: var(--purple); color: var(--purple); }
  .rm-content { background: var(--card); border: 1px solid var(--border); border-radius: 12px; padding: 20px; flex: 1; }
  .rm-month { font-size: 11px; color: var(--muted); font-weight: 700; letter-spacing: 1px; text-transform: uppercase; margin-bottom: 4px; }
  .rm-title { font-size: 16px; font-weight: 700; color: var(--heading); margin-bottom: 8px; }
  .rm-items { display: flex; flex-wrap: wrap; gap: 8px; }
  .rm-tag {
    background: rgba(0,201,255,0.1); border: 1px solid rgba(0,201,255,0.2);
    color: var(--cyan); font-size: 12px; font-weight: 600;
    padding: 3px 10px; border-radius: 20px;
  }
  .rm-tag.green  { background: rgba(0,230,118,0.1); border-color: rgba(0,230,118,0.2); color: var(--green); }
  .rm-tag.purple { background: rgba(171,71,188,0.1); border-color: rgba(171,71,188,0.2); color: var(--purple); }
  .rm-tag.amber  { background: rgba(255,165,0,0.1);  border-color: rgba(255,165,0,0.2);  color: var(--amber); }

  /* ── UTILITY ── */
  .text-center { text-align: center; }
  .mt-8  { margin-top: 8px; }
  .mt-16 { margin-top: 16px; }
  .mt-24 { margin-top: 24px; }
  .mt-32 { margin-top: 32px; }
  .mb-24 { margin-bottom: 24px; }
  .tag-row { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px; }
  .info-box {
    background: rgba(0,201,255,0.06); border: 1px solid rgba(0,201,255,0.2);
    border-radius: 10px; padding: 18px 20px; margin-top: 24px;
  }
  .info-box p { margin: 0; font-size: 14px; color: var(--text); }
  .info-box strong { color: var(--cyan); }
  .highlight { color: var(--cyan); font-weight: 600; }
  .divider { border: none; border-top: 1px solid var(--border); margin: 32px 0; }
  @media(max-width: 600px) {
    .lifecycle { grid-template-columns: 1fr 1fr; }
    .lc-phase { border-bottom: 1px solid var(--border); border-right: none; }
    .loop-phase { font-size: 11px; padding: 6px 10px; }
  }
  .concept-block { display: flex; flex-direction: column; gap: 24px; }
  .concept {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 10px; padding: 22px;
    display: flex; gap: 18px; align-items: flex-start;
  }
  .concept-num {
    width: 36px; height: 36px; border-radius: 8px;
    background: rgba(0,201,255,0.1); color: var(--cyan);
    display: flex; align-items: center; justify-content: center;
    font-weight: 800; font-size: 14px; flex-shrink: 0;
  }
  .concept-body h3 { font-size: 16px; margin-bottom: 6px; }
  .concept-body p  { font-size: 14px; color: var(--muted); margin: 0; }
  .concept-body .analogy { font-size: 13px; color: rgba(0,201,255,0.8); margin-top: 8px; font-style: italic; }
  footer {
    background: var(--surface); border-top: 1px solid var(--border);
    text-align: center; padding: 32px 24px;
    font-size: 13px; color: var(--muted);
  }
  footer strong { color: var(--cyan); }
</style>
</head>
<body>

<!-- ═══ NAVIGATION ═══ -->
<nav>
  <span class="logo">⚙ DevOps Guide</span>
  <a href="#what">What is DevOps</a>
  <a href="#lifecycle">Lifecycle</a>
  <a href="#concepts">Core Concepts</a>
  <a href="#levels">Skill Levels</a>
  <a href="#aws-tools">AWS Tools</a>
  <a href="#azure-tools">Azure Tools</a>
  <a href="#common-tools">Common Tools</a>
  <a href="#jobs">Job Market</a>
  <a href="#roadmap">Roadmap</a>
</nav>

<!-- ═══ HERO ═══ -->
<div class="hero">
  <div class="hero-badge">Beginner to Advanced Guide</div>
  <h1>Everything About <span>DevOps</span></h1>
  <p>A complete, jargon-free guide covering what DevOps is, the tools used in AWS &amp; Azure, and what the job market looks like in India and the USA.</p>
  <div class="infinity-loop">
    <div class="loop-phase dev">📋 Plan</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase dev">💻 Code</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase dev">🔨 Build</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase sec">🧪 Test</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase ops">🚀 Release</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase ops">☁ Deploy</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase ops">⚙ Operate</div>
    <div class="loop-arrow">→</div>
    <div class="loop-phase sec">📊 Monitor</div>
    <div class="loop-arrow" style="color:var(--cyan)">↺</div>
  </div>
  <p style="font-size:13px;color:var(--muted);margin-top:12px">The DevOps Infinity Loop — continuous cycle of development and operations</p>
</div>


<!-- ═══ SECTION 1: WHAT IS DEVOPS ═══ -->
<section id="what">
<div class="container">
  <div class="section-label">Chapter 01</div>
  <h2>What Exactly is DevOps?</h2>
  <p class="subtitle">Let's start from zero — no jargon, just plain English.</p>

  <div class="info-box">
    <p>
      <strong>Simple Definition:</strong> DevOps is a set of practices, tools, and a cultural philosophy that combines
      <strong>Development (Dev)</strong> — writing software code — and
      <strong>Operations (Ops)</strong> — deploying, running, and maintaining that software —
      into a single, continuous, collaborative process.
      <br><br>
      The goal is to <strong>deliver software faster, more reliably, and with fewer failures</strong> by breaking down the wall between the people who build software and the people who run it.
    </p>
  </div>

  <hr class="divider">
  <h3 style="margin-bottom:20px">Traditional IT vs DevOps</h3>
  <div class="table-wrap">
    <table class="compare-table">
      <thead>
        <tr>
          <th>Area</th>
          <th>❌ Traditional IT (Old Way)</th>
          <th>✅ DevOps (New Way)</th>
        </tr>
      </thead>
      <tbody>
        <tr><td class="label">Team Structure</td><td class="old">Dev and Ops are separate silos — they rarely talk</td><td class="new">Dev, Ops, QA, Security work together as one team</td></tr>
        <tr><td class="label">Release Frequency</td><td class="old">Software released every 6–12 months</td><td class="new">Multiple releases per day (continuous delivery)</td></tr>
        <tr><td class="label">Deployment</td><td class="old">Manual, error-prone, done by hand</td><td class="new">Automated pipelines — one click or automatic trigger</td></tr>
        <tr><td class="label">Testing</td><td class="old">Done at the very end, after coding is complete</td><td class="new">Continuous — automated tests run on every code change</td></tr>
        <tr><td class="label">Infrastructure</td><td class="old">Manually configured physical servers</td><td class="new">Provisioned via code (IaC) — automated and repeatable</td></tr>
        <tr><td class="label">Feedback Loop</td><td class="old">Bugs found months after writing code</td><td class="new">Bugs caught within minutes via automated monitoring</td></tr>
        <tr><td class="label">Failure Response</td><td class="old">Hours/days of downtime — manual recovery</td><td class="new">Auto-healing, rollbacks in seconds</td></tr>
        <tr><td class="label">Collaboration</td><td class="old">Blame culture — dev blames ops, ops blames dev</td><td class="new">Shared responsibility — everyone owns the product</td></tr>
      </tbody>
    </table>
  </div>

  <hr class="divider">
  <h3 style="margin-bottom:20px">The 4 Core Pillars of DevOps (CALMS)</h3>
  <div class="card-grid card-grid-4">
    <div class="card cyan-card">
      <div class="card-icon">🤝</div>
      <h3>Culture</h3>
      <p>Break silos between Dev, Ops, QA. Everyone shares responsibility for delivery and reliability. No blame — shared ownership.</p>
    </div>
    <div class="card green-card">
      <div class="card-icon">🤖</div>
      <h3>Automation</h3>
      <p>Automate everything: testing, deployments, infrastructure provisioning, security scans. If it's manual, automate it.</p>
    </div>
    <div class="card aws-card">
      <div class="card-icon">📉</div>
      <h3>Lean</h3>
      <p>Eliminate waste. Deliver small, frequent improvements. Focus on customer value. Cut unnecessary processes.</p>
    </div>
    <div class="card azure-card">
      <div class="card-icon">📊</div>
      <h3>Measurement</h3>
      <p>Measure everything — deployment frequency, failure rates, recovery time (DORA metrics). Data drives decisions.</p>
    </div>
  </div>

  <div class="mt-24 info-box">
    <p><strong>Real-world analogy:</strong> Think of a restaurant kitchen. DevOps is like having the chef (developer) and the waiter (operations) work together seamlessly — the chef cooks, the waiter delivers, they both handle customer feedback, and they constantly improve the process. In old IT, the chef just throws food over a wall and hopes the waiter delivers it correctly. That's the problem DevOps solves.</p>
  </div>
</div>
</section>


<!-- ═══ SECTION 2: LIFECYCLE ═══ -->
<section id="lifecycle">
<div class="container">
  <div class="section-label">Chapter 02</div>
  <h2>The DevOps Lifecycle — 8 Phases</h2>
  <p class="subtitle">DevOps follows an infinite loop of 8 phases, repeating continuously for every feature or fix.</p>

  <div class="lifecycle">
    <div class="lc-phase">
      <div class="lc-num">PHASE 01</div>
      <div class="lc-name">📋 Plan</div>
      <div class="lc-desc">Define what to build, break it into tasks, estimate effort, and prioritize using Agile sprints.</div>
      <div class="lc-tool">Tools: Jira, Azure Boards, Trello, GitHub Issues</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 02</div>
      <div class="lc-name">💻 Code</div>
      <div class="lc-desc">Developers write code, collaborate via version control (Git), and follow branching strategies.</div>
      <div class="lc-tool">Tools: Git, GitHub, GitLab, Bitbucket, VS Code</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 03</div>
      <div class="lc-name">🔨 Build</div>
      <div class="lc-desc">Code is compiled, dependencies are resolved, and a deployable artifact (JAR, Docker image) is created automatically.</div>
      <div class="lc-tool">Tools: Maven, Gradle, npm, Docker, AWS CodeBuild</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 04</div>
      <div class="lc-name">🧪 Test</div>
      <div class="lc-desc">Automated tests (unit, integration, security) run on every code change. Failures block deployments.</div>
      <div class="lc-tool">Tools: JUnit, Selenium, SonarQube, Snyk, Cypress</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 05</div>
      <div class="lc-name">🚀 Release</div>
      <div class="lc-desc">A tested, approved artifact is packaged and versioned. Release pipelines are triggered for deployment.</div>
      <div class="lc-tool">Tools: AWS CodePipeline, Azure Pipelines, Jenkins, ArgoCD</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 06</div>
      <div class="lc-name">☁ Deploy</div>
      <div class="lc-desc">The artifact is automatically deployed to servers/containers using strategies like Blue-Green or Canary.</div>
      <div class="lc-tool">Tools: AWS CodeDeploy, Helm, Kubernetes, Terraform</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 07</div>
      <div class="lc-name">⚙ Operate</div>
      <div class="lc-desc">The running application is managed — scaling, patching, config changes. Infrastructure is maintained.</div>
      <div class="lc-tool">Tools: Kubernetes, AWS ECS, Ansible, AWS Systems Manager</div>
    </div>
    <div class="lc-phase">
      <div class="lc-num">PHASE 08</div>
      <div class="lc-name">📊 Monitor</div>
      <div class="lc-desc">Application health, performance, and errors are tracked. Alerts fire on anomalies. Insights feed back into planning.</div>
      <div class="lc-tool">Tools: CloudWatch, Prometheus, Grafana, Datadog, ELK Stack</div>
    </div>
  </div>

  <div class="mt-24 info-box">
    <p><strong>Key Insight:</strong> After Phase 08 (Monitor), you loop back to Phase 01 (Plan). This is the "infinity loop" of DevOps — it never stops. The feedback from monitoring drives the next sprint's planning. This cycle is why companies using DevOps can release software hundreds of times per day while maintaining stability.</p>
  </div>
</div>
</section>


<!-- ═══ SECTION 3: CORE CONCEPTS ═══ -->
<section id="concepts">
<div class="container">
  <div class="section-label">Chapter 03</div>
  <h2>Core Concepts You Must Know</h2>
  <p class="subtitle">These are the fundamental building blocks of DevOps. Master these concepts before diving into tools.</p>

  <div class="concept-block">
    <div class="concept">
      <div class="concept-num">1</div>
      <div class="concept-body">
        <h3>CI — Continuous Integration</h3>
        <p>Every developer merges their code to a shared branch multiple times a day. Each merge automatically triggers a build and runs tests. This ensures code always works together and bugs are caught immediately — not weeks later.</p>
        <p class="analogy">🍳 Analogy: Multiple chefs all adding ingredients to the same pot as they cook, tasting it continuously — rather than everyone adding everything at the end and hoping it tastes good.</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">2</div>
      <div class="concept-body">
        <h3>CD — Continuous Delivery &amp; Continuous Deployment</h3>
        <p><strong>Continuous Delivery</strong>: Every successful code change is automatically built, tested, and made ready to deploy to production — but a human still approves the final release.
        <br><strong>Continuous Deployment</strong>: Goes one step further — every successful change is automatically deployed to production with NO human intervention. Used by companies like Netflix, Amazon.</p>
        <p class="analogy">🚚 Analogy: A factory conveyor belt — products (features) move from assembly (code) → inspection (testing) → ready to ship (CD) → on the truck automatically (continuous deployment).</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">3</div>
      <div class="concept-body">
        <h3>IaC — Infrastructure as Code</h3>
        <p>Instead of manually clicking buttons to set up servers, databases, and networks, you write code (scripts/templates) that creates and configures your entire infrastructure automatically. It's version-controlled, repeatable, and auditable.</p>
        <p class="analogy">🏗️ Analogy: Instead of a builder manually laying every brick by hand, they use a blueprint (code) and a machine does the rest — consistently, every time. Tools: Terraform, AWS CloudFormation, Azure Bicep.</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">4</div>
      <div class="concept-body">
        <h3>Containerization (Docker)</h3>
        <p>A container is a lightweight, self-contained package that includes your application AND everything it needs to run (code, runtime, libraries, settings). Containers run identically on any machine — developer laptop, test server, or production cloud.</p>
        <p class="analogy">📦 Analogy: A shipping container — the goods inside are packed with everything they need, and they can be moved between ships, trains, or trucks and they always work the same way. Docker is the most popular container tool.</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">5</div>
      <div class="concept-body">
        <h3>Container Orchestration (Kubernetes)</h3>
        <p>When you have hundreds of containers running, you need something to manage them — starting, stopping, scaling, networking, and healing them automatically. Kubernetes (K8s) is the industry-standard orchestrator that does all of this at scale.</p>
        <p class="analogy">🎼 Analogy: Kubernetes is the conductor of an orchestra. Each musician (container) plays their part, and the conductor ensures they start on time, stay in sync, replaces anyone who stops playing, and scales the orchestra up or down as needed.</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">6</div>
      <div class="concept-body">
        <h3>Configuration Management</h3>
        <p>Tools that automatically configure and maintain the desired state of your servers. Instead of manually logging into 500 servers to install software, you write a playbook/recipe and the tool applies it to all servers simultaneously.</p>
        <p class="analogy">⚙️ Tools: Ansible (most popular, agentless), Chef, Puppet, AWS Systems Manager. These ensure all your servers are always in the correct state — "configuration drift" is automatically corrected.</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">7</div>
      <div class="concept-body">
        <h3>Monitoring &amp; Observability</h3>
        <p>After deploying software, you need to know if it's healthy. Monitoring tracks metrics (CPU, memory, request rate). Logging captures what happened. Tracing shows the journey of a request through multiple services. Together, these give you full observability into your system.</p>
        <p class="analogy">🔬 Three pillars: <strong>Metrics</strong> (numbers — CPU 85%, response time 200ms), <strong>Logs</strong> (events — "Error: database connection failed"), <strong>Traces</strong> (journey — request took 500ms: 100ms in API, 400ms in database).</p>
      </div>
    </div>
    <div class="concept">
      <div class="concept-num">8</div>
      <div class="concept-body">
        <h3>DevSecOps — Security Built In</h3>
        <p>Traditionally, security was checked at the very end before release ("bolt-on security"). DevSecOps shifts security <em>left</em> — integrating security checks at every stage of the pipeline: code scanning, dependency vulnerability checks, container image scanning, and infrastructure security policies — automatically, in the CI/CD pipeline.</p>
        <p class="analogy">🛡️ "Shift Left" means moving security earlier in the process. Tools: SonarQube (code quality), Snyk (vulnerability scanning), Trivy (container scanning), HashiCorp Vault (secrets management), AWS Security Hub, Microsoft Defender.</p>
      </div>
    </div>
  </div>
</div>
</section>


<!-- ═══ SECTION 4: SKILL LEVELS ═══ -->
<section id="levels">
<div class="container">
  <div class="section-label">Chapter 04</div>
  <h2>DevOps Skill Levels</h2>
  <p class="subtitle">DevOps expertise is typically grouped into three progressive levels. Here's what you need to know at each stage.</p>

  <div class="levels">
    <div class="level">
      <div class="level-header beginner">🌱 Beginner (0–1 Year)</div>
      <div class="level-body">
        <ul>
          <li>Understand Linux command line basics (files, permissions, processes, networking)</li>
          <li>Learn Git: clone, commit, push, pull, branching, merge</li>
          <li>Understand the software development lifecycle (SDLC)</li>
          <li>Learn basic shell scripting (Bash)</li>
          <li>Understand what CI/CD means and why it matters</li>
          <li>Learn Docker basics: build images, run containers, write Dockerfiles</li>
          <li>Set up a simple Jenkins or GitHub Actions pipeline</li>
          <li>Understand cloud basics: what is a VM, storage, networking (AWS EC2 / Azure VM)</li>
          <li>Learn about Agile methodology, sprints, and Jira</li>
          <li>Understand the difference between Dev, QA, and Ops roles</li>
        </ul>
      </div>
    </div>
    <div class="level">
      <div class="level-header intermediate">⚡ Intermediate (1–3 Years)</div>
      <div class="level-body">
        <ul>
          <li>Build multi-stage CI/CD pipelines with approvals, rollbacks, and notifications</li>
          <li>Write Terraform or CloudFormation to provision cloud infrastructure</li>
          <li>Learn Kubernetes: Pods, Deployments, Services, Ingress, ConfigMaps, Secrets</li>
          <li>Master Docker Compose for multi-container applications</li>
          <li>Automate server configuration with Ansible playbooks</li>
          <li>Set up monitoring with Prometheus + Grafana dashboards</li>
          <li>Implement ELK Stack (Elasticsearch, Logstash, Kibana) for centralized logging</li>
          <li>Work with AWS services: EKS, ECR, CodePipeline, CloudWatch, S3, RDS</li>
          <li>Work with Azure services: AKS, ACR, Azure Pipelines, Monitor, Key Vault</li>
          <li>Learn GitOps (ArgoCD, Flux) — Git as the source of truth for infra</li>
          <li>Integrate security scanning into pipelines (SonarQube, Snyk, Trivy)</li>
          <li>Understand Blue-Green and Canary deployment strategies</li>
        </ul>
      </div>
    </div>
    <div class="level">
      <div class="level-header advanced">🔥 Advanced (3+ Years)</div>
      <div class="level-body">
        <ul>
          <li>Design and architect enterprise CI/CD platforms at scale (hundreds of pipelines)</li>
          <li>Multi-cloud and hybrid-cloud infrastructure design with Terraform modules</li>
          <li>Kubernetes advanced: Custom Resource Definitions (CRDs), Operators, Helm charts</li>
          <li>SRE (Site Reliability Engineering): SLIs, SLOs, SLAs, error budgets, toil reduction</li>
          <li>FinOps: cloud cost optimization, reserved instances, rightsizing</li>
          <li>Advanced observability: distributed tracing (Jaeger, AWS X-Ray), chaos engineering</li>
          <li>DevSecOps at scale: SAST, DAST, SCA, container image policy enforcement (OPA/Gatekeeper)</li>
          <li>Platform Engineering: build internal developer platforms (IDPs) using Backstage</li>
          <li>Service mesh implementation (Istio, Linkerd) for microservices communication</li>
          <li>Compliance automation: SOC 2, PCI-DSS, ISO 27001 controls in pipelines</li>
          <li>Incident management: runbooks, post-mortems, blameless culture</li>
          <li>Lead and mentor junior DevOps engineers, define DevOps strategy</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</section>


<!-- ═══ SECTION 5: AWS TOOLS ═══ -->
<section id="aws-tools">
<div class="container">
  <div class="section-label">Chapter 05</div>
  <h2>🟠 AWS DevOps Tools — Complete Reference</h2>
  <p class="subtitle">Amazon Web Services (AWS) provides a comprehensive suite of native DevOps services. These are the most important ones used in production environments today.</p>

  <div class="table-wrap">
    <table>
      <thead>
        <tr>
          <th>Category</th>
          <th>AWS Tool / Service</th>
          <th>What It Does</th>
          <th>Common Use Case</th>
        </tr>
      </thead>
      <tbody>
        <!-- Source Control -->
        <tr>
          <td class="cat">Source Control</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CodeCommit</td>
          <td class="desc">Fully managed, private Git repository service hosted on AWS. Highly available, encrypted at rest, integrates natively with other AWS services.</td>
          <td class="use">Store and version your application source code; trigger CodePipeline on every commit</td>
        </tr>
        <!-- CI/CD -->
        <tr>
          <td class="cat">CI/CD — Orchestration</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CodePipeline</td>
          <td class="desc">Fully managed continuous delivery pipeline that orchestrates the entire release workflow — from source code changes to production deployment. Connects CodeCommit, CodeBuild, CodeDeploy, and third-party tools.</td>
          <td class="use">Automate the full release pipeline: code change → build → test → deploy to production</td>
        </tr>
        <tr>
          <td class="cat">CI/CD — Build</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CodeBuild</td>
          <td class="desc">Managed build service that compiles source code, runs tests, and produces deployable artifacts. Scales automatically — no build servers to manage. Uses buildspec.yml to define build steps.</td>
          <td class="use">Compile Java/Node.js/Python apps, run unit tests, build Docker images, run SonarQube scans</td>
        </tr>
        <tr>
          <td class="cat">CI/CD — Deploy</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CodeDeploy</td>
          <td class="desc">Automated deployment service that deploys applications to EC2 instances, Lambda functions, ECS containers, or on-premises servers. Supports Blue/Green and In-place deployment strategies with automatic rollback on failure.</td>
          <td class="use">Zero-downtime deployments to EC2 fleets; Blue-Green deployments to ECS; Lambda version deployments</td>
        </tr>
        <tr>
          <td class="cat">CI/CD — Platform</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CodeStar</td>
          <td class="desc">Unified interface to manage software development activities on AWS — combines CodeCommit, CodeBuild, CodeDeploy, and CodePipeline with a project dashboard. Good for quick project setup.</td>
          <td class="use">Rapid project bootstrapping with pre-configured CI/CD pipelines and team collaboration</td>
        </tr>
        <!-- Containers -->
        <tr>
          <td class="cat">Container Registry</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>Amazon ECR</td>
          <td class="desc">Fully managed Docker container registry — store, manage, and deploy container images securely. Integrated with ECS and EKS. Supports image vulnerability scanning and lifecycle policies to auto-delete old images.</td>
          <td class="use">Store Docker images built by CodeBuild; pull images for ECS/EKS deployments</td>
        </tr>
        <tr>
          <td class="cat">Container Service</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>Amazon ECS</td>
          <td class="desc">Managed container orchestration service — run Docker containers on AWS without managing cluster infrastructure (when using Fargate). Simpler than Kubernetes, ideal for teams that don't need full K8s complexity.</td>
          <td class="use">Run microservices as containers; auto-scale containerized APIs; event-driven processing with SQS</td>
        </tr>
        <tr>
          <td class="cat">Kubernetes</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>Amazon EKS</td>
          <td class="desc">Fully managed Kubernetes control plane — AWS manages the master nodes, you manage worker nodes (or use Fargate for serverless K8s). Integrates with IAM, VPC, ECR, and ALB natively.</td>
          <td class="use">Large-scale microservices platforms; stateful workloads; multi-team Kubernetes clusters</td>
        </tr>
        <!-- IaC -->
        <tr>
          <td class="cat">Infrastructure as Code</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CloudFormation</td>
          <td class="desc">AWS-native IaC service. Define your entire AWS infrastructure (VPCs, EC2, RDS, S3, IAM) in JSON or YAML templates. AWS manages creating, updating, and deleting resources (called stacks) in the correct order.</td>
          <td class="use">Provision entire AWS environments from a template; manage infrastructure as code with drift detection</td>
        </tr>
        <tr>
          <td class="cat">Infrastructure as Code</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CDK</td>
          <td class="desc">AWS Cloud Development Kit — define AWS infrastructure using real programming languages (TypeScript, Python, Java, Go) instead of YAML/JSON. CDK generates CloudFormation templates. Loved by developers.</td>
          <td class="use">Developer-friendly IaC using Python or TypeScript; reusable infrastructure constructs across teams</td>
        </tr>
        <!-- Configuration -->
        <tr>
          <td class="cat">Configuration Mgmt</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS Systems Manager (SSM)</td>
          <td class="desc">Comprehensive management service for EC2 and on-premises servers. Run commands remotely (Session Manager — no SSH needed), manage patches (Patch Manager), store parameters (Parameter Store), automate tasks (Automation Runbooks).</td>
          <td class="use">Patch all EC2 instances automatically; store DB passwords securely; run scripts on 1000s of servers at once</td>
        </tr>
        <tr>
          <td class="cat">Configuration Mgmt</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS Config</td>
          <td class="desc">Continuously monitors and records your AWS resource configurations. Evaluates resources against compliance rules. Tracks configuration changes over time — great for audit trails and compliance (SOC 2, PCI-DSS).</td>
          <td class="use">Compliance auditing; detect when S3 buckets become public; track who changed what and when</td>
        </tr>
        <!-- Monitoring -->
        <tr>
          <td class="cat">Monitoring &amp; Logging</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>Amazon CloudWatch</td>
          <td class="desc">AWS's core monitoring service. Collects metrics (CPU, memory, custom), logs (CloudWatch Logs), events, and creates alarms that trigger actions (scale, notify). Also includes CloudWatch Insights for log querying and CloudWatch Dashboards.</td>
          <td class="use">Alert on high CPU; auto-scale EC2 based on metrics; query application logs; create operational dashboards</td>
        </tr>
        <tr>
          <td class="cat">Distributed Tracing</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS X-Ray</td>
          <td class="desc">Distributed tracing service that helps you analyze and debug microservices applications. Visualizes the full request journey across all services, identifies bottlenecks, and shows which service is causing latency or errors.</td>
          <td class="use">Debug why a request is slow across 5 microservices; find which Lambda is causing latency spikes</td>
        </tr>
        <!-- Security -->
        <tr>
          <td class="cat">Identity &amp; Access</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS IAM</td>
          <td class="desc">Identity and Access Management — control who (users, roles, services) can do what (actions) on which AWS resources. Every DevOps engineer must master IAM. Principle of least privilege is enforced here. Includes policies, roles, and federated identity.</td>
          <td class="use">Grant CodeBuild permission to push to ECR; restrict developer access to production; cross-account access</td>
        </tr>
        <tr>
          <td class="cat">Secrets Management</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS Secrets Manager</td>
          <td class="desc">Securely store and automatically rotate secrets like database passwords, API keys, and OAuth tokens. Applications retrieve secrets at runtime via API — no hardcoded credentials in code or environment variables.</td>
          <td class="use">Store RDS database passwords; rotate credentials automatically every 30 days; inject secrets into ECS containers</td>
        </tr>
        <tr>
          <td class="cat">Key Management</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS KMS</td>
          <td class="desc">Key Management Service — create and manage cryptographic keys used to encrypt your data across AWS services (S3, EBS, RDS, Secrets Manager). Audit key usage via CloudTrail for compliance requirements.</td>
          <td class="use">Encrypt S3 buckets, EBS volumes, and RDS databases; meet compliance encryption requirements</td>
        </tr>
        <tr>
          <td class="cat">Security Posture</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS Security Hub</td>
          <td class="desc">Centralized security findings dashboard that aggregates alerts from GuardDuty, Inspector, Macie, Config, and third-party tools. Provides a security score and prioritized list of issues to fix. Great for DevSecOps teams.</td>
          <td class="use">Centralized security visibility; compliance scoring against CIS Benchmarks; automated remediation workflows</td>
        </tr>
        <!-- Artifacts -->
        <tr>
          <td class="cat">Artifact Management</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS CodeArtifact</td>
          <td class="desc">Fully managed artifact repository for software packages — npm, PyPI, Maven, NuGet. Teams publish packages internally and pull approved packages from public repos through CodeArtifact (proxy), allowing you to control which external packages are used.</td>
          <td class="use">Private npm/Maven package registry; audit and control open-source dependencies; share internal libraries</td>
        </tr>
        <!-- Serverless -->
        <tr>
          <td class="cat">Serverless Compute</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS Lambda</td>
          <td class="desc">Run code without managing servers. Lambda executes functions in response to events (API call, S3 upload, DynamoDB change, scheduled trigger). Scales automatically from 0 to millions of invocations. Pay only for execution time.</td>
          <td class="use">Serverless API backends; automated remediation scripts; event-driven pipeline triggers; cron jobs in the cloud</td>
        </tr>
        <!-- Load Balancing -->
        <tr>
          <td class="cat">Load Balancing</td>
          <td class="tool"><span class="badge badge-aws">AWS</span><br>AWS ALB / NLB</td>
          <td class="desc">Application Load Balancer (ALB) — routes HTTP/S traffic to ECS/EKS containers, EC2 instances, or Lambda based on rules (path, host, header). Network Load Balancer (NLB) — ultra-low latency for TCP/UDP traffic.</td>
          <td class="use">Route traffic between Blue-Green deployments; Kubernetes Ingress via AWS Load Balancer Controller</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
</section>


<!-- ═══ SECTION 6: AZURE TOOLS ═══ -->
<section id="azure-tools">
<div class="container">
  <div class="section-label">Chapter 06</div>
  <h2>🔵 Azure DevOps Tools — Complete Reference</h2>
  <p class="subtitle">Microsoft Azure has one of the most comprehensive DevOps platforms in the market, centered around Azure DevOps Services — an all-in-one suite that covers the full software delivery lifecycle.</p>

  <div class="info-box mt-16 mb-24">
    <p><strong>Azure DevOps (the platform)</strong> is a single product that bundles five services: Azure Boards (planning), Azure Repos (code), Azure Pipelines (CI/CD), Azure Test Plans (testing), and Azure Artifacts (packages). Many organizations use this end-to-end without any third-party tools.</p>
  </div>

  <div class="table-wrap">
    <table>
      <thead>
        <tr>
          <th>Category</th>
          <th>Azure Tool / Service</th>
          <th>What It Does</th>
          <th>Common Use Case</th>
        </tr>
      </thead>
      <tbody>
        <!-- DevOps Platform -->
        <tr>
          <td class="cat">DevOps Platform</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure DevOps Services</td>
          <td class="desc">Microsoft's all-in-one DevOps platform — integrates planning (Boards), source control (Repos), CI/CD (Pipelines), testing (Test Plans), and package management (Artifacts) in one cloud-hosted service. Works with any language, cloud, or operating system.</td>
          <td class="use">End-to-end DevOps for enterprise teams; .NET, Java, Node.js, Python projects; hybrid and multi-cloud environments</td>
        </tr>
        <!-- Source Control -->
        <tr>
          <td class="cat">Source Control</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Repos</td>
          <td class="desc">Free, unlimited private Git repositories within Azure DevOps. Supports both Git and the legacy TFVC (Team Foundation Version Control). Includes pull request workflows, branch policies (require approvals, block force push), and code search.</td>
          <td class="use">Host application code; enforce branch protection rules; manage pull request reviews; trigger Azure Pipelines on commit</td>
        </tr>
        <!-- CI/CD -->
        <tr>
          <td class="cat">CI/CD Pipelines</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Pipelines</td>
          <td class="desc">Fully featured CI/CD service that builds, tests, and deploys to any cloud or on-premises environment. Supports YAML-based pipelines for "pipeline as code," multi-stage pipelines, deployment gates, approval workflows, and parallel jobs. Works natively with GitHub, Docker, Kubernetes, Terraform, and more.</td>
          <td class="use">Build .NET/Java/Node apps; deploy to AKS or App Service; multi-environment deployments with approvals (Dev → QA → Prod)</td>
        </tr>
        <tr>
          <td class="cat">CI/CD (GitHub)</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>GitHub Actions</td>
          <td class="desc">GitHub-native CI/CD automation platform (owned by Microsoft). Workflows are defined in YAML files in the repository (.github/workflows/). Massive marketplace of pre-built actions. Deeply integrated with Azure services via official Azure actions.</td>
          <td class="use">CI/CD for GitHub-hosted code; deploy to Azure App Service, AKS, or Azure Functions from GitHub</td>
        </tr>
        <!-- Project Management -->
        <tr>
          <td class="cat">Project Management</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Boards</td>
          <td class="desc">Agile project management tool within Azure DevOps. Supports Scrum, Kanban, and custom process templates. Track work items (User Stories, Tasks, Bugs, Epics), manage backlogs, run sprints, and create burndown charts. Integrates directly with Azure Repos and Pipelines.</td>
          <td class="use">Sprint planning; backlog management; link commits/pull requests to work items; release tracking dashboards</td>
        </tr>
        <!-- Containers -->
        <tr>
          <td class="cat">Container Registry</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Container Registry (ACR)</td>
          <td class="desc">Private Docker and OCI container registry for Azure. Stores and manages container images and Helm charts. Integrates with Azure Pipelines and AKS. Includes geo-replication (copies images to multiple regions), image scanning with Microsoft Defender, and Tasks (build images in the cloud).</td>
          <td class="use">Store Docker images built by Azure Pipelines; pull images to AKS; geo-replicate images for global deployments</td>
        </tr>
        <tr>
          <td class="cat">Serverless Containers</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Container Instances (ACI)</td>
          <td class="desc">Run containers directly without managing any cluster or virtual machines. Fast startup (seconds), pay-per-second billing. Good for one-off or burst workloads but not a full Kubernetes replacement. Can be used as a Kubernetes virtual node for burst scaling.</td>
          <td class="use">Run batch jobs in containers; quick testing of Docker images; burst compute for AKS via virtual nodes</td>
        </tr>
        <tr>
          <td class="cat">Kubernetes</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Kubernetes Service (AKS)</td>
          <td class="desc">Fully managed Kubernetes service — Azure manages the control plane for free, you manage node pools (VMs). Integrates with Azure AD (RBAC), Azure Monitor, ACR, Key Vault (via CSI driver), and Azure Load Balancer. Supports cluster autoscaler, spot node pools, and Azure Policy for governance.</td>
          <td class="use">Run production microservices; host multi-tenant SaaS applications; enterprise Kubernetes platform with AAD RBAC</td>
        </tr>
        <tr>
          <td class="cat">Container Apps</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Container Apps</td>
          <td class="desc">Serverless Kubernetes-based platform — run microservices and APIs without managing K8s clusters. Built on top of Kubernetes and Dapr (Distributed Application Runtime). Scale-to-zero capability, built-in KEDA-based autoscaling, traffic splitting for A/B testing.</td>
          <td class="use">Serverless microservices; event-driven workloads; APIs that need scale-to-zero; simpler alternative to AKS</td>
        </tr>
        <!-- IaC -->
        <tr>
          <td class="cat">Infrastructure as Code</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure ARM Templates</td>
          <td class="desc">Azure Resource Manager templates — JSON-based declarative IaC for Azure resources. Define your entire Azure infrastructure (VMs, VNets, databases, storage) in JSON. Azure ensures the state matches your template. The original native IaC for Azure.</td>
          <td class="use">Provision Azure environments from templates; enterprise governance with template specs; What-If analysis before deployment</td>
        </tr>
        <tr>
          <td class="cat">Infrastructure as Code</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Bicep</td>
          <td class="desc">A cleaner, simpler Domain-Specific Language (DSL) for Azure IaC — a huge improvement over ARM JSON templates. Bicep compiles to ARM templates. Strongly typed, with VS Code extension support, modular structure, and much more readable than raw ARM JSON.</td>
          <td class="use">Modern Azure IaC — replace ARM JSON with cleaner Bicep syntax; reusable Bicep modules for platform teams</td>
        </tr>
        <!-- Configuration -->
        <tr>
          <td class="cat">App Configuration</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure App Configuration</td>
          <td class="desc">Centralized service to manage application settings and feature flags separately from your code. Apps connect to App Configuration at runtime and pull their settings. Supports feature flags (turn features on/off without deploying), labels for environment separation (dev/staging/prod).</td>
          <td class="use">Centralize config for microservices; feature flag management for canary releases; environment-specific settings management</td>
        </tr>
        <tr>
          <td class="cat">Automation</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Automation</td>
          <td class="desc">Cloud-based automation service for repetitive IT tasks. Run PowerShell and Python runbooks on schedule or on-demand. State Configuration (DSC) manages server configuration like Ansible. Update Management patches Azure and on-premises VMs automatically.</td>
          <td class="use">Automate VM shutdown/startup schedules; patch management across hybrid environments; PowerShell-based remediation</td>
        </tr>
        <!-- Monitoring -->
        <tr>
          <td class="cat">Monitoring (Core)</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Monitor</td>
          <td class="desc">Azure's core monitoring platform — collects metrics and logs from all Azure resources, applications, and infrastructure (including on-premises). Creates alerts, sends notifications, and triggers automated actions. The backbone of all Azure observability tooling.</td>
          <td class="use">Alert on VM high CPU; auto-scale App Service based on request count; trigger Logic Apps on alert conditions</td>
        </tr>
        <tr>
          <td class="cat">Application Monitoring</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Application Insights</td>
          <td class="desc">APM (Application Performance Monitoring) service built into Azure Monitor. Add SDK to your app and it automatically collects request rates, response times, failure rates, dependency calls, exceptions, and custom events. Includes distributed tracing (Application Map) to visualize microservice dependencies.</td>
          <td class="use">Monitor .NET/Java/Node.js app performance; track API response times; debug exceptions in production; end-to-end distributed tracing</td>
        </tr>
        <tr>
          <td class="cat">Log Analytics</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Log Analytics Workspace</td>
          <td class="desc">Centralized log aggregation and query service within Azure Monitor. Collect logs from all Azure services, VMs, AKS clusters, applications, and security tools into one workspace. Query logs using KQL (Kusto Query Language) — a powerful, SQL-like log analysis language.</td>
          <td class="use">Central logging for all Azure resources; custom dashboards with KQL queries; security log analysis; AKS and container log analysis</td>
        </tr>
        <!-- Security -->
        <tr>
          <td class="cat">Secrets Management</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Key Vault</td>
          <td class="desc">Secure storage for secrets (passwords, API keys), cryptographic keys, and SSL/TLS certificates. Applications retrieve secrets at runtime via managed identity — no credentials in code. HSM (Hardware Security Module) backing available for compliance. Integrates directly with AKS (CSI driver), App Service, and Azure Pipelines.</td>
          <td class="use">Store database connection strings; inject secrets into AKS pods; manage SSL certificates; meet compliance requirements</td>
        </tr>
        <tr>
          <td class="cat">Identity &amp; Access</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Microsoft Entra ID (Azure AD)</td>
          <td class="desc">Microsoft's cloud identity platform — manage users, groups, and service principals. Provides SSO, MFA, Conditional Access, and Managed Identities (applications that authenticate to Azure services without storing credentials). Central to all Azure RBAC and DevOps access control.</td>
          <td class="use">DevOps team access control; AKS RBAC integration; service-to-service authentication; SSO for developer tools</td>
        </tr>
        <tr>
          <td class="cat">DevSecOps</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Microsoft Defender for DevOps</td>
          <td class="desc">Security tool that integrates directly into Azure Pipelines and GitHub Actions. Scans code (SAST), infrastructure-as-code templates (Terraform, ARM, Bicep), and container images for vulnerabilities. Provides a unified security view across all your code repositories.</td>
          <td class="use">Shift-left security scanning in pipelines; IaC misconfiguration detection; container image vulnerability alerts</td>
        </tr>
        <!-- Artifacts -->
        <tr>
          <td class="cat">Artifact Management</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Artifacts</td>
          <td class="desc">Package management service within Azure DevOps. Host private feeds for npm, NuGet, Maven, Python (pip), and Cargo packages. Upstream sources allow you to proxy public registries (npmjs.com, PyPI, Maven Central) — packages are cached and scanned before use by your team.</td>
          <td class="use">Private NuGet packages for .NET teams; private npm registry; share reusable libraries across projects; proxy public package registries</td>
        </tr>
        <!-- Serverless -->
        <tr>
          <td class="cat">Serverless Compute</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Functions</td>
          <td class="desc">Event-driven serverless compute — run functions in response to HTTP requests, timer schedules, Service Bus messages, Blob storage events, Cosmos DB changes, and more. Supports C#, JavaScript, Python, Java, and PowerShell. Consumption plan charges only for execution time.</td>
          <td class="use">Webhook processors; scheduled automation; event-driven data pipelines; API backends without managing servers</td>
        </tr>
        <!-- Testing -->
        <tr>
          <td class="cat">Testing</td>
          <td class="tool"><span class="badge badge-azure">Azure</span><br>Azure Load Testing</td>
          <td class="desc">Fully managed load testing service — generate high-scale load using Apache JMeter scripts. Identify performance bottlenecks before production. Integrates with Azure Pipelines to run load tests as part of your CI/CD pipeline and automatically fail if thresholds are exceeded.</td>
          <td class="use">Performance baseline before production releases; load test AKS APIs; integrate load testing into release gates</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
</section>


<!-- ═══ SECTION 7: COMMON TOOLS ═══ -->
<section id="common-tools">
<div class="container">
  <div class="section-label">Chapter 07</div>
  <h2>🌐 Common &amp; Universal DevOps Tools</h2>
  <p class="subtitle">These tools are cloud-agnostic — they work with both AWS and Azure (and other clouds). Most DevOps engineers are expected to know these regardless of which cloud they work on.</p>

  <div class="table-wrap">
    <table>
      <thead>
        <tr>
          <th>Category</th>
          <th>Tool</th>
          <th>Description</th>
          <th>AWS ✓</th>
          <th>Azure ✓</th>
          <th>Type</th>
        </tr>
      </thead>
      <tbody>
        <tr><td class="cat">Version Control</td><td class="tool">Git</td><td class="desc">The universal distributed version control system — tracks all code changes. Every DevOps engineer must master Git: branching, merging, rebasing, pull requests, and tagging.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Version Control</td><td class="tool">GitHub</td><td class="desc">The world's most popular code hosting platform (owned by Microsoft). Beyond Git repos — provides GitHub Actions CI/CD, pull requests, code review, GitHub Packages, GitHub Copilot, and Dependabot (automated security updates).</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Free / Paid</span></td></tr>
        <tr><td class="cat">Version Control</td><td class="tool">GitLab</td><td class="desc">All-in-one DevOps platform — Git repos + built-in CI/CD + container registry + security scanning + Kubernetes integration. Can be self-hosted (GitLab CE) or cloud (GitLab.com). Popular in enterprises that want everything in one place without GitHub.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">CI/CD</td><td class="tool">Jenkins</td><td class="desc">The most widely deployed open-source CI/CD automation server in the world. Hundreds of plugins for every tool and cloud. Highly customizable via Jenkinsfile (Groovy-based pipeline as code). Requires self-hosting and maintenance — but industry standard.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">CI/CD</td><td class="tool">GitHub Actions</td><td class="desc">YAML-based workflows that run on GitHub's infrastructure. Event-driven (push, PR, schedule, webhook). 15,000+ marketplace actions. Tightly integrated with GitHub repos. Free for public repos; usage minutes for private repos.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Free / Paid</span></td></tr>
        <tr><td class="cat">CI/CD</td><td class="tool">GitLab CI/CD</td><td class="desc">Built-in CI/CD in GitLab defined via .gitlab-ci.yml. Multi-stage pipelines, parallel jobs, environments, and deploy boards. Auto DevOps feature auto-detects your language and creates a pipeline automatically. No setup needed when using GitLab.com.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">CI/CD (GitOps)</td><td class="tool">ArgoCD</td><td class="desc">GitOps continuous delivery tool for Kubernetes. Monitors your Git repos and automatically synchronizes the cluster state to match what's defined in Git. Provides a visual UI to see what's deployed, what's out of sync, and rollback history. The leading GitOps tool for K8s.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Containerization</td><td class="tool">Docker</td><td class="desc">The de-facto standard for building and running containers. Docker Desktop for local development, Docker Engine for servers. Key concepts: Dockerfile (build instructions), Docker image (artifact), Docker container (running instance), Docker Compose (multi-container apps locally).</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Orchestration</td><td class="tool">Kubernetes (K8s)</td><td class="desc">The industry-standard container orchestration platform — automates deployment, scaling, and management of containerized applications. Core concepts: Pod, Deployment, Service, Ingress, ConfigMap, Secret, Namespace, PersistentVolume, HorizontalPodAutoscaler. Available as EKS (AWS) and AKS (Azure).</td><td>✅ EKS</td><td>✅ AKS</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">K8s Packaging</td><td class="tool">Helm</td><td class="desc">Kubernetes package manager — "charts" are pre-packaged, templated Kubernetes manifest bundles. Install complex applications (databases, monitoring stacks) with one command. Manage application configuration across environments via values files. Essential for K8s deployments.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Infrastructure as Code</td><td class="tool">Terraform</td><td class="desc">The most popular multi-cloud IaC tool — write once, deploy to AWS, Azure, GCP, Kubernetes, and 100+ providers. Uses HCL (HashiCorp Configuration Language). State management tracks what Terraform has deployed. Modules allow reusable infrastructure components. Industry-standard for cloud-agnostic IaC.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Config Management</td><td class="tool">Ansible</td><td class="desc">Agentless configuration management and automation tool — uses SSH to connect to servers, no agents installed. Playbooks are YAML files describing the desired system state. Roles allow reusable configuration. Widely used for server provisioning, application deployment, and cloud resource management.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Config Management</td><td class="tool">Chef / Puppet</td><td class="desc">Agent-based configuration management tools — enterprise-grade. Chef uses Ruby-based "recipes" and "cookbooks." Puppet uses its own declarative DSL. Agents run on managed servers and enforce configuration. More complex than Ansible but powerful for very large fleets (thousands of servers).</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Monitoring</td><td class="tool">Prometheus</td><td class="desc">Open-source metrics collection and alerting system — the standard for Kubernetes monitoring. Applications expose a /metrics endpoint; Prometheus scrapes it on a schedule. Stores time-series data. PromQL is the query language. Paired with Grafana for visualization. The most popular monitoring stack for K8s.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Visualization</td><td class="tool">Grafana</td><td class="desc">Open-source analytics and visualization platform — create beautiful dashboards from data sources like Prometheus, CloudWatch, Azure Monitor, Elasticsearch, and 100+ others. Drag-and-drop dashboard builder, alerting, and annotation support. The standard for DevOps dashboards and NOC/SOC screens.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Log Management</td><td class="tool">ELK Stack</td><td class="desc">Elasticsearch + Logstash + Kibana (sometimes + Beats). Logstash/Beats collect logs from all sources. Elasticsearch stores and indexes them for fast search. Kibana provides search UI and dashboards. Industry standard for centralized log management. OpenSearch (AWS fork) is an alternative.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">APM (Paid)</td><td class="tool">Datadog</td><td class="desc">Commercial full-stack observability platform — metrics, logs, traces, APM, RUM, synthetics, security, and more in one product. Extremely popular in enterprise environments. Quick to set up, powerful dashboards, smart alerting. Integrations with 700+ technologies. Industry's leading commercial monitoring tool.</td><td>✅</td><td>✅</td><td><span class="badge badge-aws" style="background:rgba(99,0,210,0.15);color:#9D00FF;border-color:rgba(99,0,210,0.3)">Commercial</span></td></tr>
        <tr><td class="cat">Secrets Management</td><td class="tool">HashiCorp Vault</td><td class="desc">Enterprise-grade secrets management — store, access, and rotate secrets, certificates, and encryption keys. Dynamic secrets (Vault generates temporary credentials on demand). Integrates with AWS, Azure, Kubernetes, and CI/CD tools. Standard for enterprises with strict compliance requirements.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Code Quality</td><td class="tool">SonarQube</td><td class="desc">Static application security testing (SAST) and code quality analysis — detects bugs, code smells, security vulnerabilities, and coverage gaps in your code before it reaches production. Integrates into CI/CD pipelines. Quality Gates block merges/deployments if code doesn't meet standards.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Security Scanning</td><td class="tool">Snyk</td><td class="desc">Developer-first security platform — scans your open-source dependencies (npm, pip, Maven, Go modules) for known vulnerabilities (CVEs) and suggests fixes. Also scans Docker images, Terraform/Kubernetes IaC, and code. IDE plugins let developers fix security issues while coding.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Free / Paid</span></td></tr>
        <tr><td class="cat">Container Scanning</td><td class="tool">Trivy</td><td class="desc">Open-source container image and filesystem vulnerability scanner by Aqua Security. Scans Docker images, file systems, and Git repos for vulnerabilities (OS packages, language libraries) and IaC misconfigurations. Fast, easy to integrate into CI/CD pipelines — one command to scan.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Open Source</span></td></tr>
        <tr><td class="cat">Incident Management</td><td class="tool">PagerDuty</td><td class="desc">Industry-leading incident management and on-call scheduling platform. Receives alerts from CloudWatch, Azure Monitor, Prometheus, Datadog, and 700+ integrations. Intelligently routes alerts to the right on-call engineer. Tracks incidents, escalations, post-mortems, and mean time to resolve (MTTR).</td><td>✅</td><td>✅</td><td><span class="badge badge-aws" style="background:rgba(99,0,210,0.15);color:#9D00FF;border-color:rgba(99,0,210,0.3)">Commercial</span></td></tr>
        <tr><td class="cat">Project Management</td><td class="tool">Jira</td><td class="desc">The most widely used Agile project management tool. Tracks Epics, User Stories, Tasks, and Bugs. Manages Scrum sprints and Kanban boards. Integrates with GitHub, GitLab, Jenkins, and all major DevOps tools. Roadmaps for release planning. Used in nearly every enterprise DevOps team.</td><td>✅</td><td>✅</td><td><span class="badge badge-aws" style="background:rgba(99,0,210,0.15);color:#9D00FF;border-color:rgba(99,0,210,0.3)">Commercial</span></td></tr>
        <tr><td class="cat">Documentation</td><td class="tool">Confluence</td><td class="desc">Team wiki and documentation platform by Atlassian (same company as Jira). Create runbooks, architecture docs, onboarding guides, and postmortem reports. Deep integration with Jira — link documentation to requirements and incidents. Standard for DevOps team knowledge bases.</td><td>✅</td><td>✅</td><td><span class="badge badge-aws" style="background:rgba(99,0,210,0.15);color:#9D00FF;border-color:rgba(99,0,210,0.3)">Commercial</span></td></tr>
        <tr><td class="cat">Communication</td><td class="tool">Slack</td><td class="desc">Team messaging platform that has become the nerve center of DevOps — alerts from monitoring, CI/CD notifications, deployment announcements, and ChatOps (run /deploy or /rollback commands from Slack). Integrates with every major DevOps tool. Essential for distributed teams.</td><td>✅</td><td>✅</td><td><span class="badge badge-free">Free / Paid</span></td></tr>
      </tbody>
    </table>
  </div>
</div>
</section>


<!-- ═══ SECTION 8: JOB MARKET ═══ -->
<section id="jobs">
<div class="container">
  <div class="section-label">Chapter 08</div>
  <h2>💼 Current Job Market — India &amp; USA (2025–2026)</h2>
  <p class="subtitle">DevOps is one of the most in-demand and highest-paying technical disciplines globally. Here's a realistic picture of the current market in both India and the United States.</p>

  <div class="market-grid">
    <!-- INDIA -->
    <div class="market-card">
      <div class="market-header india">🇮🇳 India Job Market</div>
      <div class="table-wrap">
        <table>
          <thead>
            <tr><th>Role</th><th>Experience</th><th>CTC / Year</th></tr>
          </thead>
          <tbody>
            <tr>
              <td class="tool" style="font-size:13px">Junior DevOps Engineer</td>
              <td class="exp-tag">0–2 yrs</td>
              <td><span class="salary-low">₹4 – 9 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">DevOps Engineer</td>
              <td class="exp-tag">2–4 yrs</td>
              <td><span class="salary-low">₹9 – 18 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">Senior DevOps Engineer</td>
              <td class="exp-tag">4–7 yrs</td>
              <td><span class="salary-high">₹18 – 38 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">DevOps Lead / Architect</td>
              <td class="exp-tag">7–10 yrs</td>
              <td><span class="salary-high">₹35 – 65 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">SRE (Site Reliability Eng.)</td>
              <td class="exp-tag">3–7 yrs</td>
              <td><span class="salary-high">₹20 – 50 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">Cloud DevOps Engineer</td>
              <td class="exp-tag">2–6 yrs</td>
              <td><span class="salary-high">₹14 – 35 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">DevSecOps Engineer</td>
              <td class="exp-tag">3–7 yrs</td>
              <td><span class="salary-high">₹18 – 42 LPA</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">Platform Engineer</td>
              <td class="exp-tag">4–8 yrs</td>
              <td><span class="salary-high">₹25 – 55 LPA</span></td>
            </tr>
          </tbody>
        </table>
      </div>
      <div style="padding:16px 20px;border-top:1px solid var(--border)">
        <p style="font-size:13px;color:var(--muted);margin-bottom:10px"><strong style="color:var(--heading)">Top Hiring Companies:</strong></p>
        <div class="tag-row">
          <span class="badge badge-aws" style="font-size:11px">Amazon India</span>
          <span class="badge badge-azure" style="font-size:11px">Microsoft India</span>
          <span class="badge badge-free" style="font-size:11px">Google India</span>
          <span class="badge badge-aws" style="font-size:11px">Flipkart</span>
          <span class="badge badge-azure" style="font-size:11px">Zepto / Swiggy</span>
          <span class="badge badge-free" style="font-size:11px">Razorpay</span>
          <span class="badge badge-aws" style="font-size:11px">Infosys / TCS</span>
          <span class="badge badge-azure" style="font-size:11px">Accenture</span>
          <span class="badge badge-free" style="font-size:11px">ThoughtWorks</span>
        </div>
        <p style="font-size:13px;color:var(--muted);margin-top:14px"><strong style="color:var(--heading)">Most In-Demand Skills (India 2025–26):</strong></p>
        <div class="tag-row">
          <span class="badge badge-aws" style="font-size:11px">Kubernetes</span>
          <span class="badge badge-azure" style="font-size:11px">Terraform</span>
          <span class="badge badge-both" style="font-size:11px">Docker</span>
          <span class="badge badge-aws" style="font-size:11px">AWS</span>
          <span class="badge badge-azure" style="font-size:11px">Azure</span>
          <span class="badge badge-free" style="font-size:11px">Jenkins</span>
          <span class="badge badge-free" style="font-size:11px">Python / Bash</span>
          <span class="badge badge-free" style="font-size:11px">GitHub Actions</span>
          <span class="badge badge-both" style="font-size:11px">Prometheus/Grafana</span>
        </div>
      </div>
    </div>

    <!-- USA -->
    <div class="market-card">
      <div class="market-header usa">🇺🇸 USA Job Market</div>
      <div class="table-wrap">
        <table>
          <thead>
            <tr><th>Role</th><th>Experience</th><th>Salary / Year</th></tr>
          </thead>
          <tbody>
            <tr>
              <td class="tool" style="font-size:13px">Junior DevOps Engineer</td>
              <td class="exp-tag">0–2 yrs</td>
              <td><span class="salary-low">$80k – $110k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">DevOps Engineer</td>
              <td class="exp-tag">2–4 yrs</td>
              <td><span class="salary-low">$110k – $150k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">Senior DevOps Engineer</td>
              <td class="exp-tag">4–7 yrs</td>
              <td><span class="salary-high">$150k – $200k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">DevOps Lead / Principal</td>
              <td class="exp-tag">7–10 yrs</td>
              <td><span class="salary-high">$185k – $260k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">SRE (Site Reliability Eng.)</td>
              <td class="exp-tag">3–7 yrs</td>
              <td><span class="salary-high">$160k – $240k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">Cloud DevOps Engineer</td>
              <td class="exp-tag">2–6 yrs</td>
              <td><span class="salary-high">$130k – $185k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">DevSecOps Engineer</td>
              <td class="exp-tag">3–7 yrs</td>
              <td><span class="salary-high">$140k – $195k</span></td>
            </tr>
            <tr>
              <td class="tool" style="font-size:13px">Platform Engineer</td>
              <td class="exp-tag">4–8 yrs</td>
              <td><span class="salary-high">$170k – $250k</span></td>
            </tr>
          </tbody>
        </table>
      </div>
      <div style="padding:16px 20px;border-top:1px solid var(--border)">
        <p style="font-size:13px;color:var(--muted);margin-bottom:10px"><strong style="color:var(--heading)">Top Hiring Companies:</strong></p>
        <div class="tag-row">
          <span class="badge badge-aws" style="font-size:11px">Amazon / AWS</span>
          <span class="badge badge-azure" style="font-size:11px">Microsoft</span>
          <span class="badge badge-free" style="font-size:11px">Google</span>
          <span class="badge badge-aws" style="font-size:11px">Netflix</span>
          <span class="badge badge-azure" style="font-size:11px">Meta</span>
          <span class="badge badge-free" style="font-size:11px">Cloudflare</span>
          <span class="badge badge-aws" style="font-size:11px">Stripe / Robinhood</span>
          <span class="badge badge-azure" style="font-size:11px">JP Morgan / Goldman</span>
          <span class="badge badge-free" style="font-size:11px">Salesforce / IBM</span>
        </div>
        <p style="font-size:13px;color:var(--muted);margin-top:14px"><strong style="color:var(--heading)">Most In-Demand Skills (USA 2025–26):</strong></p>
        <div class="tag-row">
          <span class="badge badge-aws" style="font-size:11px">Kubernetes / EKS</span>
          <span class="badge badge-azure" style="font-size:11px">Terraform</span>
          <span class="badge badge-both" style="font-size:11px">Docker</span>
          <span class="badge badge-aws" style="font-size:11px">AWS</span>
          <span class="badge badge-free" style="font-size:11px">Python / Go</span>
          <span class="badge badge-free" style="font-size:11px">GitHub Actions</span>
          <span class="badge badge-both" style="font-size:11px">Datadog / Grafana</span>
          <span class="badge badge-free" style="font-size:11px">ArgoCD / GitOps</span>
          <span class="badge badge-azure" style="font-size:11px">DevSecOps</span>
        </div>
      </div>
    </div>
  </div>

  <div class="mt-24 table-wrap">
    <table>
      <thead>
        <tr>
          <th>Factor</th>
          <th>🇮🇳 India</th>
          <th>🇺🇸 USA</th>
        </tr>
      </thead>
      <tbody>
        <tr><td class="label">Most demanded cloud</td><td>AWS (dominant) + Azure growing fast</td><td>AWS (leader) + Azure (enterprise) + GCP</td></tr>
        <tr><td class="label">Hottest certifications</td><td>AWS SAA, CKA, Terraform Associate, Azure AZ-104</td><td>CKA, AWS DevOps Pro, Terraform, GCP DevOps</td></tr>
        <tr><td class="label">Emerging roles</td><td>Platform Engineer, SRE, DevSecOps</td><td>Staff SRE, Principal DevOps, FinOps Engineer</td></tr>
        <tr><td class="label">Work model</td><td>Hybrid dominant; remote growing in startups</td><td>Remote-first common; on-site for FAANG</td></tr>
        <tr><td class="label">Top sectors hiring</td><td>IT services (TCS/Infosys), FinTech, e-commerce</td><td>Big tech, BFSI, healthcare, government/DoD</td></tr>
        <tr><td class="label">Scripting language</td><td>Python, Bash, PowerShell</td><td>Python, Go, Bash</td></tr>
        <tr><td class="label">Market growth (YoY)</td><td>~25–30% demand growth</td><td>~18–22% demand growth</td></tr>
      </tbody>
    </table>
  </div>
</div>
</section>


<!-- ═══ SECTION 9: ROADMAP ═══ -->
<section id="roadmap">
<div class="container">
  <div class="section-label">Chapter 09</div>
  <h2>🗺️ Your DevOps Learning Roadmap</h2>
  <p class="subtitle">Here's a practical month-by-month plan for a complete beginner to become job-ready in DevOps. Follow this order — don't skip ahead.</p>

  <div class="roadmap mt-32">
    <div class="rm-step">
      <div class="rm-dot done">1</div>
      <div class="rm-content">
        <div class="rm-month">Month 1 — Foundation</div>
        <div class="rm-title">Linux, Networking &amp; Git</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">Master Linux command line (essential for every DevOps tool), basic networking (IP, DNS, HTTP, firewalls), and Git workflows. This is your foundation — everything else builds on this.</p>
        <div class="rm-items">
          <span class="rm-tag green">Linux CLI (Ubuntu)</span>
          <span class="rm-tag green">File permissions &amp; processes</span>
          <span class="rm-tag green">Bash scripting basics</span>
          <span class="rm-tag green">Git: clone, commit, branch, merge</span>
          <span class="rm-tag green">GitHub pull requests</span>
          <span class="rm-tag green">Networking: TCP/IP, DNS, HTTP, SSH</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot done">2</div>
      <div class="rm-content">
        <div class="rm-month">Month 2 — Cloud Basics</div>
        <div class="rm-title">AWS or Azure — Cloud Fundamentals</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">Pick ONE cloud first (AWS is recommended for beginners globally; Azure if your company uses Microsoft). Understand the core services you'll use every day as a DevOps engineer.</p>
        <div class="rm-items">
          <span class="rm-tag">EC2 / Azure VM</span>
          <span class="rm-tag">S3 / Azure Blob Storage</span>
          <span class="rm-tag">VPC / Virtual Network</span>
          <span class="rm-tag">IAM / Entra ID</span>
          <span class="rm-tag">Security Groups / NSG</span>
          <span class="rm-tag">Free Tier hands-on labs</span>
          <span class="rm-tag">AWS SAA or AZ-900 study</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot done">3</div>
      <div class="rm-content">
        <div class="rm-month">Month 3 — Containerization</div>
        <div class="rm-title">Docker — Containers from Scratch</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">Containers are central to modern DevOps. Learn to build, run, and manage Docker containers. This will unlock every other DevOps tool.</p>
        <div class="rm-items">
          <span class="rm-tag">Docker installation &amp; CLI</span>
          <span class="rm-tag">Write Dockerfiles</span>
          <span class="rm-tag">Build &amp; push images to ECR/ACR</span>
          <span class="rm-tag">Docker Compose (multi-container)</span>
          <span class="rm-tag">Docker networking &amp; volumes</span>
          <span class="rm-tag">Container security basics</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot done">4</div>
      <div class="rm-content">
        <div class="rm-month">Month 4 — CI/CD Pipelines</div>
        <div class="rm-title">Jenkins + GitHub Actions</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">Build your first real CI/CD pipeline — automate code build, test, and deployment. This is the heart of DevOps practice.</p>
        <div class="rm-items">
          <span class="rm-tag">Install &amp; configure Jenkins</span>
          <span class="rm-tag">Jenkinsfile (pipeline as code)</span>
          <span class="rm-tag">GitHub Actions YAML workflows</span>
          <span class="rm-tag">Build Docker images in pipeline</span>
          <span class="rm-tag">Deploy to EC2 / Azure VM</span>
          <span class="rm-tag">Pipeline triggers &amp; notifications</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot">5</div>
      <div class="rm-content">
        <div class="rm-month">Month 5 — Infrastructure as Code</div>
        <div class="rm-title">Terraform + Ansible</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">Stop clicking in the AWS/Azure console — start provisioning infrastructure with code. Terraform for cloud resources, Ansible for server configuration.</p>
        <div class="rm-items">
          <span class="rm-tag amber">Terraform init/plan/apply/destroy</span>
          <span class="rm-tag amber">Terraform state management</span>
          <span class="rm-tag amber">Terraform modules</span>
          <span class="rm-tag amber">Ansible playbooks &amp; roles</span>
          <span class="rm-tag amber">Ansible for EC2/Azure VM setup</span>
          <span class="rm-tag amber">Combine Terraform + Ansible</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot">6</div>
      <div class="rm-content">
        <div class="rm-month">Month 6 — Kubernetes</div>
        <div class="rm-title">Kubernetes (K8s) Fundamentals</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">The most critical skill in modern DevOps. Learn Kubernetes step by step using minikube locally, then EKS or AKS on the cloud. Work toward the CKA certification.</p>
        <div class="rm-items">
          <span class="rm-tag amber">Pods, Deployments, Services</span>
          <span class="rm-tag amber">ConfigMaps &amp; Secrets</span>
          <span class="rm-tag amber">Ingress controllers</span>
          <span class="rm-tag amber">HPA (autoscaling)</span>
          <span class="rm-tag amber">Helm charts</span>
          <span class="rm-tag amber">EKS or AKS cluster setup</span>
          <span class="rm-tag amber">CKA exam prep</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot">7</div>
      <div class="rm-content">
        <div class="rm-month">Month 7 — Monitoring &amp; Observability</div>
        <div class="rm-title">Prometheus, Grafana &amp; ELK Stack</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">A deployed application is only half the job. Learn to monitor it, alert on issues, and analyze logs. Set up the industry-standard monitoring stack.</p>
        <div class="rm-items">
          <span class="rm-tag green">Prometheus setup &amp; PromQL</span>
          <span class="rm-tag green">Grafana dashboards</span>
          <span class="rm-tag green">Alertmanager configuration</span>
          <span class="rm-tag green">ELK Stack setup</span>
          <span class="rm-tag green">CloudWatch / Azure Monitor</span>
          <span class="rm-tag green">On-call &amp; incident response</span>
        </div>
      </div>
    </div>
    <div class="rm-step">
      <div class="rm-dot purple">8</div>
      <div class="rm-content">
        <div class="rm-month">Month 8+ — Specialization &amp; Certification</div>
        <div class="rm-title">Advanced Topics &amp; Certifications</div>
        <p style="font-size:13px;color:var(--muted);margin-bottom:12px">Now specialize based on your job target. Get certified to prove your skills to employers. Start applying for DevOps roles.</p>
        <div class="rm-items">
          <span class="rm-tag purple">CKA — Certified Kubernetes Admin</span>
          <span class="rm-tag purple">AWS DevOps Engineer Professional</span>
          <span class="rm-tag purple">HashiCorp Terraform Associate</span>
          <span class="rm-tag purple">AZ-400 Azure DevOps Expert</span>
          <span class="rm-tag purple">DevSecOps — SonarQube, Snyk</span>
          <span class="rm-tag purple">GitOps — ArgoCD / Flux</span>
          <span class="rm-tag purple">SRE practices (SLO/SLI/SLA)</span>
          <span class="rm-tag purple">Build real projects &amp; GitHub portfolio</span>
        </div>
      </div>
    </div>
  </div>
</div>
</section>

<footer>
  <p>📘 <strong>DevOps: Basics to Advanced</strong> — Complete Beginner's Reference Guide</p>
  <p style="margin-top:8px">Covers AWS DevOps Tools · Azure DevOps Tools · Common Tools · India &amp; USA Job Market · 8-Month Learning Roadmap</p>
  <p style="margin-top:8px">Content accurate as of 2025–2026 | Always refer to official documentation for the latest updates</p>
</footer>

</body>
</html>
