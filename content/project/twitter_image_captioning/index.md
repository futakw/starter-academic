---
title: Twitter Image Captioning
summary: Made a model which outputs text from a image like human tweets, using Encoder-Decoder Model. Application of image captioning technique.
tags:
- Deep learning
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

This work was done in the class activity at the university when I was a first-year master's student.

We aimed to generate tweet-like text from an input image.

The difference between the general image captioning task is large. In the image captioning task, the purpose of the deep learning model is to explain the input image precisely and objectively. On the other hand, tweets are allowed to be subjective, vague, or humorous. Tweets can be diverse.

We first constructed Twitter Dataset using Twitter API. We collected about 5000 pairs of images and texts from 31 Twitter accounts. In this work, we only collected tweets of animals.

For model, we use Encoder(CNN)-Decoder(LSTM) model. In the training phase, we first pre-trained model by STAIR captions dataset for 10 epochs and then finetuned by Twitter dataset for 2 epochs.

For evaluation, we took a questionnaire from 35 participants. In the questionnaire, the naturalness of texts, the correspondence of image and text, humor, whether you want to LIKE the tweet were asked. The results showed that our model performed better than a model trained only by the STAIR dataset, yet it still loses to human's real tweet.


Keywords.
- Twitter API
- python
- pytorch
- Image Captioning