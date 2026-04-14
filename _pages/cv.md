---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======

PhD graduate and researcher working across computer graphics, procedural modeling, botanical reconstruction, plant geometry, and interactive systems.

* [Download PDF CV]({{ '/files/CV_Bosheng_Li.pdf' | relative_url }})
* [Google Scholar](https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en)
* [ORCID](https://orcid.org/0009-0006-6490-1184)

Research interests
======

* Computer graphics
* Procedural modeling
* Botanical and tree reconstruction
* Plant geometry and phenotyping
* Interactive systems, rendering, and tooling

Education
======

* **Ph.D., Computer Science**, Purdue University, 2025

Selected publications
======

{% assign cv_publications = site.publications | where: "cv_selected", true | sort: "date" | reverse %}
<ul>{% for post in cv_publications %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> ({{ post.date | date: "%Y" }}), <i>{{ post.venue }}</i></li>
{% endfor %}</ul>

Software and projects
======

### [EvoEngine](https://github.com/edisonlee0212/EvoEngine)

EvoEngine is a cross-platform interactive application and rendering framework that combines layered engine architecture, a data-oriented runtime, editor tooling, Vulkan-based rendering, ray tracing support, and Python bindings.

Profiles and contact
======

* Email: [li2343@purdue.edu](mailto:li2343@purdue.edu)
* Google Scholar: [scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en](https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en)
* ORCID: [0009-0006-6490-1184](https://orcid.org/0009-0006-6490-1184)
* GitHub: [github.com/edisonlee0212](https://github.com/edisonlee0212)
* LinkedIn: [bosheng-li-54a4b8177](https://www.linkedin.com/in/bosheng-li-54a4b8177)
