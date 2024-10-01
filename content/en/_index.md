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
      title: "Protect Access, Manage Identities: Tailored IAM Solutions for Your Business"
      text: SIMPLE SUBSCRIPTION SERVICE, CANCEL ANY TIME.
      primary_action:
        text: Get Started
        url: /contact/
        icon: rocket-launch
      secondary_action:
        text: Our services
        url: /services
      announcement:
        text: "Announcing the world's safest and simplest IAM security-focused provider"
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
  - block: prices
    content:
      heading:
        title: "Flexible pricing options"
      column: 6
      items: []
      background: false

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
      title: Features
      text: Our team offers a wide range of Identity and Access Management (IAM) services to fit your needs
      items:
        - name: Strengthen Security
          icon: magnifying-glass
          description: Incident reports, post-mortems, and automated monitoring help mitigate security risks, implement proactive measures, and manage IAM-related vulnerabilities
        - name: Resolve IAM Issues with Experts
          icon: bolt
          description: Access on-call IAM specialists, personalized support, and alert systems to quickly resolve access control, identity verification, and authentication issues
        - name: Cloud IAM Integration
          icon: sparkles
          description: Manage IAM across cloud platforms like Azure AD, AWS, Google Cloud, and Kubernetes to ensure secure access management and compliance
        - name: Identity Lifecycle Assistance
          icon: code-bracket
          description: Consult with our experts to streamline user provisioning, SAML, OAuth, OIDC, and MFA implementations, as well as troubleshoot IAM configurations
        - name: Proven Expertise
          icon: star
          description: Trusted by industry leaders such as Goldman Sachs and The European Patent Office for secure and scalable IAM solutions
        - name: Customized IAM Solutions
          icon: rectangle-group
          description: Our team works closely with you to customize your IAM solutions, ensuring your specific identity management needs are met efficiently

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Who are we?
          text: Suresta is an Identity and Access Management (IAM) consultancy and software services provider based in Valencia, Spain. We specialize in securing digital identities and streamlining access management across multiple platforms.
          feature_icon: check
          features:
            - "Enable seamless authentication and authorization"
            - "Prevent unauthorized access and mitigate identity breaches"
            - "Ensure compliance with security standards"
            - "Balance security and user experience"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Learn More about IAM Solutions
            url: https://www.netapp.com/devops-solutions/what-is-site-reliability-engineering/
        - title: Why a subscription?
          text: Our subscription model provides flexibility and value in IAM management. Instead of high contractor fees or the long process of hiring internal staff, you get expert IAM services tailored to your needs.
          feature_icon: bolt
          features:
            - "No long-term contracts or hidden fees"
            - "No need for complex onboarding or training for new staff"
            - "Services customized to your IAM requirements for as long as you need them"
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
      title: "Get Started with a Free Consultation"
      text: Contact us below
      button:
        text: Get Started
        url: /contact/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

