---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
description: "CV of Enguang Fan — PhD student at UIUC, ex-Google researcher. Education, publications, research experience, honors, and skills."
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-section {
  margin-top: 2em;
}
.cv-section-title {
  font-size: 1em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  border-bottom: 2px solid #e8e8e8;
  padding-bottom: 4px;
  margin-bottom: 1em;
  color: #333;
}
.cv-entry {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1.2em;
  gap: 1em;
}
.cv-entry-body {
  flex: 1;
}
.cv-entry-date {
  color: #888;
  font-size: 0.88em;
  white-space: nowrap;
  text-align: right;
  padding-top: 2px;
}
.cv-org {
  font-weight: 700;
  font-size: 0.97em;
}
.cv-role {
  font-style: italic;
  color: #555;
  font-size: 0.92em;
}
.cv-detail {
  font-size: 0.88em;
  color: #555;
  margin-top: 2px;
}
.cv-bullets {
  margin-top: 6px;
  padding-left: 1.3em;
  font-size: 0.88em;
  color: #444;
}
.cv-bullets li {
  margin-bottom: 4px;
  line-height: 1.55;
}
</style>

**[Download PDF Resume](/files/Enguang_resume_04052026.pdf)**

<div class="cv-section">
<div class="cv-section-title">Education</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">University of Illinois Urbana-Champaign</div>
    <div class="cv-role">PhD in Computer Science</div>
    <div class="cv-detail">Advised by Prof. Klara Nahrstedt. Previously worked with Prof. Deepak Vasisht and Prof. Matthew Caesar.</div>
  </div>
  <div class="cv-entry-date">Aug 2024 – May 2027</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">University of Illinois Urbana-Champaign</div>
    <div class="cv-role">Master of Computer Science</div>
  </div>
  <div class="cv-entry-date">Aug 2022 – May 2024</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">University of Illinois Urbana-Champaign</div>
    <div class="cv-role">B.S. in Statistics &amp; Computer Science, <strong>Highest Distinction</strong></div>
  </div>
  <div class="cv-entry-date">Aug 2019 – Aug 2022</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Internship</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Google — Android Location Team</div>
    <div class="cv-role">Student Researcher &nbsp;·&nbsp; Mountain View, CA</div>
    <div class="cv-detail">Supervised by Dr. Roy Want. Android Location Team — the team behind indoor positioning in Google Maps and Android Location Services.</div>
    <ul class="cv-bullets">
      <li>Designed an advanced indoor localization prototype combining Wi-Fi RTT and IMU sensor fusion on Pixel, achieving substantially lower latency and higher accuracy than Google's production Fused Location Provider (FLP).</li>
      <li>Implemented a passive Wi-Fi listening framework reusing cached FLP scan results for continuous RTT-based ranging, reducing localization update latency by <strong>57%</strong> and eliminating blackout periods.</li>
      <li>Built a high-precision PDR module leveraging Android's step detector and orientation sensors, fused with Wi-Fi RTT via a multi-state Kalman filter, achieving <strong>0.8 m accuracy at 90% CDF</strong>.</li>
      <li>Contributed to integrating Wi-Fi RTT capabilities into Google's FLP framework for next-generation indoor localization.</li>
    </ul>
  </div>
  <div class="cv-entry-date">May – Aug 2025</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Research Experience</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Crowdsourcing Ubiquitous Indoor Localization with Wi-Fi Ranging</div>
    <div class="cv-role">Supervised by Prof. Deepak Vasisht, UIUC</div>
    <ul class="cv-bullets">
      <li>Designed and implemented <em>PeepLoc</em>, a scalable indoor localization system using non-cooperative Wi-Fi Ranging and IMU-based PDR, requiring no infrastructure or PHY-layer access.</li>
      <li>Proposed a probabilistic backend for geolocating APs using one-way ToF estimates fused with PDR trajectories, solving a joint non-linear least squares problem under clock offset uncertainty.</li>
      <li>Demonstrated PeepLoc outperforms Android FLP by over <strong>40%</strong> in mean error (3.41 m vs. 7.71 m) across four real-world campus buildings.</li>
    </ul>
  </div>
  <div class="cv-entry-date">Oct 2024 – May 2025</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Swarm-Based GPS Spoofing Detection by Multimodal Sensor Fusion</div>
    <div class="cv-role">Supervised by Prof. Matthew Caesar, UIUC</div>
    <ul class="cv-bullets">
      <li>Proposed an EKF-based sensor fusion architecture combining IMU, inter-drone communication, and signal strength analysis to detect GPS spoofing on resource-constrained drones.</li>
      <li>Demonstrated significant improvements in location accuracy and error variance reduction over baselines via simulation on real-world mobility traces.</li>
    </ul>
  </div>
  <div class="cv-entry-date">May – Aug 2023</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Probabilistic Programming Robustness</div>
    <div class="cv-role">Supervised by Prof. Sasa Misailovic, UIUC</div>
    <ul class="cv-bullets">
      <li>Contributed to building a system for automatically transforming probabilistic programs to enhance robustness against data variability.</li>
      <li>Conducted robustness assessments of probabilistic programs using Stan and R.</li>
    </ul>
  </div>
  <div class="cv-entry-date">May 2020 – Feb 2021</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Teaching</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">CS 437 Topics in Internet of Things</div>
    <div class="cv-role">Graduate Teaching Assistant, UIUC</div>
  </div>
  <div class="cv-entry-date">Fall 2023</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="https://cs341.cs.illinois.edu/">CS 341 System Programming</a></div>
    <div class="cv-role">Graduate Teaching Assistant, UIUC</div>
  </div>
  <div class="cv-entry-date">Fall 2022</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Honors &amp; Awards</div>

* **MobiCom 2025 Best Poster Runner-Up**
* MobiCom 2025 Student Travel Grant
* IEEE MILCOM 2023 Student Travel Grant — [Link](https://milcom2023.ieee-milcom.org/)
* UIUC Fall 2022 Teachers (TA) Ranked as Excellent by Their Students — [Link](https://citl.illinois.edu/docs/default-source/teachers-ranked-as-excellent/tre-2022-fall.pdf)
* UIUC Dean's List FA19, SP20, FA21, SP22
</div>

<div class="cv-section">
<div class="cv-section-title">Service</div>

* ISIBER 2026 (Reviewer)
* IROS 2026 (Reviewer)
* PRICAI 2025 (Reviewer)
* OSDI 2025 (Artifact Evaluation Reviewer)
* SIGCOMM 2025 (Artifact Evaluation Reviewer)
* EuroSys 2026 (Artifact Evaluation Reviewer)
</div>

<div class="cv-section">
<div class="cv-section-title">Skills</div>

* **Programming**: C/C++, Java, Python, Matlab
* **Tools & Frameworks**: PyTorch, TensorFlow, NumPy, OpenCV, ROS/ROS2, CMake, Gazebo
* **Techniques**: Sensor Fusion, Kalman Filtering, SLAM, Object-Oriented Design, Unit Testing
</div>
