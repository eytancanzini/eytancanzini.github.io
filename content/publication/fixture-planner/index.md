---
title: "Decision Making For Multi-Robot Fixture Planning Using Multi-Agent Reinforcement Learning"
authors:
- admin
- Marc Auledas-Noguera
- Simon Pope
- Ashutosh Tiwari
date: "2024-02-11T00:00:00Z"
doi: "10.1109/TASE.2024.3424677"

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Automation Science & Engineering"
publication_short: "IEEE T-ASE"

abstract: Within the realm of flexible manufacturing, fixture layout planning allows manufacturers to rapidly deploy optimal fixturing plans that can reduce surface deformation that leads to crack propagation in components during manufacturing tasks. The role of fixture layout planning has evolved from being performed by experienced engineers to computational methods due to the number of possible configurations for components. Current optimisation methods commonly fall into sub-optimal positions due to the existence of local optima, with data-driven machine learning techniques relying on costly to collect labelled training data. In this paper, we present a framework for multi-agent reinforcement learning with team decision theory to find optimal fixturing plans for manufacturing tasks. We demonstrate our approach on two representative aerospace components with complex geometries across a set of drilling tasks, illustrating the capabilities of our method; we will compare this against state of the art methods to showcase our method's improvement at finding optimal fixturing plans with 3 times the improvement in deformation control within tolerance bounds.

# Summary. An optional shortened abstract.
summary: To create optimal fixturing plans for autonomous manufacturing, we combine a team theoretic approach to understanding optima with reinforcement learning to find fixturing plans.

tags:
- Multi-Agent Systems
- Reinforcement Learning

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://doi.org/10.1109/TASE.2024.3424677
url_code: 'https://github.com/ManufacturingInformatics/marl_fixture_planner'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of the multi-agent approach for determining optimal fixture plans using reinforcement learning.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
