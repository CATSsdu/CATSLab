---
title: 'Cache-aware Task Decomposition for Efficient Intermittent Computing Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - xs
  - zw
  - Mengying Zhao
  - zzm
  - jl


# Author notes (optional)
author_notes:

date: "2024-06-23T00:00:00Z"
doi: "10.1145/3649329.3657382"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *61th ACM/IEEE Design Automation Conference*
publication_short: \[DAC'24\]

abstract: Energy harvesting offers a scalable and cost-effective power solution for IoT devices, but it introduces the challenge of frequent and unpredictable power failures due to the unstable environment. To address this, intermittent computing has been proposed, which periodically backs up the system state to non-volatile memory (NVM), enabling robust and sustainable computing even in the face of unreliable power supplies. In modern processors, write back cache is extensively utilized to enhance system performance. However, it poses a challenge during backup operations as it buffers updates to memory, potentially leading to inconsistent system states. One solution is to adopt a write-through cache, which avoids the inconsistency issue but incurs increased memory access latency for each write reference. Some existing work enforces a cache flushing before backups to maintain a consistent system state, resulting in significant backup overhead. In this paper, we point out that although cache delays updates to the main memory, it may preserve a recoverable system state in the main memory. Leveraging this characteristic, we propose a cache-aware task decomposition method that divides an application into multiple tasks, ensuring that no dirty cache lines are evicted during their execution. Furthermore, the cache-aware task decomposition maintains an unchanged memory state during the execution of each task, enabling us to parallelize the backup process with task execution and effectively hide the backup latency. Experimental results with different power traces demonstrate the effectiveness of the proposed system.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3649329.3657382'
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
