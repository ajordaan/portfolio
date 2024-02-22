---
title: Quickvoice
publishDate: 2022-10-01 00:00:00
featured: true
featuredOrder: 1
img: /assets/quickvoice.png
img_alt: The student detail page of Quickvoice
description: |
  A custom CRM application that handles everything a small business needs to manage their users effectively
tags:
  - Rails
  - Postgres
  - SaaS
---

This project holds a special place in my heart. It was the first proper application I ever built, and it started out as a Java desktop app way back in 2014 to help my mom manage her Drama Academy students. Since then both the project and I have grown and changed a lot! 

The project now runs on rails, and has many more features. It has standard CRUD actions to allow principals to manage student and parent information; there are attendance registers that are filled out weekly by teachers to keep track of absentees. It also integrates with other services like Mailchimp for email campaigns and Xero for invoicing and tracking parent accounts.

Parents are able to sign up their children online, and existing parents are able to re-enrol students who currently attend lessons and would like to continue the following year. 

#### Technologies Used:

**Frontend:** Sass was used as a CSS preprocessor. Stimulus.js and hotwire were used to handle client side interaction.

**Backend:** Ruby on Rails is the backend framework, along with PostgreSQL for the database, and Redis for caching. Sidekiq is used to handle background jobs and the project is deployed on Fly.io

#### Project Highlights:

**Attendance Tracking:** Accurately track student attendance, transfers between studios, when they leave and when they rejoin

**Online Sign ups:** Parents can easily enrol new students and re-enrol existing students.

**Teacher Portal:** Teachers have their own custom dashboard and can access class lists, absentee tracking and lesson notes.

#### Conclusion:

I have learned a great deal from this project, aside from the technical skills I developed while building features, I also learned about gathering requirements, evaluating the scope of features, managing my time between work and side projects.

I am quite proud of this project, and am excited to keep building and adding features.
