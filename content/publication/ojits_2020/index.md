---
title: "Optimised Traffic Light Management Through Reinforcement Learning: Traffic State Agnostic Agent vs. Holistic Agent With Current V2I Traffic State Knowledge"
authors:
- admin
- Vincent Latzko
- Martin Reisslein
- Frank H. P. Fitzek
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-09-29T00:00:00Z"
doi: "10.1109/OJITS.2020.3027518"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In *IEEE Open Journal of Intelligent Transportation Systems (OJ-ITS)*"
publication_short: ""

abstract: Traffic light control falls into two main categories':' Agnostic systems that do not exploit knowledge of the current traffic state, e.g., the positions and velocities of vehicles approaching intersections, and holistic systems that exploit knowledge of the current traffic state. Emerging fifth generation (5G) wireless networks enable Vehicle-to-Infrastructure (V2I) communication to reliably and quickly collect the current traffic state. However, to the best of our knowledge, the optimized traffic light management without and with current traffic state information has not been compared in detail. This study fills this gap in the literature by designing representative Deep Reinforcement Learning (DRL) agents that learn the control of multiple traffic lights without and with current traffic state information. Our agnostic agent considers mainly the current phase of all traffic lights and the expired times since the last change. In addition, our holistic agent considers the positions and velocities of the vehicles approaching the intersections. We compare the agnostic and holistic agents for simulated traffic scenarios, including a road network from Barcelona, Spain. We find that the holistic system substantially increases average vehicle velocities and flow rates, while reducing CO 2 emissions, average wait and trip times, as well as a driver stress metric.

# Summary. An optional shortened abstract.
summary: We analyze the benefits of transmitting a detailed vehicle state via V2I, when optimizing traffic systems with DRL.

tags:
- Intelligent Transportation Systems
- Reinforcement Learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9208696
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# slides: example
---
This publication was awarded the [IEEE Open Journal of Intelligent Transportation Systems Best Paper Award 2020](ojits_bestpaperaward.pdf)
<!-- (https://www.linkedin.com/posts/itssieee_ojits-ieee-ieeeitss-activity-6946167314258026496-XEZ8/?trk=public_profile_like_view&originalSubdomain=de) -->
<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
