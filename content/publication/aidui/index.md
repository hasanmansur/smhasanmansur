---
title: 'AidUI: Toward Automated Recognition of Dark Patterns in User Interfaces'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sabiha Salma
  - Damilola Awofisayo
  - Kevin Moran

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-12-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 45th IEEE/ACM International Conference on Software Engineering (ICSE 2023), Melbourne, Australia, May 14th-20th, 2023*
publication_short: In *The 45th IEEE/ACM International Conference on Software Engineering (ICSE 2023), Melbourne, Australia, May 14th-20th, 2023*

abstract: Past studies have illustrated the prevalence of UI dark patterns, or user interfaces that can lead end-users toward (unknowingly) taking actions that they may not have intended. Such deceptive UI designs can result in adverse effects on end users, such as oversharing personal information or financial loss. While significant research progress has been made toward the development of dark pattern taxonomies, developers and users currently lack guidance to help recognize, avoid, and navigate these often subtle design motifs. However, automated recognition of dark patterns is a challenging task, as the instantiation of a single type of pattern can take many forms, leading to significant variability.
In this paper, we take the first step toward understanding the extent to which common UI dark patterns can be automatically recognized in modern software applications. To do this, we introduce AidUI, a novel automated approach that uses computer vision and natural language processing techniques to recognize a set of visual and textual cues in application screenshots that signify the presence of ten unique UI dark patterns, allowing for their detection, classification, and localization. To evaluate our approach, we have constructed ContextDP, the current largest dataset of fully-localized UI dark patterns that spans 175 mobile and 83 web UI screenshots containing 301 dark pattern instances. The results of our evaluation illustrate that AidUI achieves an overall precision of 0.66, recall of 0.67, F1-score of 0.65 in detecting dark pattern instances, reports few false positives, and is able to localize detected patterns with an IoU score of ~0.84. Furthermore, a significant subset of our studied dark patterns can be detected quite reliably (F1 score of over 0.82), and future research directions may allow for improved detection of additional patterns.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2303.06782'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/SageSELab/AidUI'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

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
slides:
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
 -->
