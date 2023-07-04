---
title: 'Optimizing Edge SLAM: Judicious Parameter Settings and Parallelized Map Updates'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Peter Sossalla
  - Johannes Hofer
  - Justus Rischke
  - admin
  - Giang T. Nguyen
  - Martin Reisslein
  - Frank H. P. Fitzek

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-12-04T00:00:00Z'
doi: '10.1109/GLOBECOM48099.2022.10001128'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *IEEE Global Communications Conference (GLOBECOM)*"
# publication_short:

abstract: Edge Simultaneous Localization and Mapping (SLAM) retains only the tracking on the mobile device, while offloading the compute-intensive local mapping and loop close to edge computing. Existing Edge SLAM approaches incur relatively high delays for offloading, resulting in high failure probabilities, i.e., low reliability, for commonly used public SLAM datasets. We discovered that two parameters which had not previously been studied in detail, namely the number of features and the number of keyframes that are bundled for a local map update, play a critical role in the offloading delay. Also, previous approaches updated the local map in the mobile device in a serial manner, incurring map update latencies. We study the numbers of features and bundled keyframes in detail and we parallelize the local map update. We find that judicious parameter settings, namely relatively small numbers of features (750 per frame) and bundled keyframes (1, i.e., effectively no bundling), reduce the map update latency to less than half compared to the previously common settings (1000 features per frame and 6 keyframes used for a map update). For a low network latency of 20ms, these judicious parameter settings in conjunction with our parallelized local map updating, reduce the 79% failure rate of the previous Edge SLAM systems down to 2%.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
