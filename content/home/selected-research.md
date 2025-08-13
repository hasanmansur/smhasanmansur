---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 35

title: Selected Research
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Multimodal Code Summarization
    company: Principal Contributor
    company_url:
    company_logo:
    location:
    date_start: '2024-01-01'
    date_end: ''
    description: |2-
        - Goal: To investigate on Multimodal‑LLMs capabilities in capturing UI semantics for code summarization.
        - Automated the data extraction pipeline to collect and map multi-modal data (code, comment, UI) from open-source app repositories.
        - Lead the team to develop ground truth code summaries by augmenting UI information.
        - Formulated the design of experiments that include different prompt techniques, input modalities and LLMs.
        - Developed the pipeline for both lexical and semantic similarity based quantitative evaluation.
  - title: AidUI
    company: Principal Contributor
    company_url:
    company_logo:
    location: Published in ICSE'23
    date_start: '2021-01-01'
    date_end: '2022-12-31'
    description: |2-
        - [paper link](https://arxiv.org/abs/2303.06782), [project repo](https://github.com/SageSELab/AidUI)
        - AidUI is an automated approach to detect and localize deceptive design patterns on UIs.
        - Developed a unified taxonomy and a set of heuristic rules to detect visual‑textual cues that signify the presence of deceptive UI design patterns.
        - Automated the data pipeline to extract UIs from publicly available app usage videos and screenshots by prior studies.
        - Designed and developed an approach that leverages computer vision and NLP techniques to detect different deceptive patterns on UI.
        - Implemented an automated evaluation pipeline. Dockerized and published research artifacts in a public repository.
  - title: MotorEase
    company: Co-Contributor
    company_url:
    company_logo:
    location: Published in ICSE'24
    date_start: '2022-05-01'
    date_end: '2023-05-31'
    description: |2-
        - [paper link](https://arxiv.org/abs/2403.13690), [project repo](https://github.com/SageSELab/MotorEase)
        - MotorEase is an approach to detect motor‑impairment accessibility violations in app UIs.
        - Developed the initial prototype of the “Semantic Text Matching” component of the automated approach.
        - Collaborated with the lead contributor on labeling and curation of the dataset.

design:
  columns: '2'
---
