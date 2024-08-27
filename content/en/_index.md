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
      title: "Software Reliability, Integrity, and Assistance"
      text: SIMPLE SUBSCRIPTION SERVICE, CANCEL ANY TIME.
      primary_action:
        text: Get Started
        url: /contact/
        icon: rocket-launch
      secondary_action:
        text: Our services
        url: /
      announcement:
        text: "Announcing the world's first Site Reliability and Assurance Service Provider."
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
      items:
        - title: "Basic"
          text: "Start off with our free solutions and essential checks."
          offer:
            price: 0.00
            discount: ""
            frequency: "Free"
            text: "Special offer"
          arguments:
            - icon: "eye"
              text: "Basic observability tools"
            - icon: "bell-alert"
              text: "Simple alerts and notifications"
            - icon: "document-text"
              text: "Access to documentation resources"
            - icon: "check-circle"
              text: "Up to 3 automated health checks per project"
            - icon: "shield-check"
              text: "Up to 3 automated port scans per project"
            - icon: "clock"
              text: "1 hour of free consultation per month"
          cta:
            text: "Get Started"
            url: "/contact"
        - title: "Essential"
          text: "All free tier benefits with additional essential features."
          offer:
            price: 43.00
            discount: ""
            frequency: "per month"
            text: "Billed monthly"
          arguments:
            - icon: "eye"
              text: "Storage capacity monitoring alerts"
            - icon: "check-circle"
              text: "Up to 10 automated health checks per project"
            - icon: "shield-check"
              text: "Basic vulnerability scanning for one website"
            - icon: "puzzle-piece"
              text: "Basic linting setup with pre-commit hooks"
            - icon: "clock"
              text: "1 hour per month of software developer consultation"
            - icon: "clipboard-document-check"
              text: "1 hour per month of code reviews by a senior engineer"
          cta:
            text: "Get Started"
            url: "/contact"
        - title: "Advanced"
          text: "All Essential tier benefits with even more advanced features."
          offer:
            price: 97.00
            discount: ""
            frequency: "per month"
            text: "Billed monthly"
          arguments:
            - icon: "bell-alert"
              text: "Automated alerts setup for up to 2 projects"
            - icon: "cloud"
              text: "Basic cloud backup solutions included"
            - icon: "circle-stack"
              text: "Managed database clusters setup and support"
            - icon: "cog"
              text: "Simple CI/CD pipeline setup with GitHub Actions"
            - icon: "cloud-arrow-up"
              text: "Basic DevOps and cloud management services"
            - icon: "shield-check"
              text: "1 hour per week of security audits and senior software engineer consultation"
          cta:
            text: "Get Started"
            url: "/contact"
        - title: "Professional"
          text: "Comprehensive consultation and IT support."
          offer:
            price: -1
            discount: ""
            frequency: "monthly or yearly"
            text: "Custom contract"
          arguments:
            - icon: "academic-cap"
              text: "Technical leadership and mentorship"
            - icon: "puzzle-piece"
              text: "Custom integrations and solutions"
            - icon: "shield-check"
              text: "Managed cybersecurity services"
            - icon: "check-circle"
              text: "Incident reports and post-mortem analysis"
            - icon: "clock"
              text: "1 hour per week of senior software engineer consultation"
            - icon: "clipboard-document-list"
              text: "1 hour per month of senior architect consultation and system reviews"
          cta:
            text: "Contact Us"
            url: "/contact"
        - title: "Premium"
          text: "Comprehensive and tailored IT consulting."
          offer:
            price: -1
            discount: ""
            frequency: "monthly or yearly"
            text: "Custom contract"
          arguments:
            - icon: "cloud"
              text: "Cloud cost optimization and FinOps implementation"
            - icon: "cog-8-tooth"
              text: "Fully managed IT services for up to 100 projects"
            - icon: "shield-check"
              text: "SIEM solutions with 24/7 monitoring"
            - icon: "server-stack"
              text: "Multi-cloud management and support"
            - icon: "code-bracket-square"
              text: "Advanced Kubernetes management with service mesh"
            - icon: "clipboard-document-check"
              text: "40 hours per week of senior architect and technical leadership"
          cta:
            text: "Contact Us"
            url: "/contact"
        - title: "Elite"
          text: "Custom enterprise solutions to fit your unique needs."
          offer:
            price: -1
            discount: ""
            frequency: "monthly or yearly"
            text: "Custom contract"
          arguments:
            - icon: "building-office-2"
              text: "Enterprise IT management for 100+ projects"
            - icon: "cloud"
              text: "Multi-cloud architecture and FinOps"
            - icon: "circle-stack"
              text: "Data lake implementation and management"
            - icon: "light-bulb"
              text: "Advanced AI/ML implementations"
            - icon: "shield-check"
              text: "Quarterly red team exercises and penetration testing"
            - icon: "clock"
              text: "Monthly digital transformation consulting"
          cta:
            text: "Contact Us"
            url: "/contact"
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
          text: Suresta is software development consultancy and software services provider based in Valencia, Spain, specializing in site reliability engineering (SRE) for all types of software. The link between development and operations is critical, and we're here to help you build it.
          feature_icon: check
          features:
            - "Bridge the gap between developers and operations"
            - "Avoid outages"
            - "Provide peace of mind on the integrity and realiability of your projects"
            - "Balance reliability and progress"

          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Read More about SRE
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

