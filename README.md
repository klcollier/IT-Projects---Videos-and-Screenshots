<div  align="center">👨‍💻INFORMATION TECHNOLOGY DEMONSTRATIONS👨‍💻</div>
<p style="text-align:center"></p>


<div align="center">
  <h1>MICROSOFT AZURE</h1>
</div>

## Azure Environment
[Youtube](https://www.youtube.com/watch?v=npy3Q0vupQM)

- Resource Groups
- Virtual Machines
- Functions of the Environment


## osTicket Help Desk System  
![linktoosticket](https://imgur.com/a/aMsW14Q)


- System Creation
- Assigning Roles
- Assigning Tickets
- SLAs & Severities
  

## VPNs

- ProtonVPN
- Security Concepts for Remote Workers
- Azure


## Azure Network Security
![linktoActiveDir](https://youtu.be/npy3Q0vupQM)

- Azure Active Directory Deployment
- File Management
- Users & Assignments
- Access & Permissions


## DNS

- A-Records
- CNAMEs
- Azure Disk Storage


## Cost Management
![linktoAzureSubscriptionscreenshot](https://youtu.be/npy3Q0vupQM)

- Azure Subscription Creation
- Billing
- Budgets
- Procurement


<!---
klcollier/klcollier is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Help Desk Projects</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@400;500&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet"/>
  <style>
    :root {
      --bg: #f5f4f0;
      --surface: #ffffff;
      --border: #e0ddd6;
      --text: #1a1917;
      --muted: #6b6860;
      --accent: #1d4ed8;
      --accent-light: #eff6ff;
      --accent-muted: #93c5fd;
      --green: #15803d;
      --green-light: #f0fdf4;
      --amber: #b45309;
      --amber-light: #fffbeb;
      --tag-bg: #eeecea;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      min-height: 100vh;
    }

    /* ── HEADER ── */
    header {
      background: var(--surface);
      border-bottom: 1px solid var(--border);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-inner {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 2rem;
      height: 64px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 0.6rem;
      font-family: 'DM Mono', monospace;
      font-weight: 500;
      font-size: 0.9rem;
      color: var(--text);
      text-decoration: none;
      letter-spacing: -0.02em;
    }

    .logo-icon {
      width: 32px; height: 32px;
      background: var(--text);
      border-radius: 8px;
      display: grid;
      place-items: center;
    }

    .logo-icon svg { color: var(--bg); }

    nav { display: flex; gap: 2rem; }
    nav a {
      font-size: 0.875rem;
      font-weight: 500;
      color: var(--muted);
      text-decoration: none;
      transition: color 0.15s;
    }
    nav a:hover { color: var(--text); }

    /* ── HERO ── */
    .hero {
      max-width: 1100px;
      margin: 0 auto;
      padding: 5rem 2rem 4rem;
    }

    .hero-label {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      background: var(--accent-light);
      color: var(--accent);
      font-size: 0.75rem;
      font-weight: 600;
      font-family: 'DM Mono', monospace;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      padding: 0.3rem 0.75rem;
      border-radius: 100px;
      margin-bottom: 1.5rem;
    }

    .hero-label::before {
      content: '';
      width: 6px; height: 6px;
      background: var(--accent);
      border-radius: 50%;
    }

    h1 {
      font-family: 'DM Serif Display', serif;
      font-size: clamp(2.5rem, 6vw, 4rem);
      line-height: 1.1;
      letter-spacing: -0.02em;
      color: var(--text);
      max-width: 700px;
      margin-bottom: 1.25rem;
    }

    h1 em {
      font-style: italic;
      color: var(--accent);
    }

    .hero-desc {
      font-size: 1.1rem;
      color: var(--muted);
      max-width: 540px;
      line-height: 1.7;
      margin-bottom: 2.5rem;
      font-weight: 300;
    }

    .hero-actions {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      padding: 0.6rem 1.25rem;
      border-radius: 8px;
      font-size: 0.875rem;
      font-weight: 500;
      text-decoration: none;
      transition: all 0.15s;
      cursor: pointer;
      border: none;
    }

    .btn-primary {
      background: var(--text);
      color: var(--bg);
    }
    .btn-primary:hover { background: #2d2c2a; transform: translateY(-1px); }

    .btn-ghost {
      background: transparent;
      color: var(--muted);
      border: 1px solid var(--border);
    }
    .btn-ghost:hover { border-color: var(--text); color: var(--text); }

    /* ── STATS BAR ── */
    .stats-bar {
      max-width: 1100px;
      margin: 0 auto 3rem;
      padding: 0 2rem;
    }

    .stats-inner {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.25rem 2rem;
      display: flex;
      gap: 2.5rem;
      flex-wrap: wrap;
    }

    .stat {
      display: flex;
      flex-direction: column;
    }

    .stat-num {
      font-family: 'DM Serif Display', serif;
      font-size: 1.75rem;
      color: var(--text);
      letter-spacing: -0.02em;
      line-height: 1;
    }

    .stat-label {
      font-size: 0.78rem;
      color: var(--muted);
      font-weight: 500;
      margin-top: 0.2rem;
      text-transform: uppercase;
      letter-spacing: 0.05em;
    }

    .stat-divider {
      width: 1px;
      background: var(--border);
      align-self: stretch;
    }

    /* ── SECTION ── */
    section {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 2rem 5rem;
    }

    .section-header {
      display: flex;
      align-items: baseline;
      justify-content: space-between;
      margin-bottom: 1.5rem;
      padding-bottom: 1rem;
      border-bottom: 1px solid var(--border);
    }

    h2 {
      font-family: 'DM Serif Display', serif;
      font-size: 1.5rem;
      letter-spacing: -0.01em;
    }

    .section-count {
      font-family: 'DM Mono', monospace;
      font-size: 0.8rem;
      color: var(--muted);
    }

    /* ── PROJECT GRID ── */
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      gap: 1.25rem;
    }

    .card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.5rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      transition: all 0.2s;
      position: relative;
      overflow: hidden;
    }

    .card::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0;
      height: 3px;
      background: var(--accent);
      transform: scaleX(0);
      transform-origin: left;
      transition: transform 0.2s;
    }

    .card:hover { border-color: var(--accent-muted); box-shadow: 0 4px 20px rgba(0,0,0,0.07); transform: translateY(-2px); }
    .card:hover::before { transform: scaleX(1); }

    .card-top {
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
      gap: 1rem;
    }

    .card-icon {
      width: 44px; height: 44px;
      border-radius: 10px;
      display: grid;
      place-items: center;
      flex-shrink: 0;
      font-size: 1.3rem;
    }

    .card-status {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.72rem;
      font-weight: 600;
      padding: 0.25rem 0.6rem;
      border-radius: 100px;
      font-family: 'DM Mono', monospace;
      letter-spacing: 0.03em;
    }

    .status-active { background: var(--green-light); color: var(--green); }
    .status-wip { background: var(--amber-light); color: var(--amber); }
    .status-archived { background: var(--tag-bg); color: var(--muted); }

    .status-dot {
      width: 5px; height: 5px;
      border-radius: 50%;
      background: currentColor;
    }

    .card h3 {
      font-family: 'DM Serif Display', serif;
      font-size: 1.1rem;
      letter-spacing: -0.01em;
      color: var(--text);
    }

    .card p {
      font-size: 0.875rem;
      color: var(--muted);
      line-height: 1.6;
      flex: 1;
    }

    .card-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.4rem;
    }

    .tag {
      background: var(--tag-bg);
      color: var(--muted);
      font-size: 0.72rem;
      font-family: 'DM Mono', monospace;
      padding: 0.2rem 0.55rem;
      border-radius: 4px;
      font-weight: 500;
    }

    .card-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding-top: 0.75rem;
      border-top: 1px solid var(--border);
    }

    .card-meta {
      font-size: 0.78rem;
      color: var(--muted);
      font-family: 'DM Mono', monospace;
    }

    .card-links { display: flex; gap: 0.5rem; }

    .icon-btn {
      width: 32px; height: 32px;
      border-radius: 6px;
      border: 1px solid var(--border);
      background: transparent;
      display: grid;
      place-items: center;
      cursor: pointer;
      color: var(--muted);
      text-decoration: none;
      transition: all 0.15s;
    }
    .icon-btn:hover { border-color: var(--text); color: var(--text); }

    /* ── FEATURED ── */
    .card-featured {
      grid-column: 1 / -1;
      flex-direction: row;
      gap: 2rem;
      padding: 2rem;
      background: linear-gradient(135deg, #fafafa 0%, var(--accent-light) 100%);
      border-color: var(--accent-muted);
    }

    .card-featured .card-body { flex: 1; display: flex; flex-direction: column; gap: 1rem; }
    .card-featured .card-visual {
      width: 220px;
      flex-shrink: 0;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      gap: 0.6rem;
      padding: 1rem;
      align-self: center;
    }

    .mini-bar {
      height: 8px;
      border-radius: 100px;
      background: var(--border);
      position: relative;
      overflow: hidden;
    }

    .mini-bar-fill {
      position: absolute;
      left: 0; top: 0; bottom: 0;
      border-radius: 100px;
      background: var(--accent);
    }

    .mini-bar-label {
      display: flex;
      justify-content: space-between;
      font-size: 0.68rem;
      font-family: 'DM Mono', monospace;
      color: var(--muted);
    }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--border);
      background: var(--surface);
      padding: 2rem;
      text-align: center;
    }

    .footer-inner {
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .footer-copy {
      font-size: 0.8rem;
      color: var(--muted);
      font-family: 'DM Mono', monospace;
    }

    .footer-links { display: flex; gap: 1.5rem; }
    .footer-links a {
      font-size: 0.8rem;
      color: var(--muted);
      text-decoration: none;
      transition: color 0.15s;
    }
    .footer-links a:hover { color: var(--text); }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(16px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .hero { animation: fadeUp 0.5s ease both; }
    .stats-bar { animation: fadeUp 0.5s 0.1s ease both; }
    .card { animation: fadeUp 0.4s ease both; }
    .card:nth-child(1) { animation-delay: 0.1s; }
    .card:nth-child(2) { animation-delay: 0.15s; }
    .card:nth-child(3) { animation-delay: 0.2s; }
    .card:nth-child(4) { animation-delay: 0.25s; }
    .card:nth-child(5) { animation-delay: 0.3s; }

    @media (max-width: 640px) {
      .card-featured { flex-direction: column; }
      .card-featured .card-visual { width: 100%; }
      nav { display: none; }
      .stat-divider { display: none; }
    }
  </style>
</head>
<body>

<!-- HEADER -->
<header>
  <div class="header-inner">
    <a href="#" class="logo">
      <div class="logo-icon">
        <svg width="16" height="16" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M9.75 3.104v5.714a2.25 2.25 0 01-.659 1.591L5 14.5M9.75 3.104c-.251.023-.501.05-.75.082m.75-.082a24.301 24.301 0 014.5 0m0 0v5.714c0 .597.237 1.17.659 1.591L19.8 15.3M14.25 3.104c.251.023.501.05.75.082M19.8 15.3l-1.57.393A9.065 9.065 0 0112 15a9.065 9.065 0 00-6.23-.693L5 14.5m14.8.8l1.402 1.402c1 1 .03 2.798-1.319 2.798H4.117c-1.35 0-2.32-1.798-1.319-2.798L4.2 15.3"/>
        </svg>
      </div>
      helpdesk.dev
    </a>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
      <a href="https://github.com" target="_blank">GitHub ↗</a>
    </nav>
  </div>
</header>

<!-- HERO -->
<div class="hero">
  <div class="hero-label">IT Support Portfolio</div>
  <h1>Tools built to keep <em>teams running</em> smoothly.</h1>
  <p class="hero-desc">
    A collection of IT support tools, automation scripts, and help desk solutions—built to reduce ticket volume, speed up resolution, and empower end users.
  </p>
  <div class="hero-actions">
    <a href="#projects" class="btn btn-primary">
      <svg width="14" height="14" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M3 7.5h18M3 12h18M3 16.5h18"/></svg>
      Browse Projects
    </a>
    <a href="https://github.com" target="_blank" class="btn btn-ghost">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg>
      View on GitHub
    </a>
  </div>
</div>

<!-- STATS BAR -->
<div class="stats-bar">
  <div class="stats-inner">
    <div class="stat">
      <span class="stat-num">6</span>
      <span class="stat-label">Projects</span>
    </div>
    <div class="stat-divider"></div>
    <div class="stat">
      <span class="stat-num">4</span>
      <span class="stat-label">Active</span>
    </div>
    <div class="stat-divider"></div>
    <div class="stat">
      <span class="stat-num">3</span>
      <span class="stat-label">Languages</span>
    </div>
    <div class="stat-divider"></div>
    <div class="stat">
      <span class="stat-num">2024</span>
      <span class="stat-label">Latest Update</span>
    </div>
  </div>
</div>

<!-- PROJECTS SECTION -->
<section id="projects">
  <div class="section-header">
    <h2>IT Support Projects</h2>
    <span class="section-count">6 repositories</span>
  </div>

  <div class="project-grid">

    <!-- FEATURED -->
    <div class="card card-featured">
      <div class="card-body">
        <div class="card-top">
          <div class="card-icon" style="background:#eff6ff; font-size:1.4rem;">🎫</div>
          <span class="card-status status-active"><span class="status-dot"></span>Active</span>
        </div>
        <div>
          <h3>AutoTicket — Smart Ticket Routing System</h3>
          <p>Automatically categorizes and routes incoming support tickets using keyword matching and priority scoring. Integrates with popular help desk platforms via REST API. Reduces first-response time by routing tickets to the right team instantly.</p>
        </div>
        <div class="card-tags">
          <span class="tag">Python</span>
          <span class="tag">REST API</span>
          <span class="tag">Automation</span>
          <span class="tag">Jira</span>
          <span class="tag">ServiceNow</span>
        </div>
        <div class="card-footer">
          <span class="card-meta">Updated 2 weeks ago</span>
          <div class="card-links">
            <a href="#" class="icon-btn" title="View Repo">
              <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg>
            </a>
            <a href="#" class="icon-btn" title="Live Demo">
              <svg width="14" height="14" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg>
            </a>
          </div>
        </div>
      </div>
      <div class="card-visual">
        <div style="font-size:0.68rem; font-family:'DM Mono',monospace; color:var(--muted); margin-bottom:0.5rem;">TICKET ROUTING</div>
        <div>
          <div class="mini-bar-label"><span>Hardware</span><span>82%</span></div>
          <div class="mini-bar" style="margin-top:0.2rem; margin-bottom:0.5rem;"><div class="mini-bar-fill" style="width:82%"></div></div>
        </div>
        <div>
          <div class="mini-bar-label"><span>Software</span><span>67%</span></div>
          <div class="mini-bar" style="margin-top:0.2rem; margin-bottom:0.5rem;"><div class="mini-bar-fill" style="width:67%; background:#6366f1"></div></div>
        </div>
        <div>
          <div class="mini-bar-label"><span>Network</span><span>91%</span></div>
          <div class="mini-bar" style="margin-top:0.2rem; margin-bottom:0.5rem;"><div class="mini-bar-fill" style="width:91%; background:#0891b2"></div></div>
        </div>
        <div>
          <div class="mini-bar-label"><span>Access</span><span>55%</span></div>
          <div class="mini-bar" style="margin-top:0.2rem;"><div class="mini-bar-fill" style="width:55%; background:#d97706"></div></div>
        </div>
      </div>
    </div>

    <!-- Card 2 -->
    <div class="card">
      <div class="card-top">
        <div class="card-icon" style="background:#f0fdf4;">🔐</div>
        <span class="card-status status-active"><span class="status-dot"></span>Active</span>
      </div>
      <h3>AD Password Reset Portal</h3>
      <p>Self-service web portal allowing employees to reset Active Directory passwords securely without IT involvement. Includes identity verification via security questions and email OTP.</p>
      <div class="card-tags">
        <span class="tag">PowerShell</span>
        <span class="tag">Active Directory</span>
        <span class="tag">ASP.NET</span>
      </div>
      <div class="card-footer">
        <span class="card-meta">Updated 1 month ago</span>
        <div class="card-links">
          <a href="#" class="icon-btn"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg></a>
          <a href="#" class="icon-btn"><svg width="14" height="14" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg></a>
        </div>
      </div>
    </div>

    <!-- Card 3 -->
    <div class="card">
      <div class="card-top">
        <div class="card-icon" style="background:#fefce8;">📊</div>
        <span class="card-status status-active"><span class="status-dot"></span>Active</span>
      </div>
      <h3>IT Asset Inventory Dashboard</h3>
      <p>Real-time dashboard for tracking hardware and software assets across the organization. Auto-syncs with discovery agents and alerts on expiring licenses or aging hardware.</p>
      <div class="card-tags">
        <span class="tag">Python</span>
        <span class="tag">React</span>
        <span class="tag">PostgreSQL</span>
        <span class="tag">SNMP</span>
      </div>
      <div class="card-footer">
        <span class="card-meta">Updated 3 weeks ago</span>
        <div class="card-links">
          <a href="#" class="icon-btn"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg></a>
          <a href="#" class="icon-btn"><svg width="14" height="14" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg></a>
        </div>
      </div>
    </div>

    <!-- Card 4 -->
    <div class="card">
      <div class="card-top">
        <div class="card-icon" style="background:#fdf4ff;">⚙️</div>
        <span class="card-status status-wip"><span class="status-dot"></span>In Progress</span>
      </div>
      <h3>Onboarding Automation Suite</h3>
      <p>End-to-end new hire onboarding script suite. Creates AD accounts, provisions O365 licenses, sets up Slack, assigns laptop config profiles, and emails the new hire — all from a single form submission.</p>
      <div class="card-tags">
        <span class="tag">PowerShell</span>
        <span class="tag">Graph API</span>
        <span class="tag">Azure AD</span>
      </div>
      <div class="card-footer">
        <span class="card-meta">Updated 5 days ago</span>
        <div class="card-links">
          <a href="#" class="icon-btn"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg></a>
          <a href="#" class="icon-btn"><svg width="14" height="14" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg></a>
        </div>
      </div>
    </div>

    <!-- Card 5 -->
    <div class="card">
      <div class="card-top">
        <div class="card-icon" style="background:#fff1f2;">🌐</div>
        <span class="card-status status-active"><span class="status-dot"></span>Active</span>
      </div>
      <h3>Network Monitor & Alerter</h3>
      <p>Lightweight network monitoring tool that pings devices on a schedule, logs uptime, and sends Slack/email alerts when a host goes unreachable. Generates weekly availability reports.</p>
      <div class="card-tags">
        <span class="tag">Python</span>
        <span class="tag">Slack API</span>
        <span class="tag">Grafana</span>
      </div>
      <div class="card-footer">
        <span class="card-meta">Updated 2 months ago</span>
        <div class="card-links">
          <a href="#" class="icon-btn"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg></a>
          <a href="#" class="icon-btn"><svg width="14" height="14" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg></a>
        </div>
      </div>
    </div>

    <!-- Card 6 -->
    <div class="card">
      <div class="card-top">
        <div class="card-icon" style="background:#f0fdf4;">📋</div>
        <span class="card-status status-archived"><span class="status-dot"></span>Archived</span>
      </div>
      <h3>KB Article Scraper & Formatter</h3>
      <p>Scrapes internal SharePoint knowledge base pages and reformats them into clean Markdown or Confluence wiki format. Useful for migrations between help desk platforms.</p>
      <div class="card-tags">
        <span class="tag">Python</span>
        <span class="tag">BeautifulSoup</span>
        <span class="tag">Markdown</span>
      </div>
      <div class="card-footer">
        <span class="card-meta">Updated 8 months ago</span>
        <div class="card-links">
          <a href="#" class="icon-btn"><svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.551-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"/></svg></a>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <span class="footer-copy">© 2024 helpdesk.dev — Built with GitHub Pages</span>
    <div class="footer-links">
      <a href="https://github.com" target="_blank">GitHub</a>
      <a href="mailto:you@example.com">Contact</a>
    </div>
  </div>
</footer>

</body>
</html>
