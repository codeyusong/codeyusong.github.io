---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Buddy, CDU Global Buddy Program
          company: Charles Darwin University
          company_url: ''
          company_logo: 'building-columns'
          location: NT, Australia
          date_start: '2024-01-16'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Spearheading support initiatives for international students, nurturing a sense of belonging, and orchestrating in-person gatherings to cultivate cultural exchange and solidarity.
              * Collaborating closely with senior buddies and CDU Global staff to innovate student engagement strategies, thereby enhancing the overall student experience, and fostering a welcoming campus environment.
              * Offering personalized mentorship and guidance to aid international students in navigating academic challenges and social integration, ensuring their seamless transition into university life, and promoting cross-cultural understanding.
        - title: Workshop Facilitator, Research Bazaar Northern Territory
          company: Charles Darwin University
          company_url: ''
          company_logo: 'building-columns'
          location: NT, Australia
          date_start: '2023-10-25'
          date_end: '2023-10-26'
          description: |2-
              Responsibilities include:
              
              * Provided support to Dr. Mirjam Kaestli (Presenter) and collaborated with other facilitators in assisting participants with debugging program environments and troubleshooting code during workshops. 
              * Proficiently handled data importation and library installations in R, demonstrating adeptness in fundamental operations.
              * Effectively executed R scripts and utilized Tidyverse/ggplot2 packages for data manipulation and visualization, highlighting advanced R techniques.
    design:
      columns: '2'

  - block: markdown
    id: Gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: yusong0223@hotmail.com
      address:
        street: 6 Dripstone Road
        city: Casuarina
        region: NT
        postcode: '0810'
        country: Australia
        country_code: AU
      office_hours:
        - '09:00 to 17:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '-12.37711482315052'
        longitude: '130.88131577217044' 
    design:
      columns: '2'
---
