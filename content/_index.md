---
title: "Home"
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "Software Reliability and Assurance as a Service"
      text: SIMPLE SUBSCRIPTION, CANCEL ANY TIME.
      primary_action:
        text: Get Started
        url: https://suresta.com/contact/
        icon: rocket-launch
      secondary_action:
        text: Our services
        url: https://suresta.com/
      announcement:
        text: "Announcing the release of version 2."
        link:
          text: "Read more"
          url: "/blog/"
  - block: stats
    content:
      items:
        - statistic: "10+"
          description: |
            Years of experience  
            among all our team members
        - statistic: "100k+"
          description: |
            Incidents resolved  
            since 2016
        - statistic: "300+"
          description: |
            Projects supported  
            in various platforms
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Our team offers dozens of technical and business services to suit your needs 
      items:
        - name: Optimize Security
          icon: magnifying-glass
          description: Options include incident reports and post mortems, as well as tracing, automated monitoring, and other features to mitigate risk, employ proactive measures, and manage your exposure
        - name: Resolve issues guided by specialists
          icon: bolt
          description: Options for on-call support and personalized assistance, as well as alert systems and observability tools to resolve issues quickly and smoothly
        - name: Cloud
          icon: sparkles
          description: Manage cloud capacity, cost management, and debugging with services like Azure, Google Cloud, AWS, and Kubernetes
        - name: Coding Assistance
          icon: code-bracket
          description: Confer with our experts in languages like Golang, Python, Typescript, Javascript, Java, and others to troubleshoot and refactor your code
        - name: Highly Rated
          icon: star
          description: World-class expertise, including projects with Goldman Sachs, The European Patent Office, and dozens of other industry leaders
        - name: Personalize and Customize
          icon: rectangle-group
          description: Our world-class customer service team will work with you to find a subscription package that works for you and your needs, no more no less
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Who are we?
          text: Suresta is a boutique site reliability engineering (SRE) firm for businesses of all sizes
          feature_icon: check
          features:
            - "Bridging the gap between developers and operations"
            - "Providing peace of mind on the integrity and realiability of your projects"
            
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://suresta.com/templates/
        - title: Why SRE?
          text: The link between development and operations is critical, we help affirm it
          feature_icon: bolt
          features:
            - "Avoid outages"
            - "Balance realiability and progress"
            - "Manage incidents and respond quickly"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Read More about SRE
            url: https://www.netapp.com/devops-solutions/what-is-site-reliability-engineering/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: "Testomonials of our development team"
      text: ""
      items:
        - name: ""
          role: "Team Lead at NN Investment Partners"
          # Upload image to `assets/media/` and reference the filename here
          image: ""
          text: ""
        - name: "Richard Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: ""
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: "Pizza"
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://suresta.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

