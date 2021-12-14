---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Software Engineer Intern 
    company: Dentall Inc.
    company_url: 'https://dentall.io/'
    company_logo: dentall
    location: Taipei, Taiwan
    date_start: '2021-03-01'
    date_end: '2021-07-01'
    description: |2-
      - improved the accuracy of previous tooth-numbering detection model by 60% and x-ray classification model by 3%
      - developed deep learning application for tooth numbering and caries detection of x-ray film, using self-developed algorithms (with pytorch, tensorflow) and open-source models (e.g. YOLO, Mask R-CNN, ResNet)
      - conducted researches and survey the latest research paper of deep learning, computer version in dental field
        
  - title: Front-end Web Developer Intern
    company: Department of Computer Science, NYCU
    company_url: 'https://www.nycu.edu.tw/en/'
    company_logo: nctu
    location: Hsinchu, Taiwan
    date_start: '2020-02-01'
    date_end: '2021-02-01'
    description: |2-
      - developed registration function to serve 800+ students’ demand in independent study using React.js and Redux
      - Optimized user interface of CS department assistant website for 50+ professor users
      - Worked in a team of 10+ front-end developers and back-end developers

  - title: Software Engineer Summer Intern
    company: Wincomm Corporation
    company_url: 'https://www.wincomm.com.tw/'
    company_logo: wincomm
    location: Hsinchu, Taiwan
    date_start: '2018-07-01'
    date_end: '2018-08-31'
    description: |2-
      - built an internal web application, using Django, MySQL, python, for detecting real-time information (e.g. voltages, battery data, CPU temperature, fan speed) from hardware devices

design:
  columns: '1'
---
