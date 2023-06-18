---
# Leave the homepage title empty to use the site title
title:
date: 2023-06-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: eldre
  - block: features
    content:
      title: Scientific skills
      items:
        - name: Field sampling
          description:
          icon: search
          icon_pack: fas
        - name: Marine fauna identification
          description:
          icon: fish
          icon_pack: fas
        - name: Marine flora identification
          description:
          icon: leaf
          icon_pack: fas
        - name: Laboratory activities
          description:
          icon: flask
          icon_pack: fas
        - name: Statistics
          description:
          icon: chart-line
          icon_pack: fas
        - name: Peer-reviewed publication
          description:
          icon: pen-nib
          icon_pack: fas
  - block: features
    content:
      title: Programming skills
      items:
        - name: R
          description: 95%
          icon: r-project
          icon_pack: fab
        - name: SQL
          description: 50%
          icon: database
          icon_pack: fas
        - name: Python
          description: 20%
          icon: python
          icon_pack: fab
        - name: Markdown
          description: ''
          icon: markdown
          icon_pack: fab
        - name: LaTeX
          description: ''
          icon: file-alt
          icon_pack: fas
        - name: CSS
          description: ''
          icon: css3-alt
          icon_pack: fab
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
        - name: Enviro-Actions
          tag: EA
        - name: Seagrass meadows
          tag: Seagrass
        - name: Human-influenced benthos
          tag: PhD
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  #- block: collection
  #  content:
  #    title: Publications
  #    text:
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: false
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: collection
  #  id: talks
  #  content:
  #    title: Talks and Posters
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  - block: experience
    content:
      title: Professional experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Scientific director
          company: Northern Institute for Research in Environment and Occupational Health and Safety
          company_url: 'https://inrest.ca'
          company_logo: logo_INREST
          location: 'Sept-Îles, Canada'
          date_start: '2023-05-01'
          date_end: ''
          description: Management of the scientific program of INREST and the Industrial Harbour Center of Expertise (CEIP).
        - title: Project leader
          company: Northern Institute for Research in Environment and Occupational Health and Safety
          company_url: 'https://inrest.ca'
          company_logo: logo_INREST
          location: 'Sept-Îles, Canada'
          date_start: '2022-10-03'
          date_end: '2023-04-30'
          description: Management of the Enviro-Action project and the team, to build a real-time monitoring platform of industrial-harbour ecosystems in Canada.
        - title: Postdoctoral fellow
          company: 'Université du Québec à Rimouski'
          company_url: 'https://uqar.ca'
          company_logo: logo_UQAR
          location: Rimouski, Canada
          date_start: '2021-04-01'
          date_end: '2022-10-02'
          description: Part of MEOPAR's research program, where I evaluated the links between benthic biodiversity, biological traits and habitat parameters within eelgrass meadows in the Gulf of St. Lawrence.
        - title: Biologist
          company: Fisheries and Oceans Canada
          company_url: 'https://www.dfo-mpo.gc.ca'
          company_logo: logo_UQAR
          location: Mont-Joli, Canada
          date_start: '2021-01-04'
          date_end: '2021-03-31'
          description: Part of project SPERA, where I investigated which biological traits were the most used in the functional study of benthic ecosystems, and produced a trait database for coastal benthic invertebrates found in the north coast of the Gulf of St. Lawrence.
        - title: Deputy Director
          company: Telligo Enterprise
          company_url: 'https://www.telligo.fr'
          company_logo: logo_Telligo
          location: Multiple regions, France
          date_start: '2013-06-01'
          date_end: '2014-08-31'
          description: |2-
              Managing summer camps for children and teenagers, with responsibilities such as:

              * Take care of budgets and schedules
              * Manage and train the team
              * Organize and lead team meetings
              * Interact with external partners and sponsors
        - title: Science animator
          company: Telligo Enterprise
          company_url: 'https://www.telligo.fr'
          company_logo: logo_Telligo
          location: Multiple regions, France
          date_start: '2009-06-01'
          date_end: '2014-08-31'
          description: Taking part in summer camps to teach scientific notions to children and teenagers, focused on different themes such as Astronomy, Molecular Cooking or Biology, with playful workshops.
    design:
      columns: '2'
  - block: experience
    content:
      title: Teaching experience
      date_format: Jan 2006
      items:
        - title: 'Teaching Assistant'
          company: 'Université du Québec à Rimouski'
          company_url: 'https://uqar.ca'
          company_logo: logo_UQAR
          location: 'Rimouski, Canada'
          date_start: '2022-09-13'
          date_end: '2022-12-20'
          description: 'Taught the functional aspects of various coastal ecosystems to undergraduate students, as part of the course Functioning of marine ecosystems (BIO37800).'
        - title: 'Teaching Assistant'
          company: 'Université du Québec à Rimouski'
          company_url: 'https://uqar.ca'
          company_logo: logo_UQAR
          location: 'Rimouski, Canada'
          date_start: '2022-01-12'
          date_end: '2022-04-28'
          description: 'Taught the physical, chemical and geological basics of marine ecosystems to undergraduate students, as part of the course Introduction to oceanography (BIO17021).'
        - title: 'Teaching Assistant'
          company: 'Université du Québec à Rimouski'
          company_url: 'https://uqar.ca'
          company_logo: logo_UQAR
          location: 'Rimouski, Canada'
          date_start: '2022-03-23'
          date_end: '2022-04-13'
          description: 'Taught the basics of multivariate statistics (similarity measures, ordination, classification) to graduate students, as part of the course Statistical approaches in oceanography (OCE75420).'
        - title: 'Teaching Assistant'
          company: 'Université du Québec à Rimouski'
          company_url: 'https://uqar.ca'
          company_logo: logo_UQAR
          location: 'Rimouski, Canada'
          date_start: '2021-09-01'
          date_end: '2021-12-12'
          description: 'Taught the phylogeny, morphological characteristics and biology of marine invertebrates to undergraduate students, as part of the course Invertebrates (BIO13099).'
        - title: 'Teaching Assistant'
          company: 'Université du Québec à Rimouski'
          company_url: 'https://uqar.ca'
          company_logo: logo_UQAR
          location: 'Rimouski, Canada'
          date_start: '2021-03-24'
          date_end: '2021-03-31'
          description: 'Taught the basics of multivariate statistics (similarity measures, ordination, classification) to graduate students, as part of the course Statistical approaches in oceanography (OCE75420).'
        - title: 'Lecturer'
          company: 'Québec Center for Biodiversity Science'
          company_url: 'https://qcbs.ca'
          company_logo: logo_QCBS
          location: 'Québec, Canada'
          date_start: '2019-11-01'
          date_end: '2019-12-06'
          description: 'Taught how to use R language for data analysis, object manipulation and programmation for beginner and intermediate users.'
        - title: 'Lecturer'
          company: 'Québec Center for Biodiversity Science'
          company_url: 'https://qcbs.ca'
          company_logo: logo_QCBS
          location: 'Québec, Canada'
          date_start: '2018-09-01'
          date_end: '2018-12-14'
          description: 'Taught how to use R language for data analysis, object manipulation and programmation for beginner and intermediate users.'
        - title: 'Lecturer'
          company: 'Québec-Océan'
          company_url: 'https://quebec-ocean.ulaval.ca'
          company_logo: logo_QO
          location: 'Québec, Canada'
          date_start: '2018-04-14'
          date_end: '2018-04-14'
          description: 'Organized and presented a course on spatial analyses and geographic information systems (GIS) during the student retreat of Québec-Océan network, with the collaboration of inSileco.'
    design:
      columns: '2'
  - block: experience
    content:
      title: Associative experience
      date_format: Jan 2006
      items:
        - title: Elected representative for postdoctoral fellows
          company: 'Québec-Océan Administration Committee'
          company_url: 'https://www.quebec-ocean.ulaval.ca'
          company_logo: logo_QO
          location: 'Québec, Canada'
          date_start: '2022-01-01'
          date_end: '2022-10-02'
          description:
        - title: Elected representative for internal communications
          company: 'Québec-Océan Student Committee'
          company_url: 'https://www.quebec-ocean.ulaval.ca'
          company_logo: logo_QO
          location: 'Québec, Canada'
          date_start: '2018-11-01'
          date_end: '2019-11-13'
          description:
        - title: Elected representative of PhD students
          company: 'Québec-Océan Student Committee'
          company_url: 'https://www.quebec-ocean.ulaval.ca'
          company_logo: logo_QO
          location: 'Québec, Canada'
          date_start: '2017-11-01'
          date_end: '2018-10-30'
          description:
        - title: Treasurer and coordinator
          company: 'Université du Québec à Rimouski Student Group for Science Vulgarization'
          company_url: 'https://revus-uqar.weebly.com'
          company_logo: logo_REVUS
          location: Rimouski, Canada
          date_start: '2016-06-01'
          date_end: '2017-05-31'
          description:
        - title: Elected coordinator
          company: Canadian Healthy Oceans Network Student Committee
          company_url: 'https://chone2.ca'
          company_logo: logo_CHONe
          location: Rimouski, Canada
          date_start: '2015-10-01'
          date_end: '2020-09-30'
          description:
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Workshops and training'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url:
          title: 'Biodiversity modelling'
          organization: 'Université de Sherbrooke'
          organization_url: 'https://www.usherbrooke.ca'
          date_start: '2021-08-16'
          date_end: '2021-08-27'
          url: ''
          description: ''
        - certificate_url:
          title: 'SMAART-Sentinel North'
          organization: 'Data acquisition and treatment: from sensor to information'
          organization_url: 'https://sentinellenord.ulaval.ca'
          date_start: '2020-02-21'
          date_end: '2020-02-23'
          url: 'https://sentinellenord.ulaval.ca/fr/smaart2020'
          description: ''
        - certificate_url:
          title: 'Calculation of cumulative impact scores at the local scale'
          organization: 'Marine Ethnoecology Research Lab, University of Victoria'
          organization_url: 'https://natalieban.wordpress.com'
          date_start: '2019-03-01'
          date_end: '2019-04-01'
          url: ''
          description: 'Research interneship supervised by Natalie Ban and her team.'
        - certificate_url:
          title: 'Geospatial analyses'
          organization: 'Canadian Healthy Oceans Network'
          organization_url: 'https://chone2.ca'
          date_start: '2018-12-01'
          date_end: ''
          url: ''
          description: ''
        - certificate_url:
          title: 'Application of the M-AMBI index in the region of Sept-Îles, Canada'
          organization: 'Dinard Marine Station, IFREMER'
          organization_url: 'https://wwz.ifremer.fr/bretagne_nord'
          date_start: '2018-06-01'
          date_end: '2018-07-01'
          url: ''
          description: 'Research internship supervised by Nicolas Desroy, Aurélie Foveau and their team.'
        - certificate_url:
          title: 'Bayesian statistics for ecologists'
          organization: 'Université de Sherbrooke'
          organization_url: 'https://www.usherbrooke.ca'
          date_start: '2017-08-14'
          date_end: '2017-08-18'
          url: ''
          description: ''
        - certificate_url:
          title: 'Cartography and GIS, Data management'
          organization: 'Biology Department, Université Laval'
          organization_url: 'https://www.bio.ulaval.ca'
          date_start: '2017-08-01'
          date_end: ''
          url: ''
          description: ''
        - certificate_url:
          title: 'Advanced applications of R'
          organization: 'R à Québec Conferences'
          organization_url: 'http://raquebec.ulaval.ca'
          date_start: '2016-05-01'
          date_end: '2019-05-01'
          url: ''
          description: ''
        - certificate_url:
          title: 'Introduction to environmental indicators'
          organization: 'Canadian Healthy Oceans Network'
          organization_url: 'https://chone2.ca'
          date_start: '2016-09-01'
          date_end: ''
          url: ''
          description: ''
        - certificate_url:
          title: 'Ecology, taxonomy and identification of coastal marine flora in Bretagne'
          organization: 'Roscoff Marine Station, Université Pierre et Marie Curie'
          organization_url: 'http://www.sb-roscoff.fr'
          date_start: '2015-08-01'
          date_end: ''
          url: 'http://www.sb-roscoff.fr/en/marine-flora'
          description: ''
        - certificate_url:
          title: 'Detection of invasive species in Arctic Canadian harbors'
          organization: 'Benthic Ecology Lab, UQAR/ISMER'
          organization_url: 'https://ismer.ca'
          date_start: '2015-01-01'
          date_end: '2015-06-01'
          url: ''
          description: 'Research internship supervised by Philippe Archambault and Jesica Goldsmit.'
        - certificate_url:
          title: 'Scientific communication'
          organization: 'Banyuls Oceanographic Observatory, Université Pierre et Marie Curie'
          organization_url: 'https://wwwphp.obs-banyuls.fr'
          date_start: '2014-04-01'
          date_end: ''
          url: ''
          description: ''
        - certificate_url:
          title: 'Multivariate analyses applied to ecology'
          organization: 'Villefranche-sur-Mer Oceanographic Observatory, Université Pierre et Marie Curie'
          organization_url: 'http://www.obs-vlfr.fr'
          date_start: '2014-08-01'
          date_end: ''
          url: 'http://www.obs-vlfr.fr/web/images/docenseignement/AMEM_en.pdf'
          description: ''
        - certificate_url:
          title: 'Study of benthic communities of Antarctica using video transects'
          organization: 'Concarneau Marine Station, French National Natural Museum'
          organization_url: 'http://www.stationmarinedeconcarneau.fr'
          date_start: '2014-03-01'
          date_end: '2014-04-01'
          url: ''
          description: 'Research internship supervised by Marc Éleaume.'
        - certificate_url:
          title: 'Ecology, taxonomy and identification of coastal marine fauna in Bretagne'
          organization: 'Roscoff Marine Station, Université Pierre et Marie Curie'
          organization_url: 'http://www.sb-roscoff.fr'
          date_start: '2013-07-01'
          date_end: ''
          url: 'http://www.sb-roscoff.fr/en/roscoff-marine-station/education-and-training/summer-schools/taxonomy-marine-fauna-29-july-20-august-2019'
          description: ''
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      coordinates:
        latitude: '45.50861'
        longitude: '-73.56167'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: formspree
        formspree:
          id: moqzglqz
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
