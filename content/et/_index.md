---
# Leave the homepage title empty to use the site title
title: SEO ja digitaalne turundus JINNi poolt
date: 2023-02-06T20:42:09+02:00
type: landing

sections:
  - block: hero
    content:
      title: Kvaliteetne veebisait<br> on ettevõtete jaoks ülioluline digitaalajastul<br>
      image:
        filename: 
      cta:
        label: '**Küsi pakkumist**'
        url: '/et/#contact'
      cta_alt:
        label: Lisainfo SEO teenuste kohta
        url: et/seo/
      cta_note:
        label: Suurendage oma kasumit <br>meie turundusteenustega
      text: |-
        <!--Custom spacing-->
        <div class="mb-3"></div>
        
        Investeerimine tõhusasse SEO-sse aitab parandada teie veebisaidi ja kogu ettevõtte pikaajalist väärtust.

        <!--Custom spacing-->
        <div class="mb-3"></div>
    design:
      background:
        image:
            filename: bg3.jpg
        gradient_end: '#292E49'
        gradient_start: '#536976'
        text_color_light: true

        # #0f2027 #203a43 #2c5364
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Suurendage oma kasumit meie turundusteenustega
      items:
        - name: Otsingumootori optimeerimine
          description: Suurendage oma otsinguridu ja veebilehe külastatavust meie tõestatud SEO-teenuste abil - garanteeritud tulemused!
          icon: google
          icon_pack: fab
        - name: Kohalik SEO
          description: Fantastiline võimalus domineerida oma kohalikul turul ja meelitada ligi rohkem kvalifitseeritud liide ja müüki.
          icon: map-location-dot
          icon_pack: fas
        - name: E-kaubanduse arendamine
          description: Avastage turvalisus ja müügitulu suurendav jõud, mida annab kõrgelt funktsionaalne e-pood, ning näete oma kasumit hüppeliselt kasvamas.
          icon: wordpress-simple
          icon_pack: fab
        - name: Konversiooni optimeerimine
          description: Muutke oma veebisait meie konversiooni optimeerimise abil juhtivaks masinaks ja vaadake, kuidas teie müük tõuseb.
          icon: money-bill-trend-up
          icon_pack: fas
        - name: Pay Per Click
          description: PPC võib suurendada nähtavust ja ligi tõmmata kliente - me loome sihipäraseid reklaame ja käivitame edukaid kampaaniaid.
          icon: rectangle-ad
          icon_pack: fas
        - name: Turundusstrateegia
          description: Kavaldage oma konkurente kohandatud turundusplaaniga, mis sihib teaduslikult kõige tulusamaid võimalusi.
          icon: ranking-star
          icon_pack: fas
        - name: Sisuturundus
          description: Tehke meiega koostööd, et suurendada veebisaidi külastatavust, konversioone, brändi tuntust ja klientide lojaalsust.
          icon: arrows-to-circle
          icon_pack: fas
        - name: Ecommerce Marketing
          description: Suurendage oma müüki ja kliendibaasi e-kaubanduse turunduse abil, kasutades sisu, otsingut ja sotsiaalmeediat.
          icon: euro-sign
          icon_pack: fas
        - name: Business Intelligence
          description: 'Muutke oma otsuste tegemine BI abil: kasuta andmeanalüüsi võimsust ettevõtte edu saavutamiseks'
          icon: brain
          icon_pack: fas

  - block: collection
    id: posts
    content:
      title: Viimased postitused
      subtitle: 'Interneti-turunduse blogi'
      text: 'SEO ja digitaalne turundus'
      # Choose how many pages you would like to display (0 = all pages)
      count: 1
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
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
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Sügav õppimine
#          tag: Sügav õppimine
#        - name: Muud
#          tag: Demo
#    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false

  - block: contact
    id: contact
    content:
      title: Me oleme siin, et aidata
      subtitle:
      text: |-
            Palun jagage natuke infot oma äri ja veebisaidi kohta. Kui soovite sõbralikku vestlust telefoni teel, jätke meile oma number ja võtame teiega ühendust. Kui teksti saatmine on rohkem teie moodi, kirjutage meile. Pärast tutvumist teie ärieesmärkidega teeme teile personaalse ettepaneku.
      # Contact (add or remove contact options as necessary)
      email: contact@jinn.ee
      phone: 37255599546
#      appointment_url: 'https://calendly.com/jinnee/video-chat'
      address:
        street: Väike-Ameerika 8
        city: Tallinn
        region: Harjumaa
        postcode: '10129'
        country: Estonia
        country_code: EE
      directions: 'Gooseberry Thieves OÜ Reg.16621721'
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: formspree
        formspree:
          id: xdovenyo
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---