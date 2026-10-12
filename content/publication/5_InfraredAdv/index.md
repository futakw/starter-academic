---
title: "Defending Against Physical Adversarial Patch Attacks on Infrared Human Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lukas Strack
- admin
- Huy H. Nguyen
- Yinqiang Zheng
- Isao Echizen

# Author notes (optional)

author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-10-27T00:00:00Z"
doi: "10.1109/ICIP51287.2024.10647435"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICIP 2024"
publication_short: "ICIP 2024"

abstract: "Infrared detection is an emerging technique for safety-critical tasks owing to its remarkable anti-interference capability. However, recent studies have revealed that it is vulnerable to physically-realizable adversarial patches, posing risks in its real-world applications. To address this problem, we are the first to investigate defense strategies against adversarial patch attacks on infrared detection, especially human detection. We have devised a straightforward defense strategy, patch-based occlusion-aware detection (POD), which efficiently augments training samples with random patches and subsequently detects them. POD not only robustly detects people but also identifies adversarial patch locations. Surprisingly, while being extremely computationally efficient, POD easily generalizes to state-of-the-art adversarial patch attacks that are unseen during training. Furthermore, POD improves detection precision even in a clean (i.e., no-patch) situation due to the data augmentation effect. Evaluation demonstrated that POD is robust to adversarial patches of various shapes and sizes. The effectiveness of our baseline approach is shown to be a viable defense mechanism for real-world infrared human detection systems, paving the way for exploring future research directions."
highlights:
- Proposes the first defense against physical patches on infrared human detection.
- Detects adversarial patches through patch-aware training.
- Improves unseen-patch robustness and clean-image precision.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["recent"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2309.15519.pdf'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
bibliography: {"venue": "2024 IEEE International Conference on Image Processing (ICIP 2024)", "pages": "3896–3902", "doi": "10.1109/ICIP51287.2024.10647435", "source": "https://ieeexplore.ieee.org/document/10647435", "authors": ["Lukas Strack", "Futa Waseda", "Huy H. Nguyen", "Yinqiang Zheng", "Isao Echizen"], "volume": "なし", "issue": "なし", "review": "査読有", "doi_status": "未確認（会議版）", "checked": "2026-10-12", "abbreviation": "ICIP 2024", "conference_group": "Conference Proceedings", "equal_contribution": [0, 1]}
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
