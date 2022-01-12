---
title: "Technique of Augmenting Molecular Graph Data by Perturbating Hidden Features"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Takahiro Inoue
- Kenichi Tanaka
- Kimito Funatsu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-01-09"
doi: "10.1002/minf.202100267"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Molecular Informatics
publication_short: Mol. Inf.

abstract: Quantitative structure–property relationship models are useful in efficiently searching for molecules with desired properties in drug discovery and materials development. In recent years, many such models based on graph neural networks, showing good prediction performance, have been reported. Training graph neural networks generally require many samples, but by using a training method for a small dataset, it is possible to extract features that enable successful prediction. Herein, we design a method of augmenting graph data. In this method, random perturbations are added with a certain probability to some vertex features during message passing. We verify the proposed method's effectiveness in regression and classification tasks. It is confirmed that the proposed method is effective when the perturbation is added immediately before the readout of the graph neural network, and the effect of the data augmentation is most evident for small datasets of approximately 1000 samples.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Chemoinformatics', 'Data augmentation', 'Graph neural network', 'Structure-activity relationships', 'Virtual screening']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
