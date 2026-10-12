---
title: Twitter Image Captioning
summary: 画像から、主観やユーモアを含むツイート風の文章を生成。
tags:
- Deep learning
- Archived
date: "2021-01-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Sample output of our model
  focal_point: Smart

links:
- name: Poster PDF
  url: media/twitter_image_captioning_poster.pdf
- icon: github
  icon_pack: fab
  name: github
  url: https://github.com/futakw/Twitter_Image_Captioning
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

# slides: example
---

修士1年の授業で、画像からツイート風の文章を生成するモデルを開発しました。客観的な説明に加え、主観・曖昧さ・ユーモアを含む表現を目指しました。

Twitter APIで31アカウントから約5,000組の動物画像と文章を収集し、CNNエンコーダーとLSTMデコーダーを使用しました。STAIR Captionsで10エポック事前学習し、Twitterデータで2エポック追加学習しました。

35名へのアンケートで、自然さ・画像との対応・ユーモア・「いいね」したいかを評価しました。STAIRのみで学習したモデルを上回りましたが、人間のツイートには及びませんでした。
