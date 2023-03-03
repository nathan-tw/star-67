---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Go
          icon: golang
          icon_pack: fab
        - name: Python
          icon: python
          icon_pack: fab
        - name: AWS
          icon: aws
          icon_pack: fab
        - name: Git
          icon: git-alt
          icon_pack: fab
        - name: Database
          icon: database
          icon_pack: fas

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
        - title: Cloud Backend Engineer
          company: Ubiquiti
          company_url: "https://ui.com"
          company_logo: ubiquiti
          location: Taipei
          date_start: "2022-02-20"
          date_end: ""
          description: |2-
              * **Email**: Maintained a high-performance email service that facilitates asynchronous email sending, rate limiting, and advanced template rendering using YAML/Lua templates.
              * **Rate Limit**: Designed and implemented a highly effective rate limit mechanism for email service to prevent misdelivered emails, which resulted in a significant reduction in the misdelivered email rate by 2-5% daily.
              * **Configuration Optimization**: Designed and implemented a configuration checking stage during continuous integration, resulting in an 80% reduction in misconfigurations.
              * IP Data ETL: Designed and implemented an ETL workflow for processing IP-related data to build an IP reputation system, resulting in improved accuracy and efficiency.
              * **Performance Tuning**: Promoted services optimization with developers by monitoring services loading and scanning database slow query to improve overall system performance.
              * **Infra Configuration**: Configured infrastructures using Terraform for efficient and scalable deployment of resources in a cloud-based environment.
              * **Risk Session Detection**: Designed and implemented an anomaly detection mechanism for login session context using various user information such as IP address, user agent, and login time.
        - title: Site Reliability Engineer Intern
          company: Garmin
          company_url: "https://garmin.com"
          company_logo: garmin
          location: Taipei
          date_start: "2021-06-01"
          date_end: "2021-09-01"
          description: |2-
              * **kubernetes**: Install kubernetes cluster on bare metal servers using kubeadm.
              * **Load Testing**: Design a load testing service with Apache Jmeter. Integrate with services continuous integration
        - title: Software Testing Intern
          company: KKStream
          company_url: "https://www.kkstream.com/en"
          location: Taipei
          date_start: "2020-09-01"
          date_end: "2021-05-30"
          description: |2-
              * **CICD**: Deisgn CICD pipeline, including version tagging, service deploying and other stages for several projects.
    design:
      columns: "2"
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: linnom987321@gmail.com
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: "2"
---
