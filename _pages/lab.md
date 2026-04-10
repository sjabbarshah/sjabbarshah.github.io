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
  width: 90px;
  height: 90px;
  border-radius: 50%;
  background: var(--border-color, #e1e4e8);
  margin: 0 auto 1em;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2em;
  color: var(--masthead-link-color, #6c757d);
}

.lab-card__name {
  font-size: 1.05em;
  font-weight: 600;
  margin: 0 0 0.3em;
  color: var(--text-color, #24292e);
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

<!-- TODO: Replace the placeholder names below with your actual lab members -->

<h2 class="lab-section-title">Principal Investigator</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <p class="lab-card__name">Dr. [Advisor Name]</p>
    <p class="lab-card__role">Principal Investigator</p>
  </div>
</div>

<h2 class="lab-section-title">Graduate Students</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <p class="lab-card__name">Jabbar Shah</p>
    <p class="lab-card__role">Graduate Research Assistant</p>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <p class="lab-card__name">[Lab Member 2]</p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <p class="lab-card__name">[Lab Member 3]</p>
    <p class="lab-card__role">Graduate Student</p>
  </div>
</div>
