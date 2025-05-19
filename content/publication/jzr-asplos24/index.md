---
title: 'Accelerating Multi-Scalar Multiplication for Efficient Zero Knowledge Proofs with Multi-GPU Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - jzr
  - zzy
  - Jiming Xu
  - jl

# Author notes (optional)
author_notes:

date: "2024-04-27T00:00:00Z"
doi: "10.1145/3620666.3651364"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 3*
publication_short: \[ASPLOS'24\]

abstract: Zero-knowledge proof is a cryptographic primitive that allows for the validation of statements without disclosing any sensitive information, foundational in applications like verifiable outsourcing and digital currency. However, the extensive proof generation time limits its widespread adoption. Even with GPU acceleration, proof generation can still take minutes, with Multi-Scalar Multiplication (MSM) accounting for about 78.2% of the workload. To address this, we present DistMSM, a novel MSM algorithm tailored for distributed multi-GPU systems. At the algorithmic level, DistMSM adapts Pippenger's algorithm for multi-GPU setups, effectively identifying and addressing bottlenecks that emerge during scaling. At the GPU kernel level, DistMSM introduces an elliptic curve arithmetic kernel tailored for contemporary GPU architectures. It optimizes register pressure with two innovative techniques and leverages tensor cores for specific big integer multiplications. Compared to state-of-the-art MSM implementations, DistMSM offers an average 6.39× speedup across various elliptic curves and GPU counts. An MSM task that previously took seconds on a single GPU can now be completed in mere tens of milliseconds. It showcases the substantial potential and efficiency of distributed multi-GPU systems in ZKP acceleration.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3620666.3651364'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/OJarnNG6G_o?si=jtQauy-uLuz4cb4F'

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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
