---
layout: page
title: ""
icon: fas fa-info-circle
order: 1
---

<div class="about-header">
  <h1 class="display-title">Hi, I'm Sohaib Maan</h1>
  <p class="hero-subtitle">Machine Learning Enthusiast & Developer</p>
  <blockquote class="mission-statement">
    "Dedicated to turning raw data into intelligent insights and building predictive models for real-world impact."
  </blockquote>
</div>

## 🤖 Tech Stack & Tools

<div class="skills-grid">
  <div class="skill-item python">
    <i class="fab fa-python"></i>
    <span>Python</span>
    <small>(Scikit-Learn, Pandas)</small>
  </div>
  <div class="skill-item csharp">
    <i class="fas fa-code"></i>
    <span>C#</span>
    <small>(.NET / OOP)</small>
  </div>
  <div class="skill-item cpp">
    <i class="cpp-icon">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" aria-hidden="true">
        <polygon points="12,2 21,7 21,17 12,22 3,17 3,7" fill="none" stroke="currentColor" stroke-width="1.5"/>
        <text x="12" y="15.5" text-anchor="middle" font-family="Arial, sans-serif" font-size="8" font-weight="700" fill="currentColor">C++</text>
      </svg>
    </i>
    <span>C++</span>
    <small>(Game Development / OOP)</small>
  </div>
  <div class="skill-item sql">
    <i class="fas fa-database"></i>
    <span>MySQL</span>
    <small>(Data Engineering)</small>
  </div>
  <div class="skill-item web">
    <i class="fab fa-html5"></i>
    <span>Web</span>
    <small>(HTML5 / CSS3)</small>
  </div>
  <div class="skill-item js">
    <i class="fab fa-js-square"></i>
    <span>JavaScript</span>
    <small>(ES6)</small>
  </div>
</div>

## 🚀 The Journey So Far

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">UET Faisalabad 🎓</h3>
      <p class="milestone-date">2025 - PRESENT</p>
      <p>Advancing my engineering degree with a focus on high-performance computing and algorithmic efficiency at <strong>UET</strong>.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">Machine Learning Deep Dive 🤖</h3>
      <p class="milestone-date">SEP 2025 - FEB 2026</p>
      <p>Specializing in <strong>Predictive Modeling</strong>, using Scikit-Learn and Pandas to engineer features for intelligent insights.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">C# (.NET Framework) 🌐</h3>
      <p class="milestone-date">FEB 2026 - JUNE 2026</p>
      <p>Integrating ML models into functional web and desktop environments using <strong>.NET and C#</strong>.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">MySQL & Data Engineering 🗄️</h3>
      <p class="milestone-date">FEB 2026 - JUNE 2026</p>
      <p>Managing relational data structures to ensure seamless data flow for production-grade <strong>ML pipelines</strong>.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <h3 class="milestone-title">C++ 💻</h3>
      <p class="milestone-date">JUL 2026 - SEP 2026</p>
      <p>Learning <strong>C++</strong> independently, building on OOP concepts from C#, with a focus on data structures and core language fundamentals.</p>
    </div>
  </div>
</div>

<style>
/* Removes the empty space where the title used to sit */
header.d-flex.justify-content-between, 
#post-wrapper > header {
  display: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

.about-header {
  margin-top: -40px !important; /* Pulls your 'Hi, I'm Sohaib' to the very top */
}
  
  /* --- Universal Indigo Theme (Light/Dark Compatible) --- */
  
  .display-title {
    font-size: 3rem;
    font-weight: 900;
    background: linear-gradient(to right, #4f46e5, #06b6d4);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 0.2rem;
  }

  .hero-subtitle {
    color: #4f46e5;
    font-family: 'JetBrains Mono', monospace;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    margin-bottom: 20px;
  }

  .mission-statement {
    border-left: 5px solid #4f46e5 !important;
    background: rgba(79, 70, 229, 0.05) !important;
    border-radius: 8px !important;
    padding: 20px !important;
    color: inherit !important;
  }

  /* --- Skills Grid --- */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 15px;
    margin-top: 25px;
  }

  .skill-item {
    background: rgba(120, 120, 120, 0.05) !important;
    border: 1px solid rgba(79, 70, 229, 0.2) !important;
    padding: 20px;
    border-radius: 12px;
    text-align: center;
    transition: all 0.3s ease-in-out !important;
  }

  .skill-item:hover {
    border-color: #4f46e5 !important;
    transform: translateY(-8px) !important;
    box-shadow: 0 10px 20px rgba(79, 70, 229, 0.15);
  }

  .skill-item i {
    font-size: 2rem;
    margin-bottom: 12px;
    display: block;
    color: #4f46e5;
  }

  /* --- Perfectly Aligned & Moving Timeline --- */
  .timeline {
    position: relative;
    padding-left: 35px;
    border-left: 2px solid rgba(79, 70, 229, 0.2);
    margin: 40px 0;
    list-style: none;
  }

  .timeline-item {
    position: relative;
    margin-bottom: 35px;
    /* This allows children to move relative to this container */
    display: block; 
  }

  .timeline-dot {
    position: absolute;
    left: -42px; /* Adjusted to center exactly on the 2px line */
    top: 22px;
    width: 12px;
    height: 12px;
    background: #4f46e5;
    border-radius: 50%;
    z-index: 10;
    border: 2px solid var(--main-bg, #fff);
    transition: all 0.3s ease;
  }

  .timeline-content {
    background: rgba(120, 120, 120, 0.03) !important;
    border: 1px solid rgba(79, 70, 229, 0.1) !important;
    padding: 20px;
    border-radius: 14px;
    margin-left: 10px;
    /* The core movement logic */
    display: block;
    transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275), 
                background 0.3s ease, 
                border-color 0.3s ease !important;
    cursor: pointer;
  }

  /* Hover Action: Shift Card and Scale Dot */
  .timeline-item:hover .timeline-content {
    background: rgba(79, 70, 229, 0.07) !important;
    border-color: #4f46e5 !important;
    transform: translateX(15px) !important; /* Forces the slide effect */
    box-shadow: -5px 5px 15px rgba(0, 0, 0, 0.05);
  }

  .timeline-item:hover .timeline-dot {
    transform: scale(1.5);
    background: #06b6d4 !important;
    box-shadow: 0 0 10px #06b6d4;
  }

  .milestone-title { color: inherit; font-size: 1.2rem !important; font-weight: 700; margin-bottom: 5px !important; }
  .milestone-date { color: #4f46e5 !important; font-weight: bold; font-size: 0.8rem; margin-bottom: 10px; display: inline-block; }
  
  .timeline-content p { color: inherit; opacity: 0.8; font-size: 0.95rem; line-height: 1.6; margin: 0; }
</style>
