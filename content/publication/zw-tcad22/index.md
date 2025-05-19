---
title: 'Adaptive Task-Based Intermittent Computing System With Parallel State Backup'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - zw
  - Qianling Zhang
  - Mingsong Lv
  - Songran Liu
  - zzm
  - Qiulin Chen
  - Nan Guan
  - jl


# Author notes (optional)
author_notes:

date: "2022-10-12T00:00:00Z"
doi: "10.1109/TCAD.2022.3213989"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['transaction']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems(Volume 42, Issue 6, June 2023)*
publication_short: \[TCAD'22\]

abstract: Energy harvesting promises to power billions of Internet of Things devices without being restricted by battery life. Since the energy harvester generally outputs weak and unstable energy, the system may suffer frequent and unpredictable power failures, thus falling into cyclically reboots without forward progress. The task-based intermittent computing system which periodically backs up system states into nonvolatile memory (NVM) is proposed to solve the nonprogress problem, with the nontrivial cost of frequent backups. How to reduce the backup overhead becomes a major research problem for intermittent computing. This article, for the first time, proposes to parallelize state backup and program execution with asynchronous direct memory access (DMA) to hide the backup latency into the program’s execution. But, straightforwardly executing the state backup and the program in parallel may cause an inconsistent system state. In specific, the system state may be modified by the program during backup, and therefore may be backed up incorrectly and further cause the system to deliver an incorrect computation result. We make a deep analysis on the system behavior and observe that, although the system state may be backed up incorrectly, the incorrect backup will be covered by the subsequent correct backups soon as the backup operations are performed frequently. In addition, only a small part of variables among all the program states may cause incorrect computation result. So, in this article, we aggressively allow incorrect backups to occur and propose a backup error detection method and a fault-tolerant backup management to guarantee the correctness of the system’s execution. To augment the parallel backup method, an adaptive execution method is further proposed to reduce the number of backups and balance the ratio between task execution time and backup latency. We design a run-time system to implement the proposed approach, and experimental results conducted on an STM32F7-based platform show that the proposed method can achieve a $2.6\times $ average speedup.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9916309'
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
