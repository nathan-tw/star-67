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
              * Email: Service for sending email. Involved in features such as queuing, asynchronous sending, rate limiting and yaml/lua template rendering. Built an internal app to handle sending activities.
              * IP Data ETL: Design ETL workflow for ip related data for building an ip reputation system. The extraction features flexible settings by jinja2 template engine. including email sending activities, redis connection count, threads count, database storage, etc.
              * Performance Tuning: Promote services optimization with developers by scanning database slow query, recording cache hit rate and monitoring services loading.
              * CICD: Development and execution of scripts to maintain the continuous integration and delivery of the systems. Coordination with application owners, development and supporting teams.
              * Infra Configuration: Configure infrastructures with Terraform. Design and develop config checking scripts in continuous integration process.
        - title: Site Reliability Engineer Intern
          company: Garmin
          company_url: "https://garmin.com"
          company_logo: garmin
          location: Taipei
          date_start: "2021-06-01"
          date_end: "2021-09-01"
          description: |2-
              * kubernetes: Install kubernetes cluster on bare metal servers using kubeadm.
              * Load Testing: Design a load testing service with Apache Jmeter. Integrate with services continuous integration
        - title: Software Testing Intern
          company: KKStream
          company_url: "https://www.kkstream.com/en"
          location: Taipei
          date_start: "2020-09-01"
          date_end: "2021-05-30"
          description: |2-
              * CICD: Deisgn CICD pipeline, including version tagging, service deploying and other stages for several projects.
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
