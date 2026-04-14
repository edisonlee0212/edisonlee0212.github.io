---
layout: single
title: "Projects"
permalink: /projects/
author_profile: false
redirect_from:
  - /portfolio/
---

<section class="projects-hero">
  <p class="home-kicker">Flagship system</p>
  <h1>EvoEngine</h1>
  <p class="home-summary">
    EvoEngine is a cross-platform interactive application and rendering framework for Windows and Linux. It is the project where I have invested the most sustained systems work outside my publications, and it reflects how I think about reusable graphics infrastructure.
  </p>
  <div class="home-link-row">
    <a class="btn btn--primary" href="https://github.com/edisonlee0212/EvoEngine">GitHub repository</a>
    <a class="btn btn--inverse" href="{{ '/publications/' | relative_url }}">Related publications</a>
  </div>
</section>

<section class="home-section">
  <div class="home-section__header">
    <p class="home-kicker">What it includes</p>
    <h2>System capabilities</h2>
  </div>
  <div class="project-feature-grid">
    <article class="home-card">
      <h3>Layered application architecture</h3>
      <p>EvoEngine is organized around layers such as window, rendering, and editor layers, which makes it easier to reuse the framework across different application shapes and offscreen workflows.</p>
    </article>
    <article class="home-card">
      <h3>Data-oriented runtime</h3>
      <p>The framework includes an entity-component style design and job-system support for scalable scene behavior, simulation, and interactive content pipelines.</p>
    </article>
    <article class="home-card">
      <h3>Editor and asset tooling</h3>
      <p>It includes entity management, input handling, profiling, asset management, serialization, project management, and editor-facing utilities for day-to-day iteration.</p>
    </article>
    <article class="home-card">
      <h3>Modern rendering stack</h3>
      <p>Rendering features described in the repository include Vulkan support, GPU-driven rendering, deferred and forward pipelines, post-processing, shadows, environmental lighting, skeletal animation, and ray tracing.</p>
    </article>
    <article class="home-card">
      <h3>Plugin and Python support</h3>
      <p>The codebase supports plugins and Python bindings, which makes it useful both as a graphics foundation and as a platform for experimentation.</p>
    </article>
    <article class="home-card">
      <h3>Built for research and iteration</h3>
      <p>EvoEngine bridges rendering systems, tools, and experiments, which is why it belongs on this site alongside the publication record rather than as a secondary link.</p>
    </article>
  </div>
</section>

<section class="home-section">
  <div class="home-section__header">
    <p class="home-kicker">Why it matters</p>
    <h2>Research and systems in one place</h2>
  </div>
  <p>
    A large part of my work lives at the intersection of research ideas and the infrastructure needed to test them. EvoEngine represents that systems investment: a reusable framework for rendering, tooling, and interaction that can support more specialized graphics and modeling work over time.
  </p>
</section>
