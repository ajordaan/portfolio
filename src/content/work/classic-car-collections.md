---
title: Classic Car Collections
publishDate: 2021-06-01 00:00:00
featured: true
featuredOrder: 2
img: /assets/classic_car_collections.png
img_alt: The homepage of Classic Car Collections, showing a menu bar and a large hero image of a green Porsche
description: |
  An auction platform that allows users to view and bid on collections of vehicles in real-time.
tags:
  - Vue
  - Firebase
  - Serverless
---

This is a website I built for a Classic Car Auction House that lets users view, buy and sell their cars. It features live auctions where users can bid on cars in real-time. 

Users can search for any car that is currently for sale and search by make model year or even color. Users can upload details and pictures of vehicles that they would like to sell. 

In addition to the consumer facing site, there is an admin portal that lets admins create auctions, manage users and view user uploaded vehicles

#### Technologies Used:

**Frontend:** The app was built as a single page application using Vue.js, which is hosted as a static site using Firebase hosting.

**Backend:** Firebase was used as the backend of the application. The use of Firebase allowed for the integration of real-time database updates, authentication, serverless functions and hosting.

#### Project Highlights:

**Search Functionality:** To enhance the platform's usability, Algolia was integrated to offer full-text search capabilities. This enables users to quickly find vehicles of interest through various filters and search terms. Whenever a vehicle is added or updated, a serverless function is triggered that will update the Algolia index, ensuring the search results are always up to date.

**Real-Time Interaction:** The platform's real-time capabilities transform the traditional online auction experience, making it dynamic and engaging.

**Staging environment:** A separate firebase project serves as a staging environment, where new features can be tested without impacting the main site. 

#### Conclusion:

I learned a lot about Firebase and microservices while building this project. I also got to integrate with other services like Algolia for the search functionality.
