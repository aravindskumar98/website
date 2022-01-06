---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience and Projects
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
  - title: Data Scientist
    company: Anheuser-Busch InBev
    company_url: 'https://www.ab-inbev.com/'
    company_logo: abilogo
    location: Bangalore, India
    date_start: '2020-08-03'
    date_end: '2021-08-16'
    description: |2-
      * Improved BrewRight, ABI’s legal analytics platform for detecting fraudulent transactions for financial compliance
      * Developed machine learning models and implemented hypotheses to flag anomalous and risky transactions
      * Set-up CICD for DevOps pipelines, optimized API data extraction scripts and achieved E2E Automation
      * Migrated existing codebase to run in PySpark using Databricks; reducing runtime by 70%, saving USD 100,000
        
  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
