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
        * Writing Python scripts to analyse logs to gain insight into traffic patterns to improve tools
        * Developing a Spring proxy to route internal Amazon customers writing to LDAP depending on the traffic and the resources available in the main hubs
        * Refactoring code to migrate the inhouse replication service from 1.0 to 2.0 in China region
        * Participating in on-call duty to monitor and fix production issues
        * Using IAAC to build out production and canary CI/CD environments for the write proxy where it had automated resource creation (AWS accounts, hostclasses, IAM roles, etc.) with staged rollouts, automated host patching, and CI checks. 
        * Implementing logging to set up CloudWatch, alarms, metrics, and dashboards for the write proxy to monitor latency, availability, etc.
        * Writing load tests of different write operations at various transactions per minute for the canary environment
        * Working with system engineers to scale out the LDAP service to new regions
        * Refactoring the internal credential management system to use the new standard credential management system
  - title: SAP STAR Student
    company: SAP
    company_url: ""
    company_logo: sap-3
    location: Dublin
    date_start: "2019-05-31"
    date_end: "2021-04-30"
    description: |2-
      STAR stands for Student Training And Rotational. This is a special two year SAP Internship program for high performing students. I was selected for this program based on my excellent college results.
      
      I received the unique opportunity to combine academic studies with real industry experience. It allowed me to experience different business areas in SAP, take part in highly valuable soft skills training, and work with a wide range of technologies and tools. It provided me with a wide range of technical and professional training. I also received certifications in SAP technologies.
      
      I worked as a Product Support Engineer for SAP HANA and SAP Fiori and also worked as a Software Engineer on the SAP Analytics Cloud on the Smart Insights Service team.
  - title: Software Engineer
    company: SAP
    company_url: ""
    company_logo: sap-3
    location: Dublin
    date_start: "2020-03-01"
    date_end: "2020-09-01"
    description: |2-
        * Backend Engineer for Smart Insights Service, working on SAP Analytics Cloud
        * Focused on web development using React, Java Spring, Maven, Tomcat, Jenkins, PostgresSQL, and MySQL
        * Worked in an Agile team 
        * Wrote unit and integration tests using Junit and Mockito
        * Used Docker to dockerized API tests to provide portability and eliminated the need for a V.M to run API tests
        * Used Jenkins to build CI/CD pipelines 
        * Wrote Robot tests (Selenium) to test services running on CloudFoundry and Neo cloud platforms
        * Created various data models for both frontend and backend testing
        * Used Spring and React to create a REST full-stack dashboard that displays API response times from tests which allowed the easy identification of regressions due to code changes
        * Utilised Swagger to describe RESTful APIs
        * Created a React application that generates an Amazon AWS Cloud Practitioner exam from a massive pool of questions
        * Investigated features released to customers to ensure it was working as intended and recorded results
        * Investigated test failures and documented findings
        * Updating production systems with the latest WAR
        * Learned the various microservices in SAP Analytics Cloud
        * Participated in Java architecture design, test fiestas, feature discussions and code reviews"
  - title: Fiori Product Support Engineer
    company: SAP
    company_url: ""
    company_logo: sap-3
    location: Dublin
    date_start: "2019-07-01"
    date_end: "2019-09-01"
    description: |2-
        * Global Product Support for Fiori
        * Work involved solving customers' Fiori issues relating to HTML, CSS, JavaScript, and SAPUI5 Library.
        *	Resolved system and customer issues by troubleshooting and providing effective solutions by taking up to 5 incidents per day.
        *	Tested product components to identify root causes of issues.
        *	Escalated complex problems such as failure of interdependent nodes in large production environments to management for resolution.
        *	Managed customer relationships by delivering prompt responses to questions.
        *	Provided technical troubleshooting and problem solving for clients with installed equipment/system issues.
  - title: HANA Product Support Engineer
    company: SAP
    company_url: ""
    company_logo: sap-3
    location: Dublin
    date_start: "2019-05-01"
    date_end: "2019-08-01"
    description: |2-
        * EMEA Product Support for HANA
        * Work involved reading through logs, writing and analyzing SQL query performance, investigating system performance such as memory, CPU, and nodes
        *	Resolved system and customer issues by troubleshooting and providing effective solutions by taking up to 5 incidents per day.
        *	Tested product components to identify root causes of issues.
        *	Escalated complex problems such as failure of interdependent nodes in large production environments to management for resolution.
        *	Managed customer relationships by delivering prompt responses to questions.
        *	Provided technical troubleshooting and problem solving for clients with installed equipment/system issues.
design:
  columns: "2"
---
