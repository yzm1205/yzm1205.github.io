---
title: 'Research'
date: 2026-07-30
type: landing

sections:
  - block: markdown
    content:
      title: 'Research'
      text: |-
        I study how language models and AI systems should be evaluated, selected, and deployed when
        aggregate benchmark scores do not fully capture semantic behavior, user requirements, or
        deployment constraints. My work combines natural language processing, model evaluation,
        scalable inference, and agentic systems to develop reliable and reproducible methods for
        matching AI models to real-world tasks.

        Current directions include reliable capability and alignment evaluation, resource-aware
        model selection and routing, evaluation of multi-step and agentic systems, and efficient
        multi-GPU inference.
    design:
      columns: '1'
      spacing:
        padding: ['4rem', 0, '4rem', 0]   # top, right, bottom, left
  - block: collection
    id: research-software
    content:
      title: Research Software
      text: ''
      filters:
        folders:
          - projects
    design:
    
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
