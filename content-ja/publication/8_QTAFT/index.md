---
media_slides_path: '/media/slides/qtaft-acmmm2025'
media_slides_count: 6
title: "Quality Text, Robust Vision: The Role of Language in Enhancing Visual Robustness of Vision-Language Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Saku Sugawara
- Isao Echizen

# Author notes (optional)

# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-10-27T00:00:00Z"
doi: "10.1145/3746027.3755623"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Multimedia 2025"
publication_short: "ACM MM 2025"

abstract: "Defending pre-trained vision-language models (VLMs), such as CLIP, against adversarial attacks is crucial, as these models are widely used in diverse zero-shot tasks, including image classification. However, existing adversarial training (AT) methods for robust fine-tuning largely overlook the role of language in enhancing visual robustness. Specifically, (1) supervised AT methods rely on short texts (e.g., class labels) to generate adversarial perturbations, leading to overfitting to object classes in the training data, and (2) unsupervised AT avoids this overfitting but remains suboptimal against practical text-guided adversarial attacks due to its lack of semantic guidance. To address these limitations, we propose Quality Text-guided Adversarial Fine-Tuning (QT-AFT), which leverages high-quality captions during training to guide adversarial examples away from diverse semantics present in images. This enables the visual encoder to robustly recognize a broader range of image features even under adversarial noise, thereby enhancing robustness across diverse downstream tasks. QT-AFT overcomes the key weaknesses of prior methods -- overfitting in supervised AT and lack of semantic awareness in unsupervised AT -- achieving state-of-the-art zero-shot adversarial robustness and clean accuracy, evaluated across 16 zero-shot datasets. Furthermore, our comprehensive study uncovers several key insights into the role of language in enhancing vision robustness; for example, describing object properties in addition to object names further enhances zero-shot robustness. Our findings point to an urgent direction for future work -- centering high-quality linguistic supervision in robust visual representation learning."
highlights:
- 高品質なキャプションで敵対的学習を誘導。
- 豊かな言語教師信号により多様な意味に対する頑健性を向上。
- 16データセットでゼロショットの頑健性と精度を改善。

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["recent"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links: [{"name": "GitHub", "icon": "github", "icon_pack": "fab", "url": "https://github.com/futakw/QTAFT"}, {"name": "Hugging Face", "url": "https://huggingface.co/futakw/clip-qt-aft"}]

url_paper: 'https://arxiv.org/abs/2507.16257'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/media/slides/qtaft-acmmm2025/QualityTextRobustVision-3min.pdf'
url_source: ''
url_video: 'https://youtu.be/kzgIE-c-AEk'

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
bibliography: {"venue": "Proceedings of the 33rd ACM International Conference on Multimedia (ACM MM 2025)", "pages": "4808–4816", "doi": "10.1145/3746027.3755623", "source": "https://dl.acm.org/doi/10.1145/3746027.3755623", "authors": ["Futa Waseda", "Saku Sugawara", "Isao Echizen"], "volume": "なし", "issue": "なし", "review": "査読有", "doi_status": "未確認（会議版）", "checked": "2026-10-12", "abbreviation": "ACM MM 2025", "conference_group": "Conference Proceedings", "resources": [{"label": "GitHub", "url": "https://github.com/futakw/QTAFT"}, {"label": "Hugging Face", "url": "https://huggingface.co/futakw/clip-qt-aft"}]}
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
