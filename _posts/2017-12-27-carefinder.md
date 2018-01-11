---
layout: post
title:  "Carefinder: Medical Providers at the Tip of your Finger"
subhead: "Web app I worked on (during grad school) for finding the nearest hospitals or urgent care centers."
date:   2017-12-27 07:00:00 -0500
categories: projects
---

While working on my Masters Degree in Biomedical and Health Informatics, I took a class on eHealth Systems. The course dealt with contemporary electronic systems that are used in the healthcare field. For the most part, web apps and services pervade the field (with database technology and social media services providing the backbone of these services). For my project, I ended up creating a web service that found the nearest medical centers for the user.

The whole aim of the app was to provide users a way of finding the nearest hospital or urgent care center without fussying around with Google Maps and search queries. The app actually talks to the Google Maps API via REST and returns a list of medical centers within a 15 mile radius. The front-end of the app was made with Bootstrap. User input was processed through Javascript and API queries were done with a PHP script through AJAX (via jQuery implementation). More work is to be done with refining the app and documentation. In addition, the API search queries could be revised to eliminate garbage results (non-medical centers caught up in the query for "hospital"). ~Lastly, the app only takes in queries for ZIP codes; it would be great to implement address-based queries.~ (see edit #1 below) In any case, I'm happy with how far I've come with version 1.0 and look forward to implementing more robust features with this app.

Code for the project can be found [here](https://github.com/DanTruong/Carefinder). Credit to [Start Boostrap's](https://startbootstrap.com) [Landing Page](https://startbootstrap.com/template-overviews/landing-page/) theme for the visual style of the web app.

edit #1: 1/11/18 The service now supports freeform address input. You can input an address, just city/state or a ZIP code. 
