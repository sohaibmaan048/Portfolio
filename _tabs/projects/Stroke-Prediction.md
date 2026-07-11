---
layout: page
title: Projects
icon: fas fa-code
order: 2
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
<!-- Custom CSS for Professional ML Project Card -->
<style>
  .project-card {
    background: var(--card-bg, #1e1e24);
    border: 1px solid var(--main-border-color, #2e2e33);
    border-radius: 12px;
    overflow: hidden;
    margin-bottom: 30px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  }
  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 24px rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(74, 144, 226, 0.25);
    border-color: rgba(74, 144, 226, 0.4);
  }

  /* --- Terminal window bar --- */
  .project-termbar {
    display: flex;
    align-items: center;
    gap: 8px;
    padding: 10px 16px;
    background: rgba(0, 0, 0, 0.2);
    border-bottom: 1px solid var(--main-border-color, #2e2e33);
  }
  .term-dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    display: inline-block;
  }
  .term-dot.red { background: #ff5f56; }
  .term-dot.yellow { background: #ffbd2e; }
  .term-dot.green { background: #27c93f; }
  .term-path {
    margin-left: 8px;
    font-family: 'JetBrains Mono', 'Fira Code', monospace;
    font-size: 0.78rem;
    color: var(--text-muted-color, #8a8a94);
  }
  .term-path::after {
    content: "";
    display: inline-block;
    width: 7px;
    height: 14px;
    margin-left: 4px;
    background: #63e6be;
    vertical-align: -2px;
    animation: blink 1.1s step-end infinite;
  }
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }

  .project-inner {
    padding: 24px;
  }
  .project-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    border-bottom: 1px solid var(--main-border-color, #2e2e33);
    padding-bottom: 12px;
    margin-bottom: 16px;
  }
  .project-title {
    font-size: 1.5rem;
    font-weight: 700;
    margin: 0;
    color: var(--heading-color, #fff);
  }
  .project-meta {
    font-size: 0.85rem;
    font-weight: 600;
    font-family: 'JetBrains Mono', 'Fira Code', monospace;
    color: #63e6be; /* Sleek ML Mint/Cyan tone */
    background: rgba(99, 230, 190, 0.1);
    padding: 6px 12px;
    border-radius: 6px;
    border: 1px solid rgba(99, 230, 190, 0.2);
    white-space: nowrap;
  }
  .project-description {
    font-size: 1rem;
    line-height: 1.6;
    margin-bottom: 20px;
  }
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 24px;
  }
  .tag-badge {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 0.75rem;
    font-weight: 600;
    font-family: 'JetBrains Mono', 'Fira Code', monospace;
    padding: 5px 12px;
    border-radius: 6px;
    background: rgba(74, 144, 226, 0.1);      /* Subtle transparent tech blue */
    border: 1px solid rgba(74, 144, 226, 0.25); /* matching glowing border */
    color: #5dade2;                             /* Crisp, bright tech blue text */
    transition: transform 0.15s ease, border-color 0.15s ease;
  }
  .tag-badge i {
    font-size: 0.95rem;
  }
  .tag-badge:hover {
    transform: translateY(-2px);
    border-color: rgba(74, 144, 226, 0.6);
  }
  .tag-badge.highlight {
    background: rgba(74, 144, 226, 0.15);
    border: 1px solid rgba(74, 144, 226, 0.3);
    color: #4a90e2; /* Deep Machine Learning Blue */
  }
  .project-links {
    display: flex;
    gap: 12px;
  }
  .btn-action {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 10px 18px;
    border-radius: 6px;
    font-size: 0.9rem;
    font-weight: 600;
    text-decoration: none !important;
    transition: transform 0.2s ease, box-shadow 0.2s ease, opacity 0.2s;
  }
  .btn-action:hover {
    transform: translateY(-2px);
  }
  .btn-live {
    background: #4a90e2; /* Cyber Blue */
    color: white !important;
  }
  .btn-live:hover {
    box-shadow: 0 6px 16px rgba(74, 144, 226, 0.4);
  }
  .btn-github {
    background: #24292e; /* Classic GitHub Dark */
    color: white !important;
    border: 1px solid #444c56;
  }
  .btn-github:hover {
    background: #2f363d;
  }
</style>
<!-- ================= STROKE PREDICTION PROJECT ================= -->
<div class="project-card">
  <div class="project-termbar">
    <span class="term-dot red"></span>
    <span class="term-dot yellow"></span>
    <span class="term-dot green"></span>
    <span class="term-path">Stroke-Risk-Prediction</span>
  </div>
  <div class="project-inner">
    <div class="project-header">
      <div>
        <h3 class="project-title">🧠 Stroke Risk Prediction System</h3>
        <div style="margin-top: 6px; font-size: 0.85rem; color: var(--text-muted-color);">
          <strong>Supervisor:</strong> Dr. Bilal Ahmad
        </div>
      </div>
      <span class="project-meta">Data Science & ML</span>
    </div>
    <p class="project-description">
      An end-to-end Machine Learning pipeline built to predict stroke risks based on clinical and lifestyle factors. This project transitions an isolated data science workflow into a fully functional, production-ready web application backed by structural database integrity.
    </p>
    <div class="tech-stack">
      <span class="tag-badge highlight"><i class="devicon-fastapi-plain"></i> FastAPI</span>
      <span class="tag-badge highlight"><i class="fas fa-sitemap"></i> Random Forest</span>
      <span class="tag-badge"><i class="devicon-mysql-plain"></i> MySQL (3NF)</span>
      <span class="tag-badge"><i class="devicon-python-plain"></i> Python</span>
      <span class="tag-badge"><i class="devicon-scikitlearn-plain"></i> Scikit-Learn</span>
    </div>
    <div class="project-links">
      <a href="YOUR_FASTAPI_LIVE_URL_HERE" target="_blank" class="btn-action btn-live">
        <i class="fas fa-rocket"></i> Live Demo
      </a>
      <a href="https://github.com/sohaibmaan048/Stroke-Prediction" target="_blank" class="btn-action btn-github">
        <i class="fab fa-github"></i> GitHub Repository
      </a>
    </div>
  </div>
</div>
