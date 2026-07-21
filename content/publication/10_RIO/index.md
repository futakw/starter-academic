---
title: "Read or Ignore? A Unified Benchmark for Typographic-Attack Robustness and Text Recognition in Vision-Language Models"

# Authors
authors:
- admin
- Shojiro Yamabe
- Daiki Shiono
- Kento Sasaki
- Tsubasa Takahashi

date: "2026-09-01T00:00:00Z"
doi: ""

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
- Introduces RIO-Bench, the first benchmark unifying typographic-attack robustness and text recognition evaluation for VLMs.
- Shows that strong VLMs and existing defenses fail to balance robustness against typographic attacks and text-reading capability.
- Proposes a data-driven defense enabling adaptive selective text use, outperforming prior non-adaptive approaches.

tags: ["recent"]

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/pdf/2512.11899'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false
---

**TL;DR:** VLMs must sometimes read text in images and sometimes ignore it — but no model does both well. We propose RIO-Bench, the first benchmark unifying typographic-attack robustness and text recognition evaluation. We further introduce a data-driven defense that adaptively selects when to use in-image text, outperforming prior non-adaptive approaches.
