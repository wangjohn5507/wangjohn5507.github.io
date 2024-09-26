---
# Display name
title: Chung-Yu Wang 

# Name pronunciation (optional)
name_pronunciation:

# Full name (for SEO)
first_name: Chung-Yu
last_name: Wang

# Status emoji
status:
  icon: 💪

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role:

# Organizations/Affiliations to display in Biography blox
organizations:
  # - name:
    # url: https://www.example.com/

# Short bio (displayed in user profile at end of posts)
bio: My research interests include ML, NLP, and SE.

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: envelope
    url: 'mailto:chungyuwang5507@gmail.com'
    label: email 
  - icon: brands/google-scholar
    url: https://scholar.google.ca/citations?user=nkixRd8AAAAJ&hl=en
  - icon: brands/github
    url: https://github.com/wangjohn5507
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/chung-yu-john-wang-510269226/
  # - icon: brands/instagram
  #   url: https://www.instagram.com/

education:
  - area: MSc in Computer Science
    institution: York University, Canada
    date_start: 2023-09-01
    date_end: 2025-04-30
    summary: |
      - Supervised by [Professor Hung Viet Pham](https://hvpham.github.io/)
      - Published 1 conference paper (MSR 2024)
    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'
  - area: BSc in Information Management
    institution: National University of Kaohsiung, Taiwan
    date_start: 2018-09-01
    date_end: 2022-06-30
    summary: |
      - GPA: 3.5/4.0
      - A research assistant of the [Computational Biology & Intelligence System Lab](https://cobis.bme.ncku.edu.tw/thyang/Main) supervised by Professor Tzu-Hsien Yang
      - Published 2 journal papers and 1 domestic conference paper (TAAI 2021)

# work:
#   - position: Director of Cloud Infrastructure
#     company_name: GenCoin
#     company_url: ''
#     company_logo: ''
#     date_start: 2021-01-01
#     date_end: ''
#     summary: |2-
#       Responsibilities include:
#       - lorem ipsum dolor sit amet, consectetur adipiscing elit
#       - lorem ipsum dolor sit amet, consectetur adipiscing elit
#       - lorem ipsum dolor sit amet, consectetur adipiscing elit
#   - position: Backend Software Engineer
#     company_name: X
#     company_url: ''
#     company_logo: ''
#     date_start: 2016-01-01
#     date_end: 2020-12-31
#     summary: |
#       Responsibilities include:
#       - Migrated infrastructure to a new data center
#       - lorem ipsum dolor sit amet, consectetur adipiscing elit
#       - lorem ipsum dolor sit amet, consectetur adipiscing elit

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Java
        description: ''
        percent: 80
        icon: devicon/python
      - name: RStudio
        description: ''
        percent: 100
        icon: devicon/rstudio
      - name: PyTorch
        description: ''
        percent: 40
        icon: devicon/pytorch
  # - name: Hobbies
  #   color: '#eeac02'
  #   color_border: '#f0bf23'
  #   items:
  #     - name: Hiking
  #       description: ''
  #       percent: 60
  #       icon: person-simple-walk
  #     - name: Cats
  #       description: ''
  #       percent: 100
  #       icon: cat
  #     - name: Photography
  #       description: ''
  #       percent: 80
  #       icon: camera

languages:
  - name: English
    percent: 75
  - name: Chinese
    percent: 100

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: 'Selection of Prompt Engineering Techniques for Code Generation through Predicting Code Complexity'
    url: https://arxiv.org/abs/2409.16416
    date: '2024-09-24'
    awarder: Arxiv (Under review)
    icon: arxiv
    summary: |
      PET-Select is a PET-agnostic model designed to improve the accuracy of code generation by selecting the most appropriate prompt engineering technique (PET) based on code complexity. It uses contrastive learning to distinguish between simple and complex queries, enabling more effective PET selection. Evaluations show PET-Select improves pass@1 accuracy by up to 1.9% and reduces token usage by 74.8%, optimizing the code generation process across benchmarks.
  - title: 'Task-oriented Prompt Enhancement via Script Generation'
    url: https://arxiv.org/abs/2409.16418
    date: '2024-04-26'
    awarder: Arxiv (Under review)
    icon: arxiv
    summary: |
      TITAN is a novel strategy designed to enhance large language models' (LLMs) performance on task-oriented prompts by using a universal, zero-shot approach. It eliminates the need for task-specific instructions and manual efforts by leveraging step-back and chain-of-thought prompting techniques to refine the code-generation process. In evaluations, TITAN outperforms existing zero-shot methods, achieving state-of-the-art performance in 8 out of 11 tasks, offering a significant improvement in handling everyday task-oriented prompts.
  - title: 'Can ChatGPT Support Developers? An Empirical Evaluation of Large Language Models for Code Generation'
    url: https://ieeexplore.ieee.org/abstract/document/10555687
    date: '2024-03-26'
    awarder: 21st International Conference on Mining Software Repositories (MSR ’24)
    icon: Conf
    summary: |
      Large language models (LLMs) have shown promise in code generation, but existing studies focus mainly on research settings, leaving gaps in understanding their real-world utility. An empirical analysis of developer conversations from the DevGPT dataset reveals that LLM-generated code is primarily used for demonstrating concepts or examples rather than as production-ready code. These findings highlight the need for further improvements before LLMs can play a significant role in modern software development.
  - title: 'YTLR: Extracting yeast transcription factor-gene associations from the literature using automated literature readers'
    url: https://www.sciencedirect.com/science/article/pii/S2001037022003750
    date: '2022-01-01'
    awarder: Computational and Structural Biotechnology Journal
    icon: Elsevier
    # summary: |
    #   Cells adapt to environmental stresses mainly via transcription reprogramming. Correct transcription control is mediated by the interactions between transcription factors (TF) and their target genes. These TF-gene associations can be probed by chromatin immunoprecipitation techniques and knockout experiments, revealing TF binding (TFB) and regulatory (TFR) evidence, respectively. Nevertheless, most evidence is still fragmentary in the literature and requires tremendous human resources to curate. We developed the first pipeline called YTLR (Yeast Transcription-regulation Literature Reader) to automate TF-gene relation extraction from the literature. YTLR first identifies articles with TFB and TFR information. Then TF-gene binding pairs are extracted from the TFB articles, and TF-gene regulatory associations are recognized from the TFR papers. On gathered test sets, YTLR achieves an AUC value of 98.8% in identifying articles with TFB evidence and AUC = 83.4% in extracting the detailed TF-gene binding pairs. And similarly, YTLR also obtains an AUC value of 98.2% in identifying TFR articles and AUC = 80.4% in extracting the detailed TF-gene regulatory associations. Furthermore, YTLR outperforms previous methods in both tasks. To facilitate researchers in extracting TF-gene transcriptional relations from large-scale queried articles, an automated and easy-to-use software tool based on the YTLR pipeline is constructed. In summary, YTLR aims to provide easier literature pre-screening for curators and help researchers gather yeast TF-gene transcriptional relation conclusions from articles in a high-throughput fashion. The YTLR pipeline software tool can be downloaded at https://github.com/cobisLab/YTLR/.
  - title: 'High-efficiency classification of injured causes on agricultural jujubes using EfficentNet'
    url: https://taai2021.github.io/cyut/accepted.html
    date: '2021-11-18'
    awarder: 26th International Conference on Technologies and Applications of Artificial Intelligence (TAAI)
    icon: TAAI
  - title: 'Human IRES Atlas: an integrative platform for studying IRES-driven translational regulation in humans'
    url: https://academic.oup.com/database/article/doi/10.1093/database/baab025/6263636
    # certificate_url: https://www.datacamp.com
    date: '2021-05-18'
    awarder: Database
    icon: Database
    # summary: |
    #   It is now known that cap-independent translation initiation facilitated by internal ribosome entry sites (IRESs) is vital in selective cellular protein synthesis under stress and different physiological conditions. However, three problems make it hard to understand transcriptome-wide cellular IRES-mediated translation initiation mechanisms: (i) complex interplay between IRESs and other translation initiation–related information, (ii) reliability issue of in silico cellular IRES investigation and (iii) labor-intensive in vivo IRES identification. In this research, we constructed the Human IRES Atlas database for a comprehensive understanding of cellular IRESs in humans. First, currently available and suitable IRES prediction tools (IRESfinder, PatSearch and IRESpy) were used to obtain transcriptome-wide human IRESs. Then, we collected eight genres of translation initiation–related features to help study the potential molecular mechanisms of each of the putative IRESs. Three functional tests (conservation, structural RNA–protein scores and conditional translation efficiency) were devised to evaluate the functionality of the identified putative IRESs. Moreover, an easy-to-use interface and an IRES–translation initiation interaction map for each gene transcript were implemented to help understand the interactions between IRESs and translation initiation–related features. Researchers can easily search/browse an IRES of interest using the web interface and deduce testable mechanism hypotheses of human IRES-driven translation initiation based on the integrated results. In summary, Human IRES Atlas integrates putative IRES elements and translation initiation–related experiments for better usage of these data and deduction of mechanism hypotheses.
  
---

I am currently a graduate student of Computer Science (M.Sc) at [York University (YorkU)](https://www.yorku.ca/) in Canada supervised by Professor [Hung Viet Pham](https://hvpham.github.io/). My research interests include Machine Learning, Natural Language Processing, and Software Engineering.
