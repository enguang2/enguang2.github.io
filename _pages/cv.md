---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
description: "CV of Enguang Fan — PhD candidate at UIUC and Google Student Researcher. Education, industry experience, publications, research experience, honors, and skills."
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

**[Download PDF Resume](/files/Enguang_resume_20260925.pdf)**

<div class="cv-section">
<div class="cv-section-title">Education</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">University of Illinois Urbana-Champaign</div>
    <div class="cv-role">PhD Candidate in Computer Science</div>
    <div class="cv-detail">Advised by Prof. Klara Nahrstedt. Previously worked with Prof. Deepak Vasisht and Prof. Matthew Caesar.</div>
    <div class="cv-detail">Research: Spatial Intelligence, Wireless and Mobile Systems, Machine Learning, and Localization.</div>
  </div>
  <div class="cv-entry-date">Aug 2024 – May 2028 (expected)</div>
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
<div class="cv-section-title">Experience</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Google — Android Location Team</div>
    <div class="cv-role">Student Researcher (Intern) &nbsp;·&nbsp; Mountain View, CA</div>
    <div class="cv-detail">Supervised by Dr. Roy Want. Android Location Team — the team behind indoor positioning in Google Maps and Android Location Services.</div>
    <ul class="cv-bullets">
      <li>Advanced the integration of Wi-Fi Round Trip Time (RTT) indoor localization into Android's Fused Location Provider (FLP) and scaled evaluation across numerous Google offices in Mountain View.</li>
      <li>Achieved <strong>sub-second localization latency</strong> with <strong>1 m 90th-percentile error</strong> on Google Wi-Fi access points and <strong>2 m</strong> on enterprise-grade HPE Aruba, Cisco, and Arista wireless access points.</li>
      <li>Developed and evaluated tightly coupled particle-filter and Bayesian-grid methods for fusing Wi-Fi RTT measurements with motion sensors across varied motion and ranging conditions.</li>
      <li>Designed and implemented <strong>APSelector</strong>, a geometry-aware AP selection algorithm that prioritizes access points providing strong geometric constraints to mitigate NLOS and positive ranging biases.</li>
      <li>Incorporated IMDF walkable-path constraints, when available, as probabilistic priors to reject infeasible trajectories and further improve localization accuracy.</li>
    </ul>
  </div>
  <div class="cv-entry-date">May – Aug 2026</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Google — Android Location Team</div>
    <div class="cv-role">Student Researcher (Intern) &nbsp;·&nbsp; Mountain View, CA</div>
    <div class="cv-detail">Supervised by Dr. Roy Want. Android Location Team — the team behind indoor positioning in Google Maps and Android Location Services.</div>
    <ul class="cv-bullets">
      <li>Designed and developed an advanced indoor localization prototype combining Wi-Fi Round Trip Time (RTT) and motion sensor fusion on Pixel phones, achieving substantially lower latency and higher accuracy than Google's production Fused Location Provider (FLP) under challenging indoor environments (DFS channels, multipath-heavy areas).</li>
      <li>Implemented a passive Wi-Fi listening framework that reuses cached scan results from FLP to enable continuous RTT-based ranging without active scans, reducing localization update <strong>latency by 57%</strong> and eliminating blackout periods.</li>
      <li>Built a high-precision pedestrian dead reckoning (PDR) module leveraging Android's step detector and orientation sensors, and fused it with Wi-Fi RTT measurements through a multi-state Kalman filter, achieving <strong>0.8 m indoor localization accuracy</strong> at 90% CDF using existing commercial Wi-Fi infrastructure.</li>
      <li>Contributed to ongoing efforts to integrate Wi-Fi RTT capabilities into Google's Fused Location Provider framework for next-generation indoor localization.</li>
    </ul>
  </div>
  <div class="cv-entry-date">May – Aug 2025</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Publications</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">RTT-MOTION: Scan-Aware Real-Time Indoor Localization with Commodity Wi-Fi RTT</div>
    <div class="cv-role"><strong>Enguang Fan</strong> et al.</div>
    <div class="cv-detail">Under submission to ACM MobiCom 2027.</div>
  </div>
  <div class="cv-entry-date">2026</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Learning Latent RF Landmarks from Unlabeled Mobile Trajectories</div>
    <div class="cv-role"><strong>Enguang Fan</strong> et al.</div>
    <div class="cv-detail">Under submission to NeurIPS 2026.</div>
  </div>
  <div class="cv-entry-date">2026</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="https://arxiv.org/abs/2609.13795">Meter-Level Wi-Fi RTT Localization on a Production Enterprise WLAN</a></div>
    <div class="cv-role"><strong>Enguang Fan*</strong>, Binh Minh Tran*, Klara Nahrstedt</div>
    <div class="cv-detail">32nd ACM Annual International Conference on Mobile Computing and Networking (MobiCom '26), short paper. * Equal contribution.</div>
  </div>
  <div class="cv-entry-date">2026</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="https://arxiv.org/abs/2603.16141">Communication-Aware Multi-Agent Reinforcement Learning for Decentralized Cooperative UAV Deployment</a></div>
    <div class="cv-role"><strong>Enguang Fan</strong>, Yifan Chen, Zihan Shan, Matthew Caesar, Jae Kim</div>
    <div class="cv-detail">Accepted to the 2026 IEEE Global Communications Conference (GLOBECOM).</div>
  </div>
  <div class="cv-entry-date">2026</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="/files/milcom2023.pdf">Towards Effective Swarm-Based GPS Spoofing Detection in Disadvantaged Platforms</a></div>
    <div class="cv-role"><strong>Enguang Fan</strong>, Anfeng Peng, Matthew Caesar, Jae H. Kim, Josh Eckhardt, Greg Kimberly, Denis Osipychev</div>
    <div class="cv-detail">IEEE Military Communications Conference (MILCOM), Boston, USA.</div>
  </div>
  <div class="cv-entry-date">2023</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="https://arxiv.org/abs/2506.18317">Crowdsourcing Ubiquitous Indoor Localization with Non-Cooperative Wi-Fi Ranging</a></div>
    <div class="cv-role">Emerson Sie*, <strong>Enguang Fan*</strong>, Federico Cifuentes-Urtubey, Deepak Vasisht</div>
    <div class="cv-detail">arXiv preprint. * Equal contribution.</div>
  </div>
  <div class="cv-entry-date">2025</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="https://dl.acm.org/doi/pdf/10.1145/3680207.3765680">Scalable Indoor Localization with Non-Cooperative Wi-Fi Ranging</a></div>
    <div class="cv-role"><strong>Enguang Fan*</strong>, Emerson Sie*, Federico Cifuentes-Urtubey, Deepak Vasisht</div>
    <div class="cv-detail">Poster at the 31st ACM Annual International Conference on Mobile Computing and Networking (MobiCom), Hong Kong, China. <strong>Best Poster Runner-Up.</strong> * Equal contribution.</div>
  </div>
  <div class="cv-entry-date">2025</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org"><a href="https://arxiv.org/abs/2602.01673">Real-Time Loop Closure Detection in Visual SLAM via NetVLAD and Faiss</a></div>
    <div class="cv-role"><strong>Enguang Fan</strong></div>
    <div class="cv-detail">arXiv preprint arXiv:2602.01673.</div>
  </div>
  <div class="cv-entry-date">2026</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Research Experience</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Learning Latent RF Landmarks from Unlabeled Mobile Trajectories</div>
    <ul class="cv-bullets">
      <li>Developed a self-supervised Radio Frequency (RF) place-recognition framework that learns discriminative spatial embeddings from sparse Wi-Fi RTT/RSS trajectory segments, enabling mobile devices to discover repeatable latent landmarks without labeled locations or known access-point coordinates.</li>
      <li>Introduced RF-based loop closure for crowdsourced mobile SLAM, matching independently collected trajectory segments and incorporating high-confidence RF correspondences as constraints in pose-graph optimization to correct accumulated pedestrian dead-reckoning drift.</li>
      <li>Designed an end-to-end mapping pipeline that jointly reconstructs mobile trajectories and reusable RF landmarks from unlabeled walks, with robustness to missing AP observations, multipath, trajectory direction, and cross-device measurement variation.</li>
      <li>Built and released a synchronized Wi-Fi RTT/RSS/IMU trajectory dataset and reproducible SLAM benchmark with ground-truth poses for evaluating RF place recognition, loop-closure detection, and crowdsourced spatial mapping.</li>
    </ul>
  </div>
  <div class="cv-entry-date">Feb 2026 – Present</div>
</div>

<div class="cv-entry">
  <div class="cv-entry-body">
    <div class="cv-org">Crowdsourcing Ubiquitous Indoor Localization with Wi-Fi Ranging</div>
    <div class="cv-role">Supervised by Prof. Deepak Vasisht, UIUC</div>
    <ul class="cv-bullets">
      <li>Designed and implemented <em>PeepLoc</em>, a wireless indoor localization system fusing non-cooperative Wi-Fi ranging with pedestrian dead reckoning (PDR) without infrastructure support or PHY-layer access, achieving <strong>56% lower mean error</strong> than Android's Fused Location Provider (3.41 m vs. 7.71 m) across four buildings.</li>
      <li>Proposed a probabilistic backend that geolocates access points by fusing one-way time-of-flight (ToF) estimates with PDR trajectories in a joint non-linear least squares problem under clock-offset uncertainty.</li>
      <li>Developed a per-AP adaptive ranging model correcting non-line-of-sight (NLOS) multipath distortion and hardware-induced RTT slope deviations, improving end-to-end localization accuracy indoors.</li>
    </ul>
  </div>
  <div class="cv-entry-date">Oct 2024 – May 2025</div>
</div>
</div>

<div class="cv-section">
<div class="cv-section-title">Honors &amp; Awards</div>

* **MobiCom 2025 Best Poster Runner-Up**
* UIUC Fall 2022 Teachers (TA) Ranked as Excellent by Their Students — [Link](https://citl.illinois.edu/docs/default-source/teachers-ranked-as-excellent/tre-2022-fall.pdf)
</div>

<div class="cv-section">
<div class="cv-section-title">Skills</div>

* **Languages**: Python, C, C++, Java, MATLAB
* **Machine Learning, Deep Learning &amp; Computer Vision**: PyTorch, TensorFlow, Transformers, LSTMs, Reinforcement Learning, OpenCV
* **Robotics &amp; State Estimation**: SLAM, visual-inertial odometry, factor graphs, Kalman/particle filters, sensor fusion, PDR, ROS/ROS2
* **Wireless &amp; Mobile Systems**: Wi-Fi RTT, Android, Linux, CMake
</div>
