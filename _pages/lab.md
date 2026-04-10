---
layout: single
title: "Lab Members"
permalink: /lab/
author_profile: true
---

<style>
.lab-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
  gap: 2em;
  margin-top: 1.5em;
}

.lab-card {
  position: relative;
  background: var(--background-color, #f4f5f6);
  border-radius: 24px;
  overflow: hidden;
  height: 420px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.08);
  border: 4px solid var(--background-color, #ffffff);
  transform: translateZ(0); /* Safari fix */
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.lab-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 35px rgba(0,0,0,0.12);
}

.lab-card__avatar {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  background: var(--border-color, #e1e4e8);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 5em;
  color: var(--masthead-link-color, #ccc);
}

.lab-card__avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 20%;
  transition: transform 0.5s ease;
}

.lab-card:hover .lab-card__avatar img {
  transform: scale(1.03);
}

.lab-card__info {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  z-index: 2;
  padding: 80px 1.5em 1em;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  /* Soft white gradient for text readability, mimicking frosted glass */
  background: linear-gradient(to top, rgba(255,255,255,1) 0%, rgba(255,255,255,0.95) 40%, rgba(255,255,255,0) 100%);
}

.lab-card__name {
  font-size: 1.25em;
  font-weight: 700;
  margin: 0 0 0.1em;
  color: #1a1a1a;
}

.lab-card__name a {
  color: inherit;
  text-decoration: none;
}

.lab-card__name a:hover {
  text-decoration: underline;
}

.lab-card__role {
  font-size: 0.9em;
  font-weight: 600;
  color: #4a4a4a;
  margin: 0 0 0.2em;
  display: flex;
  align-items: center;
  gap: 6px;
}

.lab-card__role::after {
  content: "✅";
  font-size: 0.8em;
  opacity: 0.8;
}

.lab-card__comment {
  font-size: 0.85em;
  color: #4a4a4a;
  margin: 0 0 1.5em;
  line-height: 1.3;
}

.lab-card__action {
  margin-top: auto;
  display: flex;
  justify-content: flex-end;
}

.lab-btn {
  background: rgba(240, 240, 240, 0.9);
  color: #000;
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 0.85em;
  font-weight: 600;
  text-decoration: none;
  display: inline-flex;
  align-items: center;
  gap: 6px;
  transition: background 0.2s ease;
  backdrop-filter: blur(4px);
}

.lab-btn a {
  color: #000;
  text-decoration: none;
}

.lab-btn:hover {
  background: rgba(220, 220, 220, 1);
  color: #000;
  text-decoration: none;
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
    <div class="lab-card__info">
      <p class="lab-card__name"><a href="https://www.uml.edu/engineering/mechanical-industrial/faculty/sabato-alessandro.aspx" target="_blank">Prof. Alessandro Sabato</a></p>
      <p class="lab-card__comment"><strong>Advisor</strong>  &mdash; A great advisor who helps you grow both professionally and personally. A wonderful mentor with intellect, wit, and exceptional Italian cooking taste. 🇮🇹</p>
      <div class="lab-card__action">
        <a href="https://www.uml.edu/engineering/mechanical-industrial/faculty/sabato-alessandro.aspx" class="lab-btn" target="_blank">Profile <i class="fas fa-external-link-alt"></i></a>
      </div>
    </div>
  </div>
</div>

<h2 class="lab-section-title">Postdoctoral Mentor</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/fabio.jpeg" alt="Fabio Bottalico, Ph.D."></div>
    <div class="lab-card__info">
      <p class="lab-card__name"><a href="https://www.linkedin.com/in/fabio-bottalico/" target="_blank">Fabio Bottalico, Ph.D.</a></p>
      <p class="lab-card__comment"><strong>Postdoctoral Mentor</strong> &mdash; An exceptionally skillful researcher with remarkable coordination and a keen eye for detail.</p>
      <div class="lab-card__action">
        <a href="https://www.linkedin.com/in/fabio-bottalico/" class="lab-btn" target="_blank">LinkedIn <i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
</div>

<h2 class="lab-section-title">Labmates</h2>
<div class="lab-grid">
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/profile.png" alt="Jabbar Shah"></div>
    <div class="lab-card__info">
      <p class="lab-card__name">Jabbar Shah</p>
      <p class="lab-card__comment"><strong>Graduate Student</strong></p>
      <div class="lab-card__action">
        <a href="#" class="lab-btn" target="_blank">LinkedIn <i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/gaurav.jpeg" alt="Gaurav Modak"></div>
    <div class="lab-card__info">
      <p class="lab-card__name"><a href="https://www.linkedin.com/in/gaurav0123/" target="_blank">Gaurav Modak</a></p>
      <p class="lab-card__comment"><strong>Graduate Student</strong> &mdash; A genuinely talented and warm individual who is both a wonderful friend and an outstanding cook.</p>
      <div class="lab-card__action">
        <a href="https://www.linkedin.com/in/gaurav0123/" class="lab-btn" target="_blank">LinkedIn <i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><img src="/images/mo.jpg" alt="Mo"></div>
    <div class="lab-card__info">
      <p class="lab-card__name">Mo</p>
      <p class="lab-card__comment"><strong>Graduate Student</strong> &mdash; A humble and gifted mind with a wonderful ability to light up the room.</p>
      <div class="lab-card__action">
        <a href="#" class="lab-btn" target="_blank">LinkedIn <i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <div class="lab-card__info">
      <p class="lab-card__name">Francisco</p>
      <p class="lab-card__comment"><strong>Graduate Student</strong> &mdash; A powerhouse of energy and skill, always proactive and a true pleasure to work with.</p>
      <div class="lab-card__action">
        <a href="#" class="lab-btn" target="_blank">LinkedIn <i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
  <div class="lab-card">
    <div class="lab-card__avatar"><i class="fa fa-user"></i></div>
    <div class="lab-card__info">
      <p class="lab-card__name">Joao Oliveira</p>
      <p class="lab-card__comment"><strong>Graduate Student</strong> &mdash; Calm, highly capable, and always dependable. Handles every challenge with composure and grace.</p>
      <div class="lab-card__action">
        <a href="#" class="lab-btn" target="_blank">LinkedIn <i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
</div>
