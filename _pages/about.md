---
layout: portfolio
title: Hanli Zhang
permalink: /
description: Robotics researcher building learning-enabled systems for autonomy, perception, planning, and human-robot interaction.
---

<section class="portfolio-hero" aria-labelledby="intro-title">
  <div class="hero-copy">
    <p class="eyebrow">ROBOTICS · AI/ML · AUTONOMOUS SYSTEMS</p>
    <h1 id="intro-title">Building intelligent systems<br><span>from models to motion.</span></h1>
    <p class="hero-summary">I’m 张涵俐 Hanli Zhang, a robotics researcher at <a href="https://www.epfl.ch/labs/lasa/">EPFL LASA</a> under the supervision of <a href="https://people.epfl.ch/aude.billard">Prof. Aude Billard</a>, based in Lausanne, Switzerland.</p>
    <p class="hero-focus">My work connects learning, planning, perception, and control—then tests the result on real robotic systems.</p>

    <div class="hero-actions">
      <a class="button button-primary" href="#work">Explore selected work <span aria-hidden="true">↓</span></a>
      <a class="button button-secondary" href="{{ '/assets/pdf/Hanli_Zhang_Robotics_Core.pdf' | relative_url }}" target="_blank" rel="noopener">Robotics résumé <span aria-hidden="true">↗</span></a>
    </div>

    <div class="hero-links" aria-label="Contact and profiles">
      <a href="mailto:hanlizhangzhl@gmail.com"><i class="fa-solid fa-envelope" aria-hidden="true"></i> Email</a>
      <a href="https://www.linkedin.com/in/hanli-zhang"><i class="fa-brands fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
      <a href="https://github.com/hanlizhang"><i class="fa-brands fa-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </div>

  <div class="hero-visual" aria-label="Portrait of Hanli Zhang">
    <div class="portrait-frame">
      <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Hanli Zhang" width="1642" height="1606">
    </div>
    <div class="availability-card">
      <span class="status-dot" aria-hidden="true"></span>
      <span>Open to robotics &amp; applied AI roles</span>
    </div>
  </div>
</section>

<section class="proof-strip" aria-label="Selected outcomes">
  <div><strong>83%</strong><span>lower simulated tracking error</span></div>
  <div><strong>49%</strong><span>lower simulated crash rate</span></div>
  <div><strong>40 FPS</strong><span>on Jetson Xavier NX</span></div>
  <div><strong>±5 mm</strong><span>AGV pose accuracy</span></div>
</section>

<section class="portfolio-section" id="work" aria-labelledby="work-title">
  <div class="section-heading">
    <div>
      <p class="eyebrow">SELECTED WORK</p>
      <h2 id="work-title">Evidence, not just keywords.</h2>
    </div>
    <p>Projects spanning aerial robotics, embedded perception, robot learning, and visual SLAM—with demos, code, papers, and reports where available.</p>
  </div>

  <article class="project-feature">
    <div class="project-media">
      <video controls playsinline preload="metadata" poster="{{ '/assets/img/quad_lcd_demo.jpg' | relative_url }}">
        <source src="{{ '/assets/video/quad_lcd_demo_web.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support embedded video. <a href="{{ '/assets/video/quad_lcd_demo_web.mp4' | relative_url }}">Open the demo</a>.
      </video>
      <span class="media-label"><i class="fa-solid fa-play" aria-hidden="true"></i> Hardware demo</span>
    </div>
    <div class="project-copy">
      <div class="project-kicker"><span>01</span> Aerial robotics · UPenn GRASP</div>
      <h3>Drag-Aware Quadrotor Planning &amp; Sim-to-Real Validation</h3>
      <p>Learned a tracking-cost model from 200,000 simulated trajectories and integrated it into trajectory optimization with an SE(3) controller, then validated the planner on Crazyflie hardware.</p>
      <div class="project-metrics">
        <div><strong>83%</strong><span>lower tracking error</span></div>
        <div><strong>49%</strong><span>lower simulated crash rate</span></div>
      </div>
      <div class="tag-list" aria-label="Technologies"><span>Python</span><span>JAX</span><span>Trajectory optimization</span><span>Sim-to-real</span></div>
      <div class="project-links">
        <a href="https://arxiv.org/abs/2505.10228">Paper <span aria-hidden="true">↗</span></a>
        <a href="https://github.com/hanlizhang/AeroWrenchPlanner">Code <span aria-hidden="true">↗</span></a>
        <a href="{{ '/assets/video/quad_lcd_demo_web.mp4' | relative_url }}">Full video <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </article>

  <article class="project-feature project-feature-reverse">
    <div class="project-media">
      <video controls muted loop playsinline preload="metadata" poster="{{ '/assets/img/f1tenth_demo.jpg' | relative_url }}">
        <source src="{{ '/assets/video/f1tenth_demo_web.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support embedded video. <a href="{{ '/assets/video/f1tenth_demo_web.mp4' | relative_url }}">Open the demo</a>.
      </video>
      <span class="media-label"><i class="fa-solid fa-play" aria-hidden="true"></i> On-car demo</span>
    </div>
    <div class="project-copy">
      <div class="project-kicker"><span>02</span> Robot perception · UPenn xLAB</div>
      <h3>F1TENTH Depth-Based Navigation</h3>
      <p>Built a monocular-depth perception and navigation stack combining MiDaS, rangefinder calibration, and depth-guided Follow-the-Gap control. Optimized inference with ONNX/TensorRT for edge deployment.</p>
      <div class="project-metrics">
        <div><strong>40 FPS</strong><span>Jetson Xavier NX</span></div>
        <div><strong>ToF + RGB</strong><span>sensor fusion</span></div>
      </div>
      <div class="tag-list" aria-label="Technologies"><span>OpenCV</span><span>ONNX</span><span>TensorRT</span><span>Jetson</span></div>
      <div class="project-links">
        <a href="https://github.com/hanlizhang/DepthNav">Code <span aria-hidden="true">↗</span></a>
        <a href="https://github.com/hanlizhang/DepthNav/blob/main/final-report.pdf">Report <span aria-hidden="true">↗</span></a>
        <a href="{{ '/assets/video/f1tenth_demo_web.mp4' | relative_url }}">Full video <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </article>

  <div class="project-grid">
    <article class="project-card">
      <div class="project-card-top">
        <span class="project-number">03</span>
        <span class="project-type">Visual SLAM</span>
      </div>
      <h3>Gaussian Splatting SLAM with Loop Closure</h3>
      <p>Extended MonoGS with loop closure, Gaussian-aware covisibility, pose-graph optimization, global bundle adjustment, and CUDA rasterizer visibility metrics.</p>
      <div class="impact-line"><strong>Up to 23%</strong><span>lower ATE RMSE on tested TUM RGB-D sequences</span></div>
      <div class="tag-list"><span>PyTorch</span><span>CUDA</span><span>OpenCV</span><span>3DGS</span></div>
      <a class="card-link" href="https://drive.google.com/file/d/1SHhehph7SDY5q27ETMgHr2FNV_BFI8fb/view?usp=drive_link">Read project report <span aria-hidden="true">↗</span></a>
    </article>

    <article class="project-card">
      <div class="project-card-top">
        <span class="project-number">04</span>
        <span class="project-type">LLM planning</span>
      </div>
      <h3>Task Planning &amp; Evaluation for Robot Manipulation</h3>
      <p>Supervised and evaluated a planner using structured action primitives, feedback loops, recovery logic, and retune-vs-replan decisions.</p>
      <div class="impact-line"><strong>85%</strong><span>success over 20 trials, with failure-mode analysis</span></div>
      <div class="tag-list"><span>LLM agents</span><span>Evaluation</span><span>Planning</span><span>Recovery</span></div>
      <a class="card-link" href="https://drive.google.com/file/d/1fcYz8e9UB_1xfpSe6-1Ko6UQUkYjYKsY/view?usp=drive_link">Read project report <span aria-hidden="true">↗</span></a>
    </article>
  </div>
</section>

<section class="portfolio-section experience-section" id="experience" aria-labelledby="experience-title">
  <div class="section-heading">
    <div>
      <p class="eyebrow">EXPERIENCE</p>
      <h2 id="experience-title">Research depth. Field-tested engineering.</h2>
    </div>
    <p>Experience across human-robot interaction, mobile robots, aerial systems, state estimation, and deployment debugging.</p>
  </div>

  <div class="experience-list">
    <article>
      <div class="experience-meta"><span>EPFL · LASA</span><span>Lausanne, Switzerland</span></div>
      <h3>Robotics Researcher</h3>
      <p>Researching coordination-aware modeling for multi-limb human-robot interaction, combining stable dynamical-system motion primitives with cross-limb coupling.</p>
    </article>
    <article>
      <div class="experience-meta"><span>LYF Innovation Ltd., Inc.</span><span>Philadelphia, USA</span></div>
      <h3>Robotic Engineer Intern</h3>
      <p>Built a VINS-Fusion visual-inertial state-estimation pipeline with panoramic camera and IMU data, reducing outdoor tracking error by 15%.</p>
    </article>
    <article>
      <div class="experience-meta"><span>Suzhou Beacon Robot Technology Co., Ltd.</span><span>Suzhou, China</span></div>
      <h3>Algorithm Engineer</h3>
      <p>Improved AGV localization to ±5 mm pose accuracy, reduced pose-loss events by 30%, refactored 12 ROS/C++ modules, and resolved 30+ field issues.</p>
    </article>
  </div>
</section>

<section class="portfolio-section toolkit-section" aria-labelledby="toolkit-title">
  <div class="section-heading compact">
    <div>
      <p class="eyebrow">TOOLKIT</p>
      <h2 id="toolkit-title">Built for the full robotics stack.</h2>
    </div>
  </div>
  <div class="toolkit-grid">
    <div><span>01</span><h3>Robotics</h3><p>ROS1/2, SLAM, localization, mapping, state estimation, sensor fusion</p></div>
    <div><span>02</span><h3>Planning &amp; control</h3><p>Optimal control, motion planning, trajectory optimization, dynamical systems</p></div>
    <div><span>03</span><h3>AI &amp; perception</h3><p>PyTorch, JAX, TensorFlow, OpenCV, LLM planning and evaluation</p></div>
    <div><span>04</span><h3>Deployment</h3><p>C/C++, Python, ONNX, TensorRT, NVIDIA Jetson, Linux, Docker, Git</p></div>
  </div>
</section>

<section class="resume-cta" aria-labelledby="resume-title">
  <div>
    <p class="eyebrow">ROBOTICS RÉSUMÉ</p>
    <h2 id="resume-title">Robotics experience, one focused page.</h2>
    <p>The project, paper, code, and report links inside the PDF are clickable.</p>
  </div>
  <div class="resume-links">
    <a href="{{ '/assets/pdf/Hanli_Zhang_Robotics_Core.pdf' | relative_url }}" target="_blank" rel="noopener">Robotics <span>PDF ↗</span></a>
  </div>
</section>
