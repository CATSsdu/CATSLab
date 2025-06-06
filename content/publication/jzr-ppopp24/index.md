---
title: 'POSTER: Accelerating High-Precision Integer Multiplication used in Cryptosystems with GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - jzr
  - Zhaorui Zhang
  - Jiming Xu
  - jl

# Author notes (optional)
author_notes:

date: "2024-02-20T00:00:00Z"
doi: "10.1145/3627535.3638495"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming*
publication_short: \[PPoPP'24\]

abstract: High-precision integer multiplication is crucial in privacy-preserving computational techniques but poses acceleration challenges on GPUs due to its complexity and the diverse bit lengths in cryptosystems. This paper introduces GIM, an efficient high-precision integer multiplication algorithm accelerated with GPUs. It employs a novel segmented integer multiplication algorithm that separates implementation details from bit length, facilitating code optimizations. We also present a computation diagram to analyze parallelization strategies, leading to a series of enhancements. Experiments demonstrate that this approach achieves a 4.47× speedup over the commonly used baseline.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3627535.3638495'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
