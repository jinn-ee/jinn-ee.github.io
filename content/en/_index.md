---
# Leave the homepage title empty to use the site title
title: SEO and Digital Marketing by JINN.ee
date: 2023-02-06T20:42:09+02:00
type: landing

sections:
  - block: hero
    content:
      title: A high-quality website<br> is crucial for businesses<br> in the digital age
      image:
        filename: 
      cta:
        label: '**Get a Proposal**'
        url: '/#contact'
      cta_alt:
        label: Learn more about SEO services
        url: seo/
      cta_note:
        label: Maximize your profits with<br> our marketing services
      text: |-
        <!--Custom spacing-->
        <div class="mb-3"></div>
        
        Investing in effective SEO helps to improve the long-term value of your website and your overall business.

        <!--Custom spacing-->
        <div class="mb-3"></div>
    design:
      background:
        image:
            filename: j1.jpg
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
      title: Maximize your profits with our marketing services
      items:
        - name: Search Engine Optimization
          description: Boost your search rankings and website traffic with our proven SEO services - guaranteed results!
          icon: google
          icon_pack: fab
        - name: Local SEO
          description: A fantastic opportunity to dominate your local market and attract more qualified leads and sales
          icon: map-location-dot
          icon_pack: fas
        - name: E-Commerce Development
          description: Experience the security and sales-boosting power of a highly functional online store and see your profits skyrocket
          icon: wordpress-simple
          icon_pack: fab
        - name: Conversion Optimization
          description: Transform your website into a lead-generating machine with our Conversion Optimization and watch your sales soar
          icon: money-bill-trend-up
          icon_pack: fas
        - name: Pay Per Click
          description: PPC can increase visibility and attract more customers quickly - we create targeted ads and set up successful campaigns
          icon: rectangle-ad
          icon_pack: fas
        - name: Marketing Strategy
          description: Outsmart your competition with a customized marketing plan that scientifically targets the most lucrative opportunities
          icon: ranking-star
          icon_pack: fas
        - name: Content Marketing
          description: Partner with us for increased website traffic, conversions, brand awareness, and customer loyalty
          icon: arrows-to-circle
          icon_pack: fas
        - name: Ecommerce Marketing
          description: Boost your sales and customer base with ecommerce marketing using content, search, and social media
          icon: euro-sign
          icon_pack: fas
        - name: Business Intelligence
          description: 'Transform your decision-making with BI: unlock the power of data analysis for business success'
          icon: brain
          icon_pack: fas

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: 'Internet marketing blog'
      text: 'SEO and Digital Marketing'
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
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
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
      title: We're here to help
      subtitle: Fill out the form
      text: |-
            Can you share a little bit about your biz and website with us? If you want a friendly chat over the phone, leave us your number and we'll call you. If texting is more your style, drop us your Instant Messenger. After getting to know you and your business goals, we'll hit you up with a personalized proposal. And if you're a fan of face-to-face chats, you can book a video appointment with us below the contact form.
      # Contact (add or remove contact options as necessary)
      email: contact@jinn.ee
      phone: 37255514747
      appointment_url: 'https://calendly.com/jinnee/video-chat'
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
