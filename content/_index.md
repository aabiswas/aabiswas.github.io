---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
sections:
  # - block: hero
  #   demo: true # Only display this section in the Wowchemy demo site
  #   content:
  #     title: Hugo Academic Theme
  #     image:
  #       filename: hero-academic.png
  #     cta:
  #       label: '**Get Started**'
  #       url: https://wowchemy.com/templates/
  #     cta_alt:
  #       label: Ask a question
  #       url: https://discord.gg/z8wNYzb
  #     cta_note:
  #       label: >-
  #         <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
  #     text: |-
  #       **Generated by Wowchemy - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

  #       **Easily build anything with blocks - no-code required!**

  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

  #       <!--Custom spacing-->
  #       <div class="mb-3"></div>
  #       <!--GitHub Button JS-->
  #       <script async defer src="https://buttons.github.io/buttons.js"></script>
  #   design:
  #     background:
  #       gradient_end: '#1976d2'
  #       gradient_start: '#004ba0'
  #       text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lecturer
          company: Kishoreganj University
          company_url: 'https://cse.kiu.ac.bd/viewprofile/2'
          company_logo: kiu
          location: Kishoreganj, Bangladesh
          date_start: '2023-02-05'
          date_end: ''
        - title: Senior Lecturer
          company: Daffodil International University (DIU)
          company_url: 'https://daffodilvarsity.edu.bd/'
          company_logo: diu
          location: Dhaka, Bangladesh
          date_start: '2022-01-01'
          date_end: '2023-01-31'
        - title: Lecturer
          company: Daffodil International University (DIU)
          company_url: 'https://daffodilvarsity.edu.bd/'
          company_logo: diu
          location: Dhaka, Bangladesh
          date_start: '2018-09-05'
          date_end: '2021-12-31'

    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Achievements, Awards, and Services'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2024-12-31'
          date_start: '2013-01-26'
          description: |2-
              <span style="font-size: 1.5em;">**Research Awards:**</span>
              * Received best paper award from the Third International Conference on Smart Systems: Innovations in Computing (SSIC), Springer, 2021.
              * Received best paper award from the International Conference on Machine Intelligence and Data Science Applications (MIDAS), Springer, 2021.

              <span style="font-size: 1.5em;">**Scholarships:**</span>
              * Received university yearly scholarship for outstanding results.
              * Received scholarship for achieving the top position in the undergraduate entrance exam.
              
              <span style="font-size: 1.5em;">**Academic Contributions:**</span> <br>
              <span style="font-size: 1.5em;">Coach</span>
              * <strong>ICPC'24</strong>: Coached BSMRU Team at the International Collegiate Programming Contest (ICPC) Asia Dhaka Regional 2024.
              * <strong>NCPC'23</strong>: Coached BSMRU Team at the National Collegiate Programming Contest (NCPC), Bangladesh, 2023.

              <span style="font-size: 1.5em;">Session Chair</span>
              * <strong>ICCCI'21</strong>: Served as a session chair for the 2021 International Conference on Computer Communication and Informatics, IEEE, Sri Shakthi Institute of Engineering and Technology (SIET), India.

              <span style="font-size: 1.5em;">Co-convener</span>
              * <strong>MIDAS'21</strong>: Served as co-convener for the International Conference on Machine Intelligence and Data Science Applications (MIDAS 2021), Springer, Comilla University, Cumilla, Bangladesh.
              
              <span style="font-size: 1.5em;">Judge</span>
              * <strong>IC4IR'21</strong>: Served as a judge for the Mujib 100 Idea Contest 2021, organized by the University Grants Commission (UGC) of Bangladesh, as part of the 4th Industrial Revolution and Beyond (IC4IR 2021) conference.
 
              <span style="font-size: 1.5em;">Journal Reviewer</span>
              * <strong>IEEE Access</strong>: Served as a reviewer for IEEE Access.
              * <strong>International Journal of Human-Computer Studies</strong>: Served as a reviewer for International Journal of Human-Computer Studies, Elsevier journal.
              * <strong>Computers and Programs in Biomedicine</strong>: Served as a reviewer for Computers and Programs in Biomedicine, Elsevier journal.
              * <strong>Computer Methods and Programs in Biomedicine Update</strong>: Served as a reviewer for Computer Methods and Programs in Biomedicine Update, Elsevier journal.
              * <strong>Computers and Electronics in Agriculture</strong>: Served as a reviewer for Computers and Electronics in Agriculture, Elsevier journal.
              * <strong>Computers in Biology and Medicine</strong>: Served as a reviewer for Computers in Biology and Medicine, Elsevier journal.
              * <strong>Array</strong>: Served as a reviewer for Array, Elsevier journal.
              * <strong>Heliyon</strong>: Served as a reviewer for Heliyon, Elsevier journal.
              * <strong>Healthcare Analytics</strong>: Served as a reviewer for Healthcare Analytics, Elsevier journal.
              * <strong>CRBS</strong>: Served as a reviewer for Current Research in Behavioral Sciences (CRBS), Elsevier journal.
              * <strong>Applied Nursing Research</strong>: Served as a reviewer for Applied Nursing Research, Elsevier journal.
              * <strong>Machine Learning with Applications</strong>: Served as a reviewer for Machine Learning with Applications, Elsevier journal.
              * <strong>SASC</strong>: Served as a reviewer for Systems and Soft Computing (SASC), Elsevier journal.
              * <strong>Medical Engineering and Physics</strong>: Served as a reviewer for Medical Engineering and Physics, Elsevier journal.
              * <strong>SSHO</strong>: Served as a reviewer for Social Sciences & Humanities Open (SSHO), Elsevier journal.
              * <strong>Cogent Engineering</strong>: Served as a reviewer for Cogent Engineering, Taylor & Francis journal.
              * <strong>CMBBE</strong>: Served as a reviewer for Computer Methods in Biomechanics and Biomedical Engineering (CMBBE), Taylor & Francis journal.
              * <strong> International Journal of Digital Earth</strong>: Served as a reviewer for  International Journal of Digital Earth, Taylor & Francis journal.
              * <strong>BEEI</strong>: Served as a reviewer for Bulletin of Electrical Engineering and Informatics (BEEI), Published by the Institute of Advanced Engineering and Science, Indonesia. 
              * <strong>IJEECS</strong>: Served as a reviewer for Indonesian Journal of Electrical Engineering and Computer Science (IJEECS), Published by the Institute of Advanced Engineering and Science, Indonesia.  
              * <strong>APST</strong>: Served as a reviewer for Asia-Pacific Journal of Science and Technology (APST), Division of Research Administration, Khon Kaen University, Thailand.

              <span style="font-size: 1.5em;">Conference Reviewer</span>
              * <strong>CHI'25</strong>: Served as a reviewer for the ACM CHI Conference on Human Factors in Computing Systems, Yokohama, Japan (Rank: A*). [<strong>Flagship conference in the field of Human-Computer Interaction</strong>] 
              * <strong>HRI'25</strong>: Served as a reviewer for the IEEE/ACM International Conference on Human-Robot Interaction, Melbourne, Australia (Rank: A). [<strong>Flagship conference in the field of Human-Robot Interaction</strong>]
              * <strong>MobileHCI'25</strong>: Served as a reviewer for the ACM International Conference on Mobile Human-Computer Interaction (MobileHCI), Sharm El-Sheikh, Egypt (Rank: B).
              * <strong>MIET'24</strong>: Served as a reviewer for the International Conference on Machine Intelligence and Emerging Technologies, Springer, Noakhali Science and Technology University (NSTU), Bangladesh.
              * <strong>EISBG'24</strong>: Served as a reviewer for the International Conference on Embracing Industry 4.0 for Sustainable Business Growth, Noakhali Science and Technology University (NSTU), Noakhali, Bangladesh.
              * <strong>CSAE'22</strong>: Served as a reviewer for the International Conference on Computer Science and Application Engineering, ACM International Conference Proceedings Series, Nanjing, China.
              * <strong>ICSCT'21</strong>: Served as a reviewer for the International Conference on Science & Contemporary Technologies, IEEE, Bangladesh University of Business and Technology (BUBT), Dhaka, Bangladesh.
              * <strong>ICCCI'21</strong>: Served as a reviewer for the 2021 International Conference on Computer Communication and Informatics, IEEE, Sri Shakthi Institute of Engineering and Technology (SIET), India.
              * <strong>MIDAS'21</strong>: Served as reviewer for the International Conference on Machine Intelligence and Data Science Applications (MIDAS 2021), Springer, Comilla University, Cumilla, Bangladesh.

              <span style="font-size: 1.5em;">Speaker</span>
              * <strong>Lead Speaker</strong>, "Application of Artificial Intelligence and Technology in Education and Research", BSMRU, Kishoreganj, Bangladesh, December, 2023.

          url: ''
      
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
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
        - name: Machine Learning
          tag: Machine Learning
        - name: Deep Learning
          tag: Deep Learning
        - name: Natural Language Processing
          tag: Natural Language Processing
        - name: Human-Computer Interaction
          tag: Human-Computer Interaction
        - name: Healthcare
          tag: Healthcare
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: True
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: publications
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
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
  # - block: portfolio
  #   id: shared_tasks
  #   content:
  #     title: Shared Tasks
  #     filters:
  #       folders:
  #         - shared_tasks
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Software Engineering
  #         tag: Software Engineering
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '2'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: True
  # # - block: markdown
  # #   content:
  # #     title: Gallery
  # #     subtitle: ''
  # #     text: |-
  # #       {{< gallery album="demo" >}}
  # #   design:
  # #     columns: '1'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: true
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # subtitle:
      # text: |-
      #   You can directly mail me.
      # Contact (add or remove contact options as necessary)
      email: alaminbiswas.cse@gmail.com
      phone: +880 17 4007 1456
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
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
      contact_links:
        - icon: facebook
          icon_pack: fab
          name: Al Amin Biswas
          link: 'https://web.facebook.com/aab42'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # # Automatically link email and phone or display as text?
      # autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
