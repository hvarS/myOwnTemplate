---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Causality Detection using Sentence Embeddings in Financial Reports"
authors: [Harshvardhan Srivastava,Arka Mitra, Yugam Tiwari]
date: 2020-12-06
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-06T16:49:10+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proceedings of the 1st Joint Workshop on Financial Narrative Processing and MultiLing Financial Summarisation*"
publication_short: "FNP@COLING 2020"

abstract: "The paper describes the work that the team submitted to FinCausal 2020 Shared Task. This work is associated with the first sub-task of identifying causality in sentences. The various models used in the experiments tried to obtain a latent space representation for each of the sentences. Linear regression was performed on these representations to classify whether the sentence is causal or not. The experiments have shown BERT (Large) performed the best, giving a F1 score of 0.958, in the task of detecting the causality of sentences in financial texts and reports. The class imbalance was dealt with a modified loss function to give a better metric score for the evaluation."

# Summary. An optional shortened abstract.
summary: "This work is associated with the first sub-task of identifying causality in sentences. The various models used in the experiments tried to obtain a latent space representation for each of the sentences."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aclanthology.org/2020.fnp-1.16.pdf
url_code: https://github.com/hvarS/FinCausal-2020-Task
url_dataset: 
url_preprint: https://arxiv.org/abs/2011.07670
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
