---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: Machine Learning Education funded by NSF
    location: Waltham, MA
    date_start: '2023-09-01'
    date_end: ''
    description: |2-
        * Researched and developed Machine Learning materials with visualization tools for a National Science Foundation-funded high school AI education project.
        * Collaborated with academic staff to visualize Convolutional Neural Networks, integrating research and existing platforms.

  - title: Software Engineer Intern - Technology Summer Analyst
    company: UBS
    company_url: 'https://www.ubs.com'
    location: Weehawken, NJ
    date_start: '2023-06-01'
    date_end: '2023-08-31'
    description: |2-
        * Led the development of a secure file transfer system using Azure and TypeScript, with deployment through GitLab CI-CD Pipeline and Kubernetes.
        * Identified and rectified critical security vulnerabilities, prompting a security overhaul.
        * Developed an AI chatbot using OpenAI API, winning first place in the intern challenge.
        * Created an Azure Storage Solutions guide, under consideration for publication on the official UBS website.

  - title: Machine Learning Intern
    company: Global AI Investment
    location: Wall Street, NYC
    date_start: '2022-06-01'
    date_end: '2022-08-31'
    description: |2-
        * Conducted analyses on SDG, stock, and fashion item prices with Pandas, employing ML techniques to produce trend reports on S&P 500 stocks.
        * Merged financial time series data with SDG scores to identify Twitter stock price trends in relation to the SDG index.

  # - title: CEO
  #   company: GenCoin
  #   company_url: ''
  #   company_logo: org-gc
  #   location: California
  #   date_start: '2021-01-01'
  #   date_end: ''
  #   description: |2-
  #       Responsibilities include:
        
  #       * Analysing
  #       * Modelling
  #       * Deploying

  # - title: Professor of Semiconductor Physics
  #   company: University X
  #   company_url: ''
  #   company_logo: org-x
  #   location: California
  #   date_start: '2016-01-01'
  #   date_end: '2020-12-31'
  #   description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '1'
---
