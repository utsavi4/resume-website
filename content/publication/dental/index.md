---
title: 'An Attention U-Net for Semantic Segmentation of Dental Panoramic X-ray images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Kush Vora
  - Deepak Sharma

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-12-02T00:00:00Z'
doi: '10.1109/ICAST55766.2022.10039666'

# Schedule page publish date (NOT publication's date).
# publishDate: '2022-12-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 5th IEEE International Conference on Advances in Science and Technology 2022
publication_short: In IEEE

abstract: Dental disorders can lead to serious implications such as heart attack or strokes if not diagnosed and treated early. The diagnosis of these disorders differs from dentist to dentist due to differences in perception, poor x-ray quality because of noise, and different types of patients. As a result, there is an urgent need to create automated, AI-driven diagnostic solutions for dental disorders. Deep learning solutions have shown outstanding results in automated medical image analysis tasks. Our work proposes a U-Net with attention blocks to segment teeth from dental panoramic X-rays. The proposed Attention U-Net consists of four encoding and decoding blocks and achieved Dice Coefficient, IOU score, Specificity, and F1 Score of 0.9318, 0.8724, 0.9910, and 0.9379, respectively. The Attention U-Net achieves a 1.7% better Dice Coefficient score and 2.9% better IOU (Intersection Over Union) score than one of the best segmentation models, the U-Net. The segmented output can be used in computer-aided diagnostic (CAD) systems to detect various mouth disorders, helping the dentist diagnose the problem efficiently and accurately.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10039666'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'https://data.mendeley.com/datasets/hxt48yk462/2'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---