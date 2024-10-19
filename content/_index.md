---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
      
  - block: news
    content:
      title: "News:"
      newsItems:
      - detail: "· [15/10]I am working on issues related to 3D image generation in VLLM."
      - detail: "· [1/10] I am working on prompt optimization methods for LLMS under perturbations."
      - detail: "· [23/9] Please check our preprint about [LLM-based semantic file system](https://www.researchgate.net/publication/384257895_From_Commands_to_Prompts_LLM-based_Semantic_File_System_for_AIOS)！"
      - detail: "· [22/9] I will be an official intern of Shanghai AI laboratory!"
      - detail: "· [15/8] One paper was submitted to AAAI!"
      - detail: "· [1/8]  One paper was submitted to TNNLS!"
  # - block: skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
