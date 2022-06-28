---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Development Engineer
    company: Amazon
    company_url: ""
    company_logo: amazon-2
    location: Dublin
    date_start: "2021-05-31"
    date_end: ""
    description: |2-
        Responsibilities include:
        
        * Writing Python scripts to analyse logs to gain insight into traffic patterns to improve tools
        * Developing a Spring proxy to route internal Amazon customers writing to LDAP depending on the traffic and the resources available in the main hubs
        * Refactoring code to migrate the inhouse replication service from 1.0 to 2.0 in China region
        * Participating in on-call duty to monitor and fix production issues
        * Using IAAC to build out production and canary CI/CD environments for the write proxy where it had automated resource creation (AWS accounts, hostclasses, IAM roles, etc.) with staged rollouts, automated host patching, and CI checks. 
        * Implementing logging to set up CloudWatch, alarms, metrics, and dashboards for the write proxy to monitor latency, availability, etc.
        * Writing load tests of different write operations at various transactions per minute for the canary environment
        * Working with system engineers to scale out the LDAP service to new regions

  - title: SAP STAR Student
    company: SAP
    company_url: ""
    company_logo: sap-3
    location: Dublin
    date_start: "2019-05-31"
    date_end: "2021-04-30"
    description: SAP STAR intern where rotations were completed in Software Engineering for the SAP Analytics Cloud and Product Support for HANA and Fiori

design:
  columns: "2"
---
