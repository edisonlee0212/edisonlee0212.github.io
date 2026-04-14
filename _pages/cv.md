---
layout: single
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

<div class="cv-summary">
  <p class="home-kicker">Summary CV</p>
  <p>
    I am a PhD graduate and researcher working across computer graphics, procedural modeling, botanical reconstruction, plant geometry, and interactive systems.
  </p>
  <div class="cv-actions">
    <a class="btn btn--primary" href="{{ '/files/CV_Bosheng_Li.pdf' | relative_url }}">Download PDF CV</a>
    <a class="btn btn--inverse" href="{{ '/publications/' | relative_url }}">View publications</a>
    <a class="btn btn--light-outline" href="https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en">Google Scholar</a>
  </div>
</div>

## Research Interests

- Computer graphics
- Procedural modeling
- Botanical and tree reconstruction
- Plant geometry and phenotyping
- Interactive systems, rendering, and tooling

## Education

- **Ph.D., Computer Science**, Purdue University, 2025

## Selected Publications

{% assign cv_publications = site.publications | where: "cv_selected", true | sort: "date" | reverse %}
{% for post in cv_publications %}
- [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date: "%Y" }}), *{{ post.venue }}*
{% endfor %}

## Software and Projects

### [EvoEngine](https://github.com/edisonlee0212/EvoEngine)

EvoEngine is a cross-platform interactive application and rendering framework that combines layered engine architecture, a data-oriented runtime, editor tooling, Vulkan-based rendering, ray tracing support, and Python bindings. It serves as a foundation for graphics experiments, tools, and interactive workflows.

## Profiles and Links

- Email: [li2343@purdue.edu](mailto:li2343@purdue.edu)
- Google Scholar: [scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en](https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en)
- ORCID: [0009-0006-6490-1184](https://orcid.org/0009-0006-6490-1184)
- GitHub: [github.com/edisonlee0212](https://github.com/edisonlee0212)
- LinkedIn: [bosheng-li-54a4b8177](https://www.linkedin.com/in/bosheng-li-54a4b8177)
