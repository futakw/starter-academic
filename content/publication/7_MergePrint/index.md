---
title: "[ACL'25 Main] MergePrint: Merge-Resistant Fingerprints for Robust Black-box Ownership Verification of Large Language Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shojiro Yamabe*
- Futa Waseda*
- Tsubasa Takahashi
- Koki Wataoka

# Author notes (optional)

# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-05-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACL 2025 Main"
publication_short: "ACL 2025 Main"

abstract: "Protecting the intellectual property of Large Language Models (LLMs) has become increasingly critical due to the high cost of training. Model merging, which integrates multiple expert models into a single multi-task model, introduces a novel risk of unauthorized use of LLMs due to its efficient merging process. While fingerprinting techniques have been proposed for verifying model ownership, their resistance to model merging remains unexplored. To address this gap, we propose a novel fingerprinting method, MergePrint, which embeds robust fingerprints capable of surviving model merging. MergePrint enables black-box ownership verification, where owners only need to check if a model produces target outputs for specific fingerprint inputs, without accessing model weights or intermediate outputs. By optimizing against a pseudo-merged model that simulates merged behavior, MergePrint ensures fingerprints that remain detectable after merging. Additionally, to minimize performance degradation, we pre-optimize the fingerprint inputs. MergePrint pioneers a practical solution for black-box ownership verification, protecting LLMs from misappropriation via merging, while also excelling in resistance to broader model theft threats."

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2410.08604v4'
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
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
