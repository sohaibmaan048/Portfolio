---
layout: page
title: Projects
icon: fas fa-code
order: 2
---

<!-- Custom CSS for Professional ML Project Card -->
<style>
  .project-card {
    background: var(--card-bg, #1e1e24);
    border: 1px solid var(--main-border-color, #2e2e33);
    border-radius: 12px;
    padding: 24px;
    margin-bottom: 30px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .project-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
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
    color: #63e6be; /* Sleek ML Mint/Cyan tone */
    background: rgba(99, 230, 190, 0.1);
    padding: 6px 12px;
    border-radius: 6px;
    border: 1px solid rgba(99, 230, 190, 0.2);
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
    font-size: 0.75rem;
    font-weight: 600;
    padding: 4px 10px;
    border-radius: 4px;
    background: #25262b;
    border: 1px solid #373a40;
    color: #909296;
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
    transition: opacity 0.2s, background 0.2s;
  }
  .btn-action:hover {
    opacity: 0.9;
  }
  .btn-live {
    background: #4a90e2; /* Cyber Blue */
    color: white !important;
  }
  .btn-github {
    background: #24292e; /* Classic GitHub Dark */
    color: white !important;
    border: 1px solid #444c56;
  }
</style>

<!-- ================= STROKE PREDICTION PROJECT ================= -->
<div class="project-card">
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
    <span class="tag-badge highlight">FastAPI</span>
    <span class="tag-badge highlight">Random Forest</span>
    <span class="tag-badge">MySQL (3NF)</span>
    <span class="tag-badge">Python</span>
    <span class="tag-badge">Scikit-Learn</span>
  </div>

  <div class="project-links">
    <a href="YOUR_FASTAPI_LIVE_URL_HERE" target="_blank" class="btn-action btn-live">
      <i class="fas fa-rocket"></i> Live Demo
    </a>
    <a href="YOUR_GITHUB_REPO_URL_HERE" target="_blank" class="btn-action btn-github">
      <i class="fab fa-github"></i> GitHub Repository
    </a>
  </div>
</div>
