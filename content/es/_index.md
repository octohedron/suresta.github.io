---
title: "Home"
date: 2024-08-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "DevOps & Software Engineering Consultancy"
      text: TRANSFORMING YOUR DEVELOPMENT LIFECYCLE WITH EXPERT GUIDANCE
      primary_action:
        text: Get Started
        url: /contact/
        icon: rocket-launch
      secondary_action:
        text: Our services
        url: /services
      announcement:
        text: "Streamline, automate, and optimize your software delivery with our DevOps expertise."
        link:
          text: "Read more"
          url: "/blog/launching-suresta/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5

  - block: stats
    content:
      items:
        - statistic: "1B+"
          description: |
            Users of our reliable  
            software solutions
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
      title: Our Expertise
      text: Our consultancy offers specialized expertise across the entire DevOps and software engineering spectrum
      items:
        - name: DevOps Implementation
          icon: cog
          description: Expert guidance on implementing DevOps practices, CI/CD pipelines, and automation to streamline your software delivery process and increase deployment frequency
        - name: Infrastructure as Code
          icon: code-bracket
          description: Design and implementation of infrastructure as code solutions using tools like Terraform, Ansible, and CloudFormation to ensure consistent, repeatable deployments
        - name: Cloud Architecture
          icon: sparkles
          description: Strategic consultation on cloud infrastructure design, optimization, and management across Azure, Google Cloud, AWS, and Kubernetes environments
        - name: Site Reliability Engineering
          icon: shield-check
          description: Implementation of SRE practices including observability, incident response, and service level objectives to enhance system reliability and performance
        - name: DevSecOps Integration
          icon: lock-closed
          description: Embedding security throughout your development lifecycle with automated security testing, compliance monitoring, and vulnerability management
        - name: Agile Transformation
          icon: arrow-path
          description: Guidance on adopting agile methodologies and practices that complement your DevOps initiatives to improve team collaboration and delivery speed
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Who are we?
          text: Suresta is a DevOps and software engineering consultancy based in Valencia, Spain. We help organizations bridge the gap between development and operations, implementing modern practices like CI/CD, infrastructure as code, and site reliability engineering (SRE) to accelerate delivery while maintaining stability and quality.
          feature_icon: check
          features:
            - "Accelerate software delivery through automation and streamlined processes"
            - "Improve system reliability and reduce downtime"
            - "Enhance collaboration between development and operations teams"
            - "Balance speed of innovation with operational stability"

          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Learn More About DevOps
            url: https://aws.amazon.com/devops/what-is-devops/
        - title: Why choose our consultancy?
          text: Our approach works differently than other firms and developers. We provide expert consultation tailored to your specific needs, offering flexibility and value without the overhead of hiring full-time employees or dealing with rigid service contracts.
          feature_icon: bolt
          features:
            - "Personalized solutions based on your specific project requirements"
            - "Access to specialized expertise without long-term commitments"
            - "Flexible engagement models adapted to your project timeline and scope"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Get Started
            url: /contact/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: "Our Clients"
      text: "What our clients are saying about our services"
      items:
        - name: "Satisfied Customer"
          role: "Manager at GS"
          image: "testimonial-2.jpg"
          text: "Our Cloud Enablement team brought in Suresta to manage a complex identity and access management application. Their technical expertise, covering SAML, OIDC, OAuth, Go, React, AWS serverless, and Azure AD, was exactly what we needed. Thanks to their contributions, we saw significant improvements in application stability, test coverage, and logging clarity. The team communicates effectively and is a pleasure to work with. In addition to their technical prowess, they are genuinely nice people that I highly recommend."
        - name: "Satisfied Customer"
          role: "Manager at the EPO"
          image: ""
          text: "Suresta has proven to be an exceptional partner, providing developers with all the skills one would want in top-notch software professionals. Their mastery of front-end programming languages has been invaluable to both our company and our clients. The team consistently delivers on time, helping nurture long-term client relationships. Their work is always top-tier, and they are open to feedback and committed to continuous improvement. Self-motivated and eager to solve problems, Suresta has been a great asset to our projects."

    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: "Get Started with a Consultation"
      text: Contact us to discuss your project needs
      button:
        text: Get Started
        url: /contact/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
