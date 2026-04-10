---
layout: single
title: "Lab Members"
permalink: /lab/
author_profile: true
---

<style>
.lab-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  gap: 1.5em;
  margin-top: 1.5em;
}

.lab-card {
  background: var(--background-color, #fff);
  border: 1px solid var(--border-color, #e1e4e8);
  border-radius: 12px;
  padding: 1.5em;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}

.lab-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.1);
  border-color: var(--link-color, #494e52);
}

.lab-card__avatar {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background: var(--border-color, #e1e4e8);
  margin: 0 auto 1em;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2em;
  color: var(--masthead-link-color, #6c757d);
  overflow: hidden;
}

.lab-card__avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.lab-card__name {
  font-size: 1.05em;
  font-weight: 600;
  margin: 0 0 0.3em;
  color: var(--text-color, #24292e);
}

.lab-card__name a {
  color: inherit;
  text-decoration: none;
}

.lab-card__name a:hover {
  color: var(--link-color, #494e52);
}

.lab-card__role {
  font-size: 0.85em;
  color: var(--masthead-link-color, #6c757d);
  margin: 0;
}

.lab-section-title {
  font-size: 1.2em;
  font-weight: 600;
  margin-top: 2em;
  margin-bottom: 0.5em;
  padding-bottom: 0.3em;
  border-bottom: 2px solid var(--border-color, #e1e4e8);
}
</style>

<h2 class="lab-section-title">Advisor</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/professor.png" alt="Prof. Alessandro Sabato"></div>
    <p class="lab-card__name"><a href="https://www.uml.edu/engineering/mechanical-industrial/faculty/sabato-alessandro.aspx" target="_blank">Prof. Alessandro Sabato</a></p>
    <p class="lab-card__role">Advisor</p>
  </div>
</div>

<h2 class="lab-section-title">Postdoctoral Mentor</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/fabio.jpeg" alt="Fabio Bottalico, Ph.D."></div>
    <p class="lab-card__name"><a href="https://www.linkedin.com/in/fabio-bottalico/" target="_blank">Fabio Bottalico, Ph.D.</a></p>
    <p class="lab-card__role">Postdoctoral Mentor</p>
  </div>
</div>

<h2 class="lab-section-title">Labmates</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/profile.png" alt="Jabbar Shah"></div>
    <p class="lab-card__name">Jabbar Shah</p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/gaurav.jpeg" alt="Gaurav Modak"></div>
    <p class="lab-card__name"><a href="https://www.linkedin.com/in/gaurav0123/" target="_blank">Gaurav Modak</a></p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/mo.jpg" alt="Mo"></div>
    <p class="lab-card__name">Mo</p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <p class="lab-card__name">Francisco</p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <p class="lab-card__name">Joao Oliveira</p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
</div>
