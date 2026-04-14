---
permalink: /
title: "Bosheng Li"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD graduate and researcher working on computer graphics, procedural modeling, botanical reconstruction, plant geometry, and interactive systems. Much of my work focuses on trees and vegetation: how to reconstruct them, simulate them, and build tools that make complex structure editable and useful.

Research
======

My recent work sits at the intersection of several areas:

* **Procedural vegetation and tree modeling**: structure, growth, volumetric detail, roots, and authoring workflows for complex botanical forms.
* **Botanical reconstruction and learned priors**: recovering tree and plant structure from images and point clouds using machine learning, geometry, and procedural representations.
* **Interactive graphics systems**: reusable rendering, editor, and simulation infrastructure for experiments, tools, and technical applications.

Selected publications
======

{% assign featured_publications = site.publications | where: "featured", true | sort: "date" | reverse %}
{% for post in featured_publications %}
* [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date: "%Y" }}), *{{ post.venue }}*
{% endfor %}

You can find the full publication list on the [publications page]({{ '/publications/' | relative_url }}) or on [Google Scholar](https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en).

Projects
======

### [EvoEngine](https://github.com/edisonlee0212/EvoEngine)

EvoEngine is my interactive application and rendering framework for Windows and Linux. It brings together layered engine architecture, data-oriented systems, editor tooling, Vulkan-based rendering, ray tracing support, and Python bindings in one reusable codebase.

The project matters to me because a large part of graphics research also depends on systems work: rendering infrastructure, tools, asset pipelines, and interactive experimentation. EvoEngine is where much of that investment lives.

Links
======

* [CV]({{ '/cv/' | relative_url }})
* [Google Scholar](https://scholar.google.com/citations?user=3-XbxIAAAAAJ&hl=en)
* [ORCID](https://orcid.org/0009-0006-6490-1184)
* [GitHub](https://github.com/edisonlee0212)
* [LinkedIn](https://www.linkedin.com/in/bosheng-li-54a4b8177)
* [Email](mailto:li2343@purdue.edu)
