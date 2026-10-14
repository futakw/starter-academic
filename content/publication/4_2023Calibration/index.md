---
media_slides_path: '/media/slides/dac-icml2023'
media_slides_count: 7
media_poster_image: '/media/publication/ICML2023DAC/poster_ICML2023_DAC.png'
title: "Beyond In-Domain Scenarios: Robust Density-Aware Calibration"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Christian Tomani
- admin
- Yuesong Shen
- Daniel Cremers

# Author notes (optional)

author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-07-23T00:00:00Z"
doi: "10.48550/arXiv.2302.05118"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ICML 2023
publication_short: ICML 2023

abstract: "Calibrating deep learning models to yield uncertainty-aware predictions is crucial as deep neural networks get increasingly deployed in safety-critical applications. While existing post-hoc calibration methods achieve impressive results on in-domain test datasets, they are limited by their inability to yield reliable uncertainty estimates in domain-shift and out-of-domain (OOD) scenarios. We aim to bridge this gap by proposing DAC, an accuracy-preserving as well as Density-Aware Calibration method based on k-nearest-neighbors (KNN). In contrast to existing post-hoc methods, we utilize hidden layers of classifiers as a source for uncertainty-related information and study their importance. We show that DAC is a generic method that can readily be combined with state-of-the-art post-hoc methods. DAC boosts the robustness of calibration performance in domain-shift and OOD, while maintaining excellent in-domain predictive uncertainty estimates. We demonstrate that DAC leads to consistently better calibration across a large number of model architectures, datasets, and metrics. Additionally, we show that DAC improves calibration substantially on recent large-scale neural networks pre-trained on vast amounts of data."
highlights:
- Calibrates confidence using local feature density.
- Improves reliability under domain shifts and OOD inputs.
- Maintains performance across models and datasets.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["recent"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: GitHub
  icon: github
  icon_pack: fab
  url: https://github.com/futakw/DensityAwareCalibration

url_paper: 'https://arxiv.org/abs/2302.05118'
url_code: ''
url_dataset: ''
url_poster: '/media/publication/ICML2023DAC/poster_ICML2023_DAC.png'
url_project: ''
url_slides: '/media/publication/ICML2023DAC/ICML2023_DAC_final.pdf'
url_source: ''
url_video: 'https://slideslive.com/39003814/beyond-indomain-scenarios-robust-densityaware-calibration?ref=speaker-67105'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
bibliography: {"venue": "Proceedings of the 40th International Conference on Machine Learning (ICML 2023), Proceedings of Machine Learning Research", "volume": "202", "pages": "34344–34368", "source": "https://proceedings.mlr.press/v202/tomani23a.html", "authors": ["Christian Tomani", "Futa Kai Waseda", "Yuesong Shen", "Daniel Cremers"], "issue": "なし", "review": "査読有", "doi_status": "未確認（会議版）", "checked": "2026-10-12", "abbreviation": "ICML 2023", "conference_group": "Conference Proceedings", "equal_contribution": [0, 1], "resources": [{"label": "GitHub", "url": "https://github.com/futakw/DensityAwareCalibration"}, {"label": "Poster", "url": "/media/publication/ICML2023DAC/poster_ICML2023_DAC.png"}, {"label": "Slides", "url": "/media/publication/ICML2023DAC/ICML2023_DAC_final.pdf"}, {"label": "Video", "url": "https://slideslive.com/39003814/beyond-indomain-scenarios-robust-densityaware-calibration?ref=speaker-67105"}]}
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

{{< publication_media >}}
