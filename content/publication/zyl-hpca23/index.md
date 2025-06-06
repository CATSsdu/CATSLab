---
title: 'FxHENN: FPGA-based acceleration framework for homomorphic encrypted CNN inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yilan Zhu
  - Xinyao Wang
  - jl
  - Shanqing Guo

# Author notes (optional)
author_notes:

date: "2023-02-25T00:00:00Z"
doi: "10.1109/HPCA56546.2023.10071133"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Symposium on High-Performance Computer Architecture*
publication_short: \[HPCA'23\]

abstract: Fully homomorphic encryption (FHE) is a promising data privacy solution for machine learning, which allows the inference to be performed with encrypted data. However, it typically leads to 5-6 orders of magnitude higher computation and storage overhead. This paper proposes the first full-fledged FPGA acceleration framework for FHE-based convolution neural network (HE-CNN) inference. We then design parameterized HE operation modules with intra- and inter- HE-CNN layer resource management based on FPGA high-level synthesis (HLS) design flow. With sophisticated resource and performance modeling of the HE operation modules, the proposed FxHENN framework automatically performs design space exploration to determine the optimized resource provisioning and generates the accelerator circuit for a given HE-CNN model on a target FPGA device. Compared with the state-of-the-art CPU-based HE-CNN inference solution, FxHENN achieves up to 13.49X speedup of inference latency, and 1187.12X energy efficiency. Meanwhile, given this is the first attempt in the literature on FPGA acceleration of fullfledged non-interactive HE-CNN inference, our results obtained on low-power FPGA devices demonstrate HE-CNN inference for edge and embedded computing is practical.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10071133'
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
