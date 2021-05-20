---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 39

title: Academic Experiences
subtitle: 

design:
  background:
    # Name of image in `assets/media/`.
    image: image.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.6
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:

  - title: Quantitative & NLP Researcher
    company: LORA Technologies
    company_url: 'https://www.loratechai.com/'
    company_logo: loratech
    location: Hong Kong
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Currently working on the research project of integrating several state-of-the-art Natural Language Processing models (like FinBERT, etc.) with Finance applications

  - title: Economic Research Assistant
    company: China Europe International Business School (CEIBS)
    company_url: 'https://www.ceibs.edu/'
    company_logo: ceibs
    location: Shanghai
    date_start: '2020-06-01'
    date_end: '2020-10-01'
    description: |2-
        Responsibilities include:
        
        * Actively engaged in the whole process of data collection/cleansing/mining using web scrapers/spiders & textual analysis tools (BeautifulSoup, Requests, Scrapy)
        * Collaborated with multiple scholars on several econometric & macro/urban/regional economic research projects focusing on - 
      
          (i) The impacts of the unstable macroeconomic environment under the China-U.S. Trade War on various importing and exporting commodities from different sectors
          
          (ii) The synergistic and spillover effects of exhibitions/sports events on regional hotel and tourism industry
          
  - title: Quantitative Researcher
    company: PolyU Accounting & Finance Tech Lab & LORA Technologies
    company_url: 'https://sites.google.com/view/polyuaftechlab/home'
    company_logo: aftechlab
    location: Hong Kong
    date_start: '2019-06-01'
    date_end: '2020-06-01'
    description: |2-
        Responsibilities include:
        
        * Comprehensively assessed the feasibility and suitability of a series of Machine Learning (PCA + XgBoost/LightGBM) & Deep Learning (AutoEncoder + GRU/LSTM) models on the predictions of company fundamentals (i.e., the Earnings)
        * Underwent systematic training on Python, R, Blockchain & Cryptocurrency and Statistical & Machine Learning

  #- title: CEO
    #company: GenCoin
    #company_url: ''
    #company_logo: org-gc
    #location: California
    #date_start: '2021-01-01'
    #date_end: '2021-02-02'
    #description: |2-

        
 #- title: Professor of Semiconductor Physics
    #company: University X
    #company_url: ''
    #company_logo: org-x
    #location: California
    #date_start: '2016-01-01'
    #date_end: '2020-12-31'
    #description: Taught electronic engineering and researched semiconductor physics.


design:
  columns: '2'
---
