---

<!-- Tutorial: https://mickaellalande.github.io/post/tutorial/how-to-create-an-academic-github-page-with-hugo/  -->
<!-- Tutorial: https://iphysresearch.github.io/blog/post/writting-markdown/  -->


# if problems, see https://user.it.uu.se/~justin/Hugo/post/hugo_module_fail/
# or update Hugo https://wowchemy.com/docs/hugo-tutorials/update/


# Leave the homepage title empty to use the site title
title: Chris Yee WONG, Ph.D., P.Eng.
date: 2025-07-03
type: landing

sections:
  # - block: hero
  #   content:
  #     title: 
  #     # image:
  #     #   filename: hero-academic.png
  #     # cta:
  #     #   label: '**Get Started**'
  #     #   url: https://wowchemy.com/templates/
  #     # cta_alt:
  #     #   label: Ask a question
  #     #   url: https://discord.gg/z8wNYzb
  #     # cta_note:
  #     #   label: >-
  #     #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
  #     # text: |-
  #     #   Welcome to the personal page of Chris Yee Wong!

  #     #   <!--Custom spacing-->
  #     #   <div class="mb-3"></div>
  #     #   <!--GitHub Button JS-->
  #     #   <script async defer src="https://buttons.github.io/buttons.js"></script>
  #   design:
  #     background:
  #       gradient_end: '#1976d2'
  #       gradient_start: '#004ba0'
  #       text_color_light: true
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # design:
      #   columns: '2'
      # Override your bio text from `authors/admin/_index.md`?
      # text:
  - block: markdown
    content:
      title: "Gallery"
      subtitle:
      text: |-
          {{< gallery album="landing" lightbox="true" >}} 
    design: # resize_options="300x300" <-- this only affects resolution and not size
      columns: '1'
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: Concordia University
          company_url: 'https://www.concordia.ca/ginacody/mechanical-industrial-aerospace-eng.html'
          company_logo: concordia_logo
          location: Montreal, Canada
          date_start: '2024-08-01'
          date_end: ''
        - title: Research Associate
          company: McGill University - Responsible Autonomy and Intelligent Systems Ethics (RAISE) Laboratory
          company_url: 'https://sites.google.com/view/mcgillraise/home'
          company_logo: McGill_logo
          location: Montreal, Canada
          date_start: '2023-05-01'
          date_end: '2024-07-30'
        - title: Course Lecturer
          company: McGill University - Department of Mechanical Engineering
          company_url: 'https://www.mcgill.ca/mecheng'
          company_logo: McGill_logo
          location: Montreal, Canada
          date_start: '2023-08-30'
          date_end: '2024-04-30'
          # description: wtf
        - title: Postdoctoral Fellow
          company: Universite de Sherbrooke - Humanoid and Collaborative Robotics Laboratory
          company_url: ''
          company_logo: UdeS_logo_only
          location: Sherbrooke, Canada
          date_start: '2019-03-01'
          date_end: '2023-04-30'
        - title: Part-Time Professor (ENGR 243)
          company: Concordia University
          company_url: ''
          company_logo: concordia_logo
          location: Montreal, Canada
          date_start: '2021-09-01'
          date_end: '2021-12-31'
        - title: Mitacs Globalink Visiting Postdoctoral Fellow
          company: CNRS LIRMM Interactive Digital Humans
          company_url: ''
          company_logo: LogoLIRMMstacked
          location: Montpellier, France
          date_start: '2019-08-20'
          date_end: '2019-12-31'
        - title: JSPS Postdoctoral Fellow
          company: CNRS-AIST Joint Robotics Laboratory (JRL)
          company_url: ''
          company_logo: aist
          location: Tsukuba, Japan
          date_start: '2018-01-04'
          date_end: '2019-02-08'
        # - title: Ph.D. in Mechanical Engineering
        #   company: University of Toronto
        #   company_url: ''
        #   company_logo: UofT_logo
        #   location: Toronto, Canada
        #   date_start: '2013-09-01'
        #   date_end: '2017-12-31'
        # - title: B.Eng. and M.Eng. in Mechanical Engineering
        #   company: McGill University
        #   company_url: ''
        #   company_logo: McGill_logo
        #   location: Montreal, Canada
        #   date_start: '2007-09-01'
        #   date_end: '2013-08-30'
  #         # description: |2-
  #         #     Responsibilities include:

  #         #     * Analysing
  #         #     * Modelling
  #         #     * Deploying
        # - title: Professor of Semiconductor Physics
        #   company: University X
        #   company_url: ''
        #   company_logo: org-x
        #   location: California
        #   date_start: '2016-01-01'
        #   date_end: '2020-12-31'
        #   description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Active Projects
          tag: 'active'
        - name: Past Projects
          tag: old
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: markdown #TEACHING PORTFOLIO
  #   id: teaching
  #   content:
  #     title: Teaching Philosophy
  #     text: |2-
  #       SOMETEXT
  #   design:
  #     columns: '1'
  # - block: experience
  #   id: publications
  #   content:
  #     title: Publications
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     text: |2-
  #       This section is currently a work in progress.
  #       Please see my [ResearchGate](https://www.researchgate.net/profile/Christopher-Yee-Wong) or [Google Scholar](https://scholar.google.ca/citations?hl=en&user=rddmHA4AAAAJ&view_op=list_works&sortby=pubdate) profiles for a detailed list. 
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        This section is currently a work in progress.
        Please see my [ResearchGate](https://www.researchgate.net/profile/Christopher-Yee-Wong) or [Google Scholar](https://scholar.google.ca/citations?hl=en&user=rddmHA4AAAAJ&view_op=list_works&sortby=pubdate) profiles for a detailed list. 
        {{% /callout %}}
        <!-- Quickly discover relevant content by [filtering publications](./publication/). -->
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: teaching
    content:
      title: Teaching Portfolio
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      text: |2-
        > <i> I believe that knowledge cannot be transferred or prescribed; it can only be reconstructed in one's head. </i>

        My overarching philosophy as a teacher, continuously refined over 16 semesters of teaching experience as both course instructor and teaching assistant, is to act as a guide for students such that they stay engaged in the learning process and solve problems by their own reasoning. 
        The goal is to help students in reconstructing new knowledge for themselves through a mix of evidence-based educational techniques and my own creativity to ensure that my methods are effective. 

        I'm always interested in new teaching philosophies and methods, so feel free to reach out to me if you want to start a discussion!

         <sub> (The entries below are my experience as a course instructor, except for the last entry.) </sub>
      # design:
      #   columns: '2'
      #   view: compact
      #   spacing:
      #     # Customize the section spacing. Order is top, right, bottom, left.
      #     padding: ["20px", "0", "20px", "0"]
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: MECH 370 Modelling and Analysis of Dynamic Systems
          company: Concordia University
          company_url: 'https://www.concordia.ca/academics/undergraduate/calendar/current/section-71-gina-cody-school-of-engineering-and-computer-science/section-71-60-engineering-course-descriptions/mechanical-engineering-courses.html'
          company_logo: concordia_logo
          location: Montreal, Canada
          date_start: '2024-09-04'
          date_end: ''
          # description: |2-
          #   * Overall rating 4.7/5
          #   * Semesters taught: Fall 2023, Winter 2024
          #   * For some student comments, please view [my RateMyProfessors profile](https://www.ratemyprofessors.com/professor/2927024).
        - title: MECH 261/262 Measurements and Statistics Lab
          company: McGill University
          company_url: 'https://www.mcgill.ca/study/2023-2024/courses/mech-262'
          company_logo: McGill_logo
          location: Montreal, Canada
          date_start: '2023-08-30'
          date_end: '2024-04-30'
          description: |2-
            * Overall rating 4.7/5
            * Semesters taught: Fall 2023, Winter 2024
            * For some student comments, please view [my McGill RateMyProfessors profile](https://www.ratemyprofessors.com/professor/2927024).
        - title: ENGR 243 Dynamics
          company: Concordia University
          company_url: 'https://www.concordia.ca/academics/undergraduate/calendar/current/section-71-gina-cody-school-of-engineering-and-computer-science/section-71-60-engineering-course-descriptions/mechanical-engineering-courses.html'
          company_logo: concordia_logo
          location: Montreal, Canada
          date_start: '2021-09-01'
          date_end: '2021-12-31'
          description: |2-
            * Overall rating 4.71/5, enthusiasm 4.94/5, and approachability 4.94/5
            * Semesters taught: Fall 2021
            * For some student comments, please view [my Concordia RateMyProfessors profile](https://www.ratemyprofessors.com/professor?tid=2719627).
        - title: MIE 422 Automated Manufacturing
          company: University of Toronto
          company_url: ''
          company_logo: UofT_logo
          location: Toronto, Canada
          date_start: '2016-09-01'
          date_end: '2016-12-31'
          description: |2-
            * Overall rating 4.2/5, enthusiasm 4.7/5, and approachability 4.6/5
              * (Comparatively, the departmental average overall rating was 3.7/5)
            * Semesters taught: Fall 2016
        - title: Teaching Assistant / Head TA
          # company: Various Universities
          # company_url: ''
          # company_logo: 
          # location: Toronto, Canada
          date_start: '2011-09-01'
          date_end: '2022-12-31'
          description: |2-
            Two latest student evaluations as a TA: 4.7/5 and 4.5/5
            * **Université de Sherbrooke** (Oct 2021 – Dec 2022)
              * GEL 521 Identification et modélisation (Fall 2021, 2022)
            * **University of Toronto** (Sept 2013 – Dec 2017)
              * MIE 422F Automated Manufacturing (Fall 2013-2015 and 2017)
              * MIE 402S Vibrations (Spring 2014-2017)
              * MIE 1064F Control Methods with Applications to Robotics (Fall 2017)
            * **McGill University**	(Sept 2011 – Dec 2011)
              * MECH 260 Machine Tool Laboratory	(Fall 2011)
  - block: markdown
    id: prospectivestudents
    content:
      title: Prospective Students
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      text: |2-
        Students interested in joining the *Living with Assistive and Interactive Robots (LAIR) Lab* should send me an email with your resume, what you are looking for, specific topics that you are interested in, and how they relate to my work. It is particularly important to tell me if you already hold or have applied for any external funding (NSERC, FRQNT, etc) and if you are a Canadian citizen or permanent resident. Please also indicate which program you are applying for (e.g., MASc vs PhD).
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |2-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #       Contact (add or remove contact options as necessary)
  #     email: test@example.org
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: '@chrisywong1'
      #     link: 'https://twitter.com/chrisywong1'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      # autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    # design:
    #   columns: '2'
---
