---
title: 'Hybrid CNN-LSTM network to detect Dysarthria using Mel-Frequency Cepstral Coefficients'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kush Vora
  - admin
  - Darshil Mehta
  - Deepak Sharma

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-12-03T00:00:00Z'
doi: '10.1109/ICAST55766.2022.10039514'

# Schedule page publish date (NOT publication's date).
# publishDate: '2022-12-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 5th IEEE International Conference on Advances in Science and Technology 2022
publication_short: In IEEE

abstract: Dysarthria is a speech problem acquired at birth due to cerebral palsy (CP) or developed after severe brain damage. Dysarthria affects more than 70% of Parkinson's patients and 10% to 65% of people with traumatic brain injury. It is critical to detect dysarthria and other voice speech difficulties early to diagnose the underlying cause. Intelligent systems capable of identifying dysarthria with incredible precision have been developed using audio processing techniques and various deep learning models. This paper presents a hybrid CNN-LSTM model for classifying patients with dysarthria using audio recordings. The CNN-LSTM combination helps capture spatial and temporal information where CNN acts as a feature extractor while LSTM functions as a classifier. The proposed model was trained on the publicly available 9184 audio recordings from the TORGO dataset, and various audio augmentation techniques were employed to generate synthetic data. A total of 128 features were extracted using Mel Frequency Cepstral Coefficients (MFCC) and fed into the architecture as inputs. The K-fold cross-validation technique was used to avoid overfitting and increase the generalization capability of the model. The proposed architecture achieved a state-of-the-art 99.59% accuracy on the dataset. The presented work will minimize the workload of speech pathologists and help them detect dysarthria precisely and effectively.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10039514'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'http://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html'
url_poster: ''
url_project: ''
url_slides: ''
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