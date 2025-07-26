---
layout: default
title: Home
---

<!-- Link to icon animation CSS -->
<link rel="stylesheet" href="assets/css/icon-animations.css">
<!-- Link to About/Skills styling CSS -->
<link rel="stylesheet" href="assets/css/about-skills.css">
<!-- Link to Resume Button styling CSS -->
<link rel="stylesheet" href="assets/css/resume-btn.css">


<!-- Hero Section -->
<section id="hello" class="content-section">
  <div class="glass-section hero-section">
    <h1 class="hero-title">Hi, I'm ARUNABH BAROOAH</h1>
    <p class="hero-subtext">I build things at the intersection of software, data, and design.</p>
  </div>
</section>

<!-- About / Skills / Links Bento -->
<section id="about" class="content-section">
  <div class="glass-section bento-grid">
    <div class="bento-box about">
      <h2>About Me</h2>
      <p> CSE undergraduate at PES University with a passion for  full-stack development, data engineering, and machine learning.<br>
      I love building fast, innovative, useful, and beautiful products.</p>
    </div>

    <div class="bento-box skills">
      <h2>Skills</h2>
      <ul>
        <li><b>Programming Languages:</b> C, C++, Python, Go, JavaScript, HTML, CSS</li>
        <li><b>Web Development:</b> MongoDB, Express, ReactJS, NodeJS, NextJS, MySQL</li>
        <li><b>Big Data:</b> Kafka, Spark, Hadoop</li>
        <li><b>Design Tools: </b> Figma, Krita, Blender, Canva</li>
      </ul>
    </div>
    <div class="bento-box links">
      <h2>Links</h2>
      <a href="https://github.com/Arunabh13prt" target="_blank" style="margin-right: 20px;">
        <img src="assets/css/icons/github.png" alt="GitHub" width="28" height="28" style="vertical-align: middle;" />
      </a>
      <a href="http://www.linkedin.com/in/arunabh-barooah-a6a5a524b" target="_blank" style="margin-right: 20px;">
        <img src="assets/css/icons/linkedin.png" alt="LinkedIn" width="28" height="28" style="vertical-align: middle;" />
      </a>
      <a href="https://leetcode.com/u/abPrt/" target="_blank" style="margin-right: 20px;">
        <img src="assets/css/icons/leetcode.png" alt="LeetCode" width="28" height="28" style="vertical-align: middle;" />
      </a>
      <a href="assets/file/arunabh_barooah_resume.pdf" download class="resume-download-btn">Download Resume</a>
    </div>

  </div>
</section>

<!-- Projects -->
<section id="projects" class="content-section">
  <div class="glass-section">
    <h2 class="section-heading">My Projects</h2>
    <div class="project-grid">
      <a class="project-card project-link" href="https://github.com/Arunabh13prt/Distributed-Logging-System" target="_blank">
        <h3>Distributed logging system for Microservices</h3>
        <p>A system where multiple microservices can send messages over a pub-sub model. Built with Spark, Kafka, Fluentd, Kibana, ElasticSearch.</p>
      </a>
      <a class="project-card project-link" href="https://github.com/aryanmishra333/LAMBDA-Serverless-Function-Platform" target="_blank">
        <h3>⚙️ Serverless Execution Engine</h3>
        <p>A serverless function platform that allows you to run Python and Node.js code in isolated containers, similar to AWS Lambda. Built with Docker, gVisor, FastAPI</p>
      </a>
      <a class="project-card project-link" href="https://github.com/Arunabh13prt/Music-Genre-Classification-and-Recommendation-System" target="_blank">
        <h3>Deep Tune Network</h3>
        <p>A Music Genre Classification System and Recommendation System using ML models like CNN, RNN-LSTM, kNN, and techniques like cosine similarity.<br>
        Published in Springer Nature.</p>
      </a>
      <a class="project-card project-link" href="#" target="_blank">
        <h3>🛠️ Portfolio Site</h3>
        <p>This website! Built with Jekyll and GitHub Pages to showcase my projects and writing.</p>
      </a>
    </div>
  </div>
</section>

<!-- Experience -->
<section id="experience" class="content-section">
  <div class="glass-section">
    <h2 class="section-heading">Experience</h2>
    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-content">
          <h3>ML Research Intern @ C3I, PES University</h3>
          <p class="timeline-date">June 2024 – July 2024</p>
          <p>Developed Deep Tune Network (DTN) using Convolutional Neural Networks and MFCCs for automatic music genre classification,
achieving 93.01% test accuracy on the GTZAN dataset and designed a cosine similarity-based recommendation system with a similarity score of 0.85.</p>
        </div>
      </div>
      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-content">
          <h3>Core Member @ Parallax PESU</h3>
          <p class="timeline-date">Sept 2023 – Present</p>
          <p>Delivered a workshop on Krita to 40-50 students, achieving a 90% satisfaction rate based on post-workshop survey. Also executed marketing campaigns resulting in 500+ workshop registrations and 10,000+ social media interactions.</p>
        </div>
      </div>

      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-content">
          <h3>Member @ CodeChef PESU ECC</h3>
          <p class="timeline-date">Nov 2023 – Jan 2025</p>
          <p>Part of the design team. Designed and delivered marketing materials for the CodeChef PESU ECC events.</p>
        </div>
      </div>
      <!-- Add more timeline-item blocks as needed -->
    </div>
  </div>
</section>



<!-- Certificates -->
<section id="certificates" class="content-section">
  <div class="glass-section">
    <h2 class="section-heading">Certificates</h2>
    <div class="certificate-grid">
      <a href="assets/css/images/certificates/555_FL.jpg" class="certificate-card" data-lightbox="certificates" data-title="Certificate 1">
        <img src="assets/css/images/certificates/555_FL.jpg" alt="Certificate 1">
      </a>
      <a href="assets/css/images/certificates/555_Presentation.png" class="certificate-card" data-lightbox="certificates" data-title="Certificate 2">
        <img src="assets/css/images/certificates/555_Presentation.png" alt="Certificate 2">
      </a>
      <a href="assets/css/images/certificates/555_ThankYouLetter.png" class="certificate-card" data-lightbox="certificates" data-title="Certificate 3">
        <img src="assets/css/images/certificates/555_ThankYouLetter.png" alt="Certificate 3">
      </a>
      <!-- Add more certificate <a> blocks as needed -->
    </div>
  </div>
</section>

