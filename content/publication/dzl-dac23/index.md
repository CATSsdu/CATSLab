---
title: 'Accelerating DNN Inference with Heterogeneous Multi-DPU Engines'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zelin Du
  - zw
  - zzm
  - Zili Shao
  - jl


# Author notes (optional)
author_notes:

date: "2023-09-13T00:00:00Z"
doi: "10.1109/DAC56929.2023.10247675"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *60th ACM/IEEE Design Automation Conference*
publication_short: \[DAC'23\]

abstract: The Deep Learning Processor (DPU) programmable engine released by the official Xilinx Vitis AI toolchain has become one of the commercial off-the-shelf (COTS) solutions for Convolutional Neural Networks (CNNs) inference on Xilinx FPGAs. While modern FPGA devices generally have enough hardware resources to accommodate multi-DPUs simultaneously, the Xilinx toolchain currently only supports the deployment of multiple homogeneous DPUs engines that running independent inference tasks (task-level parallelism). In this work, we demonstrate that deployment of multiple heterogeneous DPU engines makes better resource efficiency for a given FPGA device. Moreover, we show that pipelined execution of a CNN inference task over heterogeneous multi-DPU engines may further improve overall inference throughput with carefully designed CNN layers-to-DPU mapping and scheduling. Finally, for a given CNN model and an FPGA device, we propose a comprehensive framework that automatically determines the optimal heterogeneous DPU deployment, and adaptively chooses the execution scheme between task-level and pipelined parallelism. Compared with the state-of-the-art solution with homogeneous multi-DPU engines and network-level parallelism, the proposed framework shows an average improvement of 13% (up-to 19%) and 6.6% (up-to 10%) on the Xilinx Zynq UltraScale+ MPSoC ZCU104 and ZCU102 platforms, respectively.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10247793'
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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
