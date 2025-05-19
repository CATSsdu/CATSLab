---
title: 'Optimizing Worst Case Data Freshness in RF-Powered Networked Embedded Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - zzm
  - Chenchen Fu
  - Chun Jason Xue
  - Song Han
  - zw
  - jl


# Author notes (optional)
author_notes:

date: "2023-02-10T00:00:00Z"
doi: "10.1109/TCAD.2023.3235799"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['transaction']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems(Volume 42, Issue 9, September 2023)*
publication_short: \[TCAD'23\]

abstract: Maintaining real-time data freshness plays a critical role in ensuring system correctness and optimizing the system performance in networked embedded systems (NESs). To quantitatively measure the freshness of the collected real-time data, the concept of Age of Information (AoI) has been extensively studied in recent years. This article explores how to minimize the worst case AoI of real-time data in radio-frequency (RF)-powered NESs. In such systems, one hybrid access point (HAP) transfers wireless power to a set of distributed sensor nodes, and in the meantime, receives the information from these sensor nodes. We utilize the metric of AoI to measure the data freshness and present a comprehensive analysis of the worst case AoI of the real-time data in the target system. Based on the analysis, an optimal energy schedule solution is designed to judiciously determine individual sensor nodes’ energy and time allocation to minimize the worst case AoI. Considering the varying importance of different information and sensor nodes in the target system, we further propose the optimal time and energy allocation scheme for minimizing the weighted worst case AoI. A multinode RF-powered NES testbed is implemented to validate the functional correctness of our solutions. The results show that our solutions significantly outperform the state-of-the-art solutions, reducing the worst case AoI and weighted worst case AoI by 69.3% and 75.1% on average, respectively.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10013747'
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
