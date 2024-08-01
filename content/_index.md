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
      title: "Software Reliability, Integrity, and Assistance"
      text: SIMPLE SUBSCRIPTION, CANCEL ANY TIME.
      primary_action:
        text: Get Started
        url: /contact/
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
        - statistic: "13+"
          description: |
            Years of experience  
            among each of our team members
        - statistic: "200k+"
          description: |
            Incidents resolved  
            since 2014
        - statistic: "40+"
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
        - name: Resolve issues through specialists
          icon: bolt
          description: Discover on-call support and personalized assistance, as well as alert systems and observability tools to find and solve problems quickly
        - name: Cloud
          icon: sparkles
          description: Manage cloud capacity, costs, and debugging in services like Azure, Google Cloud, AWS, and Kubernetes
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
          text: Suresta is a boutique software agency based out of Valencia, Spain, specializing in site reliability engineering (SRE) for all types of software. The link between development and operations is critical, and we're here to help you build it.
          feature_icon: check
          features:
            - "Bridge the gap between developers and operations"
            - "Avoid outages"
            - "Provide peace of mind on the integrity and realiability of your projects"
            - "Balance reliability and progress"
            
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text:  Read More about SRE
            url: https://www.netapp.com/devops-solutions/what-is-site-reliability-engineering/
        - title: Why a subscription?
          text: Our unique payment model works differently than other firms and developers. Rather than the exorbatant fees of a contractor, or the daunting amount of time, training, and paperwork of onboarding an employee, we offer flexibility without sacrificing value
          feature_icon: bolt
          features:
            - "No contracts laden with obligations, contingincies, or high payments"
            - "No HR paperwork or lengthy training for new employees"
            - "Services fitted to your needs, for as long as you need it"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Get Started
            url: https://suresta.com/templates/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: "Our Team Members' Clients"
      text: "Goldman Sachs, iHealth, inzpire.me, CECOTEC, POWER2DM, NTT DATA, Salzburg Research, The European Patent Officegit " 
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
      title: "Get Started with a Free Consultation"
      text: Contact us below
      button:
        text: Get Started
        url: https://suresta.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

