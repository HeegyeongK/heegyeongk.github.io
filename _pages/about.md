---
permalink: /
title: false
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <p class="eyebrow">Multi-UAV systems · Aerial robotics · Cooperative perception</p>
  <h1>Cooperative UAV systems for persistent sensing</h1>
  <p class="home-lead">
    I am a PhD candidate in Computer Science at Macquarie University, supervised by Professor Richard Han.
    I develop cooperative UAV systems that maintain useful target observations despite battery limits,
    viewpoint changes, and occlusion.
  </p>
  <p class="home-sublead">
    My work spans multi-robot planning, cooperative perception, ROS-based simulation,
    computer vision, and real-world UAV experiments.
  </p>
  <div class="home-links">
    <a class="btn btn--primary" href="/research/">Research</a>
    <a class="btn" href="/publications/">Publications</a>
    <a class="btn" href="/cv/">CV</a>
  </div>
</section>

<section class="home-section">
  <div class="section-kicker">Research overview</div>
  <h2>One persistent-sensing problem, developed across four stages</h2>

  <div class="research-trajectory">
    <div class="trajectory-step">
      <div class="trajectory-label">Continuous handoff</div>
      <div class="trajectory-project">DroNet</div>
    </div>
    <div class="trajectory-arrow">→</div>
    <div class="trajectory-step">
      <div class="trajectory-label">Verified handoff</div>
      <div class="trajectory-project">PATH</div>
    </div>
    <div class="trajectory-arrow">→</div>
    <div class="trajectory-step">
      <div class="trajectory-label">Active acquisition</div>
      <div class="trajectory-project">HARP</div>
    </div>
    <div class="trajectory-arrow">→</div>
    <div class="trajectory-step">
      <div class="trajectory-label">Relay planning</div>
      <div class="trajectory-project">VisRelay</div>
    </div>
  </div>
</section>

<section class="home-section">
  <div class="section-kicker">Selected research</div>

  <article class="home-research-item">
    <div class="home-research-index">01</div>
    <div class="home-research-copy">
      <h3><a href="/research/path/">PATH — Geometry-assisted target handoff verification</a></h3>
      <p>
        Cross-view geometric verification that the receiver UAV has acquired the same physical target as the sender,
        using a projected target prior and sender-side agreement before handoff.
      </p>
      <div class="home-research-links">
        <a href="/research/path/">Project</a>
        <a href="/publications/path/">Manuscript</a>
      </div>
    </div>
  </article>

  <article class="home-research-item">
    <div class="home-research-index">02</div>
    <div class="home-research-copy">
      <h3><a href="/research/active-acquisition/">Active target acquisition during multi-UAV handoff</a></h3>
      <p>
        Receiver-side visibility recovery when a handoff stalls because the target lies outside the receiver's field of view
        or is physically occluded, while the sender continues tracking.
      </p>
      <div class="home-research-links">
        <a href="/research/active-acquisition/">Project</a>
      </div>
    </div>
  </article>

  <div class="home-more"><a href="/research/">All research →</a></div>
</section>

<section class="home-section home-two-column">
  <div>
    <div class="section-kicker">Recent news</div>
    <div class="home-news-list">
      <div class="home-news-row">
        <span class="home-news-date">Sep 2026</span>
        <span>Joined the Technical Program Committee of IEEE MSN 2026.</span>
      </div>
      <div class="home-news-row">
        <span class="home-news-date">Aug 2026</span>
        <span>Submitted PATH to IEEE Sensors Journal.</span>
      </div>
      <div class="home-news-row">
        <span class="home-news-date">Jun 2025</span>
        <span>Published <em>Continuous Marine Tracking via Autonomous UAV Handoff</em> at ACM MobiSys MAVNet.</span>
      </div>
    </div>
    <div class="home-more"><a href="/news/">All news →</a></div>
  </div>

  <div>
    <div class="section-kicker">Selected publications</div>
    <div class="home-pub-list">
      <article class="home-pub-item">
        <h3><a href="/publications/path/">PATH: Continuous Target Sensing among Autonomous Cooperative Drones</a></h3>
        <div class="home-pub-authors"><strong>Heegyeong Kim</strong>, Alice James, Avishkar Seth, Endrowednes Kuantama, Jane Williamson, Yimeng Feng, Richard Han</div>
        <div class="home-pub-venue"><em>IEEE Sensors Journal</em>, under review</div>
      </article>

      <article class="home-pub-item">
        <h3><a href="/publications/dronet/">Continuous Marine Tracking via Autonomous UAV Handoff</a></h3>
        <div class="home-pub-authors"><strong>Heegyeong Kim</strong>, Alice James, Avishkar Seth, Endrowednes Kuantama, Jane Williamson, Yimeng Feng, Richard Han</div>
        <div class="home-pub-venue"><em>ACM MobiSys MAVNet</em>, 2025</div>
      </article>
    </div>
    <div class="home-more"><a href="/publications/">All publications →</a></div>
  </div>
</section>
