---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-entry {
  margin-bottom: 1.15rem;
}
.cv-entry-head {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 1.25rem;
}
.cv-entry-title {
  min-width: 0;
}
.cv-entry-date {
  flex: 0 0 auto;
  margin-left: auto;
  font-size: 0.78rem;
  color: var(--global-text-color-light);
  white-space: nowrap;
  text-align: right;
}
.cv-entry-detail {
  margin-top: 0.16rem;
}
.cv-research-entry {
  margin-bottom: 1.2rem;
}
.cv-research-entry .cv-entry-head {
  margin-bottom: 0.18rem;
}
.cv-research-entry ul {
  margin-top: 0.22rem;
  margin-bottom: 0;
}
.cv-research-entry li {
  margin-bottom: 0.15rem;
}
@media (max-width: 700px) {
  .cv-entry-head {
    align-items: flex-start;
  }
  .cv-entry-date {
    font-size: 0.72rem;
  }
}
</style>

Research interests
======
Multi-UAV systems; aerial robotics; cooperative perception; target tracking and handoff; visibility-aware motion planning.

Education
======
<div class="cv-entry">
  <div class="cv-entry-head">
    <div class="cv-entry-title"><strong>PhD in Computer Science</strong>, Macquarie University, Sydney, Australia</div>
    <div class="cv-entry-date">Oct. 2023 – present</div>
  </div>
  <div class="cv-entry-detail"><strong>Thesis:</strong> <em>Continuous Monitoring of Submarine Animals using Multi-Drone Systems</em></div>
  <div class="cv-entry-detail"><strong>Supervisor:</strong> Professor Richard Han</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-head">
    <div class="cv-entry-title"><strong>Master of Science in Physics, Complex Adaptive Systems</strong>, University of Gothenburg, Gothenburg, Sweden</div>
    <div class="cv-entry-date">Sep. 2020 – Jun. 2023</div>
  </div>
  <div class="cv-entry-detail">Axel Adler Scholarship holder.</div>
  <div class="cv-entry-detail"><strong>Master's thesis:</strong> <em>Finding an optimal searching pattern of a fleet of drones</em></div>
  <div class="cv-entry-detail"><strong>Supervisor:</strong> Professor Ola Benderius</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-head">
    <div class="cv-entry-title"><strong>Bachelor of Science in Engineering, Aerospace and Mechanical Engineering</strong>, Korea Aerospace University, Goyang, South Korea</div>
    <div class="cv-entry-date">Mar. 2013 – Aug. 2018</div>
  </div>
  <div class="cv-entry-detail">National Scholarship holder.</div>
</div>

Research experience
======
<div class="cv-research-entry">
  <div class="cv-entry-head">
    <div class="cv-entry-title"><strong>Doctoral Researcher — School of Computing, Macquarie University</strong></div>
    <div class="cv-entry-date">Oct. 2023 – present</div>
  </div>
  <ul>
    <li>Conduct research on cooperative multi-UAV systems for persistent visual target sensing.</li>
    <li>Develop methods for cross-view target handoff, geometric verification, active target acquisition, and relay planning.</li>
    <li>Build and evaluate research systems using ROS-based simulation, computer vision, and real-world UAV experiments.</li>
    <li>Work across system formulation, implementation, experimental design, and quantitative evaluation.</li>
  </ul>
</div>

<div class="cv-research-entry">
  <div class="cv-entry-head">
    <div class="cv-entry-title"><strong>Master's Thesis Researcher — Chalmers University of Technology</strong></div>
    <div class="cv-entry-date">Nov. 2021 – Jun. 2023</div>
  </div>
  <ul>
    <li>Developed and evaluated search strategies for fleets of drones in maritime search scenarios.</li>
    <li>Investigated Lyapunov guidance vector fields, bearing-only, oscillatory, and waypoint-based methods.</li>
    <li>Built simulation tooling using C++ and Docker.</li>
  </ul>
</div>

Publications and manuscripts
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Teaching experience
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Industry experience
======
**Data Analyst — Summer Intern, Volvo Group Truck Technology**, Gothenburg, Sweden  
Jul. 2022 – Sep. 2022

- Analysed 97 field-test routes and outputs from the Energy Prediction Algorithm (EPA+).
- Compared route and speed prediction variants and investigated factors contributing to energy-prediction error using Python-based analysis.

Technical skills
======
- **Programming:** Python, C++, MATLAB, CMake
- **Robotics / systems:** ROS, Linux, WSL, Docker, Git
- **Machine learning / scientific computing:** PyTorch, TensorFlow/Keras, scikit-learn, NumPy/SciPy
- **Computer vision / visualisation:** OpenCV, Matplotlib
- **Research tooling:** LaTeX

Selected awards
======
- First Award, SARC-BARINet Aerospace Competition, 2021
- Outstanding Presentation of Publication, The Society for Aerospace System Engineering, 2017
