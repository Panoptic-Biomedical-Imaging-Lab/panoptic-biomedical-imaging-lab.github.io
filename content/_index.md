---
title: ''
summary: 'Panoptic Biomedical Imaging Lab at the University of Ulsan'
date: 2026-07-22
type: landing

sections:
  - block: markdown
    id: home
    content:
      title: "Panoptic Biomedical Imaging Lab"
      subtitle: "University of Ulsan"
      text: |-
        **Artificial Intelligence and Computational Imaging for Biomedical Applications**

        We develop artificial intelligence and computational imaging methods
        to understand biomedical structures and physiological characteristics
        from facial, retinal, OCT, and medical images.

        Our research combines biomedical image analysis, deep learning,
        multimodal artificial intelligence, and clinically meaningful
        quantitative imaging.
    design:
      columns: '1'
      background:
        gradient_mesh:
          enable: true

  - block: markdown
    id: research
    content:
      title: "Research Areas"
      subtitle: "Our primary research directions"
      text: |-
        ### Facial Skin Imaging

        AI-based detection, segmentation, and quantitative analysis of facial
        skin characteristics, including wrinkles, pores, pigmentation, and redness.

        ### Retinal and OCT Imaging

        Computational analysis of retinal vasculature, optic structures,
        and retinal layers for quantitative biomedical assessment.

        ### Medical Image Analysis

        Deep-learning and computational-imaging techniques for medical image
        reconstruction, enhancement, segmentation, and interpretation.

        ### Multimodal AI

        Integration of biomedical images, clinical information, and language
        models to generate interpretable and clinically meaningful results.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: "Featured Publications"
      text: "Selected publications from our research group."
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: "Recent Publications"
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: "Latest News"
      subtitle: ""
      text: ""
      page_type: blog
      count: 6
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: true
        exclude_past: false
      offset: 0
      order: desc
    design:
      view: card
      columns: 3

  - block: markdown
    id: join
    content:
      title: "Join Us"
      subtitle: "Graduate Students and Undergraduate Researchers"
      text: |-
        We welcome motivated students interested in biomedical imaging,
        computer vision, deep learning, and multimodal artificial intelligence.

        Prospective students are encouraged to contact the lab with a brief
        introduction, research interests, and curriculum vitae.
    design:
      columns: '1'
---
