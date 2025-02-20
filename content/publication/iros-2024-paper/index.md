---
title: 'Generating Continuous Paths On Learned Constraint Manifolds Using Policy Search'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Simon Pope
  - Ashutosh Tiwari

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2024-10-10T00:00:00Z'
doi: '10.1109/IROS58592.2024.10802531'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2024*
publication_short: In *IROS 2024*

abstract: Many robotic manipulation tasks are constrained due to kinematic limitations placed on the object being manipulated. This increases the complexity of manipulation tasks that operate in high dimensions, leading to increased risk that sampling based planners are unable to find optimal solutions. Whilst trajectory optimisation methods provide guaranteed optimal solutions when implementing constraints, they only provide locally optimal solutions in sequential decision-making and struggle to provide globally optimal paths. These constraints can be incorporated into the probabilistic latent spaces by using demonstrations that satisfy the constraint function. However whenever constraints change or a manipulator must perform different tasks the network must be retrained to accommodate the new constraints. In this paper, we provide an approach that allows the training of a single learned manifold that can be augmented to determine the constraint manifold for the manipulation task. Using this manifold, the geodesic between two points can be computed using policy search to solve the cost function associated with the geodesic curve length Lγ. We provide comparisons in terms of path length against popular path planning algorithms with different kinematic constraints, demonstrating our method’s ability to find optimal shortest paths on constraint manifolds.

# Summary. An optional shortened abstract.
summary: By exploiting elements of Riemannian geometry, we can find embedded constraint manifolds and develop continuous paths across them

tags:
 - Planning
 - Geometry

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprints.whiterose.ac.uk/221710/'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1109/IROS58592.2024.10802531'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
slides: []
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
