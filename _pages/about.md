---
permalink: /
title: "Bosheng Li"
layout: splash
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <p class="home-kicker">Computer graphics / procedural modeling / interactive systems</p>
  <h1>I'm Bosheng Li, a PhD graduate and researcher building computational models and tools for digital vegetation.</h1>
  <p class="home-summary">
    My work spans botanical reconstruction, procedural growth, plant geometry, and interactive graphics systems. I care about models that are scientifically grounded, visually expressive, and practical for simulation, analysis, and creative tools.
  </p>
  <div class="home-link-row">
    <a class="btn btn--primary" href="{{ '/publications/' | relative_url }}">Publications</a>
    <a class="btn btn--inverse" href="{{ '/projects/' | relative_url }}">Projects</a>
    <a class="btn btn--light-outline" href="{{ '/cv/' | relative_url }}">CV</a>
    <a class="btn btn--light-outline" href="https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en">Google Scholar</a>
  </div>
</section>

<section class="home-stats">
  <div class="home-stat">
    <span class="home-stat__value">{{ site.publications | size }}</span>
    <span class="home-stat__label">verified publications on this site</span>
  </div>
  <div class="home-stat">
    <span class="home-stat__value">2025</span>
    <span class="home-stat__label">PhD completion listed by Purdue sources</span>
  </div>
  <div class="home-stat">
    <span class="home-stat__value">EvoEngine</span>
    <span class="home-stat__label">interactive application framework and rendering stack</span>
  </div>
</section>

<section class="home-section">
  <div class="home-section__header">
    <p class="home-kicker">Research directions</p>
    <h2>Where my work sits</h2>
  </div>
  <div class="home-card-grid">
    <article class="home-card">
      <h3>Procedural vegetation and tree modeling</h3>
      <p>I build models for tree structure, growth, branching, roots, and volumetric detail, with an emphasis on controllability and biological plausibility.</p>
    </article>
    <article class="home-card">
      <h3>Botanical reconstruction and learned priors</h3>
      <p>I work on recovering tree and plant structure from images and point clouds, combining procedural representations with machine learning and geometric reasoning.</p>
    </article>
    <article class="home-card">
      <h3>Interactive systems for graphics and simulation</h3>
      <p>I also spend significant time on the systems side: tooling, rendering infrastructure, editor workflows, data-oriented pipelines, and reusable frameworks for interactive applications.</p>
    </article>
  </div>
</section>

<section class="home-section">
  <div class="home-section__header">
    <p class="home-kicker">Selected work</p>
    <h2>Publication highlights</h2>
  </div>
  {% assign featured_publications = site.publications | where: "featured", true | sort: "date" | reverse %}
  <div class="home-publication-grid">
    {% for post in featured_publications limit: 4 %}
      <article class="home-publication-card">
        <p class="home-publication-card__meta">{{ post.date | date: "%Y" }} / {{ post.venue }}</p>
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt }}</p>
      </article>
    {% endfor %}
  </div>
  <p class="home-section__footer">
    The full list on this site currently covers verified publications from 2021-2025. For citations and profile metrics, see <a href="https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en">Google Scholar</a>.
  </p>
</section>

<section class="home-section home-project-spotlight">
  <div class="home-section__header">
    <p class="home-kicker">Featured project</p>
    <h2>EvoEngine</h2>
  </div>
  <p class="home-summary home-summary--compact">
    EvoEngine is my interactive application and rendering framework for Windows and Linux. It brings together layered engine architecture, data-oriented systems, editor tooling, and modern rendering features in one reusable codebase.
  </p>
  <div class="home-feature-grid">
    <div class="home-feature">
      <h3>Modular architecture</h3>
      <p>Window, render, and editor layers can be composed for desktop tools, offscreen workflows, and plugin-driven applications.</p>
    </div>
    <div class="home-feature">
      <h3>Data-oriented runtime</h3>
      <p>An ECS-style design and job system support large interactive scenes and simulation-oriented workflows.</p>
    </div>
    <div class="home-feature">
      <h3>Graphics and tooling</h3>
      <p>The framework includes Vulkan rendering, GPU-driven pipelines, ray tracing support, editor utilities, and Python bindings.</p>
    </div>
  </div>
  <div class="home-link-row">
    <a class="btn btn--primary" href="{{ '/projects/' | relative_url }}">See the project page</a>
    <a class="btn btn--inverse" href="https://github.com/edisonlee0212/EvoEngine">View repository</a>
  </div>
</section>

<section class="home-section">
  <div class="home-section__header">
    <p class="home-kicker">Contact</p>
    <h2>Find me online</h2>
  </div>
  <div class="home-inline-list">
    <a href="mailto:li2343@purdue.edu">Email</a>
    <a href="https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en">Google Scholar</a>
    <a href="https://orcid.org/0009-0006-6490-1184">ORCID</a>
    <a href="https://github.com/edisonlee0212">GitHub</a>
    <a href="https://www.linkedin.com/in/bosheng-li-54a4b8177">LinkedIn</a>
  </div>
</section>
