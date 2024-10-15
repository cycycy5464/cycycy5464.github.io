---
title: "EAN: Edge-aware Networks for Image Manipulation Localization"
authors:
- admin
date: "2024-10-08T00:00:00Z"
doi: "10.1109/TCSVT.2024.3473933"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Image manipulation has sparked widespread concern due to its potential security threats on the Internet. The boundary between the authentic and manipulated region exhibits artifacts in image manipulation localization (IML). These artifacts are more pronounced in heterogeneous image splicing and homogeneous image copy-move manipulation, while they are more subtle in removal and inpainting manipulated images. However, existing methods for image manipulation detection tend to capture boundary artifacts via explicit edge features and have limitations in effectively addressing subtle artifacts. Besides, feature redundancy caused by the powerful feature extraction capability of large models may prevent accurate identification of manipulated artifacts, exhibiting a high false-positive rate. To solve these problems, we propose a novel edge-aware network (EAN) to capture boundary artifacts effectively. This network treats the image manipulation localization problem as a segmentation problem inside and outside the boundary. In EAN, we develop an edge-aware mechanism to refine implicit and explicit edge features by the interaction of adjacent features. This approach directs the encoder to prioritize the desired edge information. Also, we design a multi-feature fusion strategy combined with an improved attention mechanism to enhance key feature representation significantly for mitigating the effects of feature redundancy. We perform thorough experiments on diverse datasets, and the outcomes confirm the efficacy of the suggested approach, surpassing leading manipulation localization techniques in the majority of scenarios.

# Summary. An optional shortened abstract.
summary: A novel Edge-aware Network for Image Manipulation Localization, which treats the image manipulation localization problem as a segmentation problem inside and outside the boundary.

# tags:
# - Large Language Models

featured: true

links:
# - name: Custom Link
#   url: https://ieeexplore.ieee.org/document/10705343
url_pdf: https://ieeexplore.ieee.org/document/10705343
url_code: 'https://github.com/cycycy5464/EAN-Edge-Aware-Net'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
