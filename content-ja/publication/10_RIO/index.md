---
media_slides_path: '/media/slides/rio-eccv2026'
media_slides_count: 6
media_poster_image: '/media/publication/ECCV2026/poster-preview.jpg'
title: "Read or Ignore? A Unified Benchmark for Typographic-Attack Robustness and Text Recognition in Vision-Language Models"

# Authors
authors:
- admin
- Shojiro Yamabe
- Daiki Shiono
- Kento Sasaki
- Tsubasa Takahashi

date: "2026-09-01T00:00:00Z"
doi: "10.1007/978-3-032-37372-4_31"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ECCV 2026"
publication_short: "ECCV 2026"

abstract: "Large vision-language models (LVLMs) are vulnerable to typographic attacks—misleading text within images that overrides visual understanding. We introduce Read-or-Ignore VQA (RIO-VQA) and its benchmark RIO-Bench, a unified evaluation framework assessing when models should read text versus ignore it based on context. Our findings show that strong LVLMs and existing defenses fail to balance typographic robustness and text-reading capability. We propose a data-driven defense mechanism enabling adaptive selective text use, moving beyond previous non-adaptive approaches."

highlights:
- 画像中のテキストを選択的に読む能力を測るRIO-Benchを提案。
- Typographic 攻撃への頑健性と文字認識を同時に評価。
- 有用な文字を読み、誤解を誘う文字を無視する能力を学習。

tags: ["recent"]

# Display this page in the Featured widget?
featured: false

links: [{"name": "GitHub", "icon": "github", "icon_pack": "fab", "url": "https://github.com/turingmotors/RIO-Bench"}, {"name": "Hugging Face", "url": "https://huggingface.co/datasets/turing-motors/RIO-Bench"}]

url_paper: 'https://arxiv.org/abs/2512.11899'
url_code: ''
url_dataset: ''
url_poster: '/media/publication/ECCV2026/ECCV26_6579_ReadorIgnore_poster.pdf'
url_project: 'https://turingmotors.github.io/rio-vqa/'
url_slides: '/media/slides/rio-eccv2026/ECCV26_6579_ReadorIgnore_5min.pdf'
url_source: ''
url_video: 'https://youtu.be/W5CxnKPkTz0?si=e0-Pu1YehJilwYAs'

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false
bibliography: {"venue": "Proceedings of the European Conference on Computer Vision (ECCV 2026), Lecture Notes in Computer Science", "volume": "17048", "pages": "562–580", "doi": "10.1007/978-3-032-37372-4_31", "source": "https://link.springer.com/chapter/10.1007/978-3-032-37372-4_31", "authors": ["Futa Waseda", "Shojiro Yamabe", "Daiki Shiono", "Kento Sasaki", "Tsubasa Takahashi"], "issue": "なし", "review": "査読有", "doi_status": "未確認（会議版）", "checked": "2026-10-12", "abbreviation": "ECCV 2026", "conference_group": "Conference Proceedings", "resources": [{"label": "Project page", "url": "https://turingmotors.github.io/rio-vqa/"}, {"label": "GitHub", "url": "https://github.com/turingmotors/RIO-Bench"}, {"label": "Hugging Face", "url": "https://huggingface.co/datasets/turing-motors/RIO-Bench"}]}
---


{{< publication_media >}}
