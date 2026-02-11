---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: Research
      subtitle: ''
      text: |-
        I am a Ph.D. student@University of Florida in Electrical and Computer Engineering, advisied by Prof. Xiaoyi Lu[](https://padsys.org/people/xiaoyi-lu.html).

        My research interests include high-performance computing and networking, runtime and communication systems, scalable training and inference of large language models, distributed and federated learning systems, and AI–HPC co-design.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: All Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Selected Projects
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
