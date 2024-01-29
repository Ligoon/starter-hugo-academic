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
  - title: Software Dev Engineer Intern
    company: Amazon, Inc.
    company_url: 'https://www.amazon.com/'
    company_logo: amazon
    location: Seattle, WA
    date_start: '2018-05-10'
    date_end: '2018-08-22'
    description: |2-
      - Designed a microservices architecture with AWS Lambda, Step Function, and S3, integrated with an existing system
      - Migrated and improved scalability of account subscription process using asynchronous workflow with Java
      - Streamlined deployment with CI/CD pipeline and wrote infrastructure as code with AWS CDK and Typescript
  
  - title: Software Engineer Intern 
    company: Dentall Inc.
    company_url: 'https://dentall.io/'
    company_logo: dentall
    location: Taipei, Taiwan
    date_start: '2021-03-01'
    date_end: '2021-07-01'
    description: |2-
      - Improved accuracy of tooth-numbering model by 60% utilizing pre-trained YOLOv5
      - Implemented post-processing algorithm using TensorFlow and Python to improve YOLOv5’s prediction by 10%
      - Achieved an accuracy of 98% on x-ray film classifier with transfer learning utilizing ResNet and DenseNet
      - Conducted researches and survey the latest research paper of deep learning, computer version in dental field
        
  - title: Front-end Web Developer Intern
    company: Department of Computer Science, NYCU
    company_url: 'https://www.nycu.edu.tw/en/'
    company_logo: nctu
    location: Hsinchu, Taiwan
    date_start: '2020-02-01'
    date_end: '2021-02-01'
    description: |2-
      - Designed and maintained CS department website for 50+ professors to manage students’ information and course status with React.js, Material UI, and Redux
      - Cooperated with back-end team to develop a new function to serve 800+ students’ demand in graduation project registration

  

design:
  columns: '1'
---
