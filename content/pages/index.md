---
title: Home
sections:
  - section_id: hero
    type: section_hero
    image_alt: App preview
    title: 'Weather data, for you'
    content: |
      Get the latest NOAA radar imagery with custom visualizations.
    actions:
      - label: Learn More
        url: /features
        style: primary
  - section_id: features
    type: section_features
    background: gray
    title: Features
    subtitle: 'Realtime, personalized radar imagery'
    features:
      - title: Personalized Radar
        image: images/royal-amaranth.webp
        image_alt: App preview on a phone and tablet
        content: >
          Choose from our radar theme or work with us to provide your own
          personalized imagery.


          Use optional map layers to enhance or minimize information.
        actions:
          - label: Learn More
            url: /features
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
      - title: Modern Formats
        image: images/response_anim_mixed.webp
        image_alt: App users welcoming a new member
        content: >
          Choose from a variety of formats including animated WEBP, which
          produces a higher quality animation over GIF at a fraction of the
          size. Static frames are also available.
        actions:
          - label: Learn More
            url: /features
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
      - title: 'Fair Pricing, Privacy-first'
        image_alt: App user profile preview
        content: >
          Pricing is billed on a pre-set quota. Change your plan at any time.
          The first 500 requests / month are not billed.


          We value our privacy and so should you. We do not sell customer data
          and anonymize internal metrics to enhance the service.
        actions:
          - label: Learn More
            url: /features
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
  - section_id: lorem-ipsum
    title: Pricing
    subtitle: Choose the plan that fits your needs
    background: gray
    pricing_plans:
      - title: Free
        subtitle: Real-time live brackground
        price: Free
        details: |
          #### Get to know Radar

          *   Standard map layer
          *   500 requests / month
        highlight: false
        actions:
          - label: Start for Free
            url: /signup?plan=free
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        type: pricing_plan
      - title: Hobby
        subtitle: Updated imagery right in Slack
        price: $4 / month
        details: |
          #### Enter Personalized Radar

          *   Optional map layers (roads, admin labels)

          *   Radar themes

          *   10,000 requests / month
        highlight: false
        actions:
          - label: Sign Up
            url: /signup?plan=hobby
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        type: pricing_plan
      - title: Pro
        subtitle: Build your own app
        price: $68 / month
        details: |
          #### Unlock Full Customization

          *   \+ Everything in Hobby

          *   Branding

          *   Custom map styles

          *   100,000 requests / month
        highlight: false
        actions:
          - label: Sign Up
            url: /signup?plan=pro
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        type: pricing_plan
    type: section_pricing
  - section_id: features-apps
    title: Apps
    subtitle: Ways to use Radar
    background: gray
    features:
      - title: Android Live Wallpaper
        content: >
          #### Looping radar in your pocket


          Our unique live wallpaper uses your current location to provide
          realtime loops of weather conditions in your area.


          $12 / year
        image_alt: lorem-ipsum
        actions: []
        type: feature_item
      - title: Radar for Slack
        content: >
          #### The latest imagery is one slash command away


          Use the interactive workflow to manage your account's settings and
          share imagery with the team.


          Free to get started.
        image_alt: lorem-ipsum
        actions: []
        type: feature_item
    type: section_features
  - section_id: lorem-ipsum
    title: Web
    content: >
      #### Beautiful radar in full resolution glory!


      Our web app provides the tooling needed to customize your experience and
      to view up to date imagery.


      *   Radar style editor

      *   Themes

      *   Map themes
    image_alt: lorem-ipsum
    background: gray
    actions: []
    type: section_content
  - section_id: call-to-action
    type: section_cta
    title: Ready for personalized imagery?
    subtitle: Sign up now to lock in our introductory rates.
    actions:
      - label: Get Started
        url: /signup
        style: primary
seo:
  title: Radar Love by Fount
  description: Personalized radar imagery
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Radar Love by Fount
      keyName: property
    - name: 'og:description'
      value: Personalized radar imagery
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Radar Love by Fount
    - name: 'twitter:description'
      value: Personalized radar imagery
layout: landing
---
