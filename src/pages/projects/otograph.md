---
layout: ../../layouts/project.astro
title: Otograph Machine Learning Health Tool
client: The Otograph, LLC.
publishDate:
img: https://images.unsplash.com/photo-1547234935-80c7145ec969?fit=crop&w=1400&h=700&q=75
description: Web app for managing student outcomes at colleges and universities.
productLink: https://www.anthology.com/products/teaching-and-learning/assessment-management
tags:
    - design
    - machine learning
    - web app
skills:
    - Vue.js
    - WordPress
    - MySQL
    - Flask
    - PyTorch
    - Google Cloud Platform
    - Ubuntu
---

An interesting web application & project. I worked with a Washington, DC company to build a website and application to allow parents to upload photos of their child's inner ear and have its health assesed by a machine learning model created by another researched. The (very good) illustrations were contracted from a local artist.

The application was built primarily using Vue.js, WordPress, and PyTorch. I was responsible for the design and implemention of the landing site, which was built using WordPress with a custom template so the client could self-manage content and users, Vue.js for interactive graphics, and hosted on Google Cloud per the client's request.

I was initially asked to work on just the landing site. Several months later I was contracted to implement a service to have PyTorch model ingest and rate inner ear photos under the understanding that the client needed a proof-of-concept or prototype to present to investors. This second service was made using a GPU enabled-Google Cloud Compute Engine instance to host a Flask API that would accept images and return the results of the machine learning model. The model was trained using PyTorch by a researcher that the Otograph founder was working with, and was able to estimate the health of the inner ear as compared to other examples of inner conditions, such as otitis (i.e., an ear infection). Ironically my infant daughter had several ear infections during this project and found that the concept indeed did work.

Unfortunately in the year since, this application has been taken offline, but I'm still impressed with what I've learned from that project. I learned about machine learning, authorization and authentication, and managing multiple interconnceted services. I also found that I had things to learn in terms of managing scalability (that dragon). I hope to work with the Otograph again in the future if they start the project again.
