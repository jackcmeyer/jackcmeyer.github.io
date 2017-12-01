---
layout: project
title: "Smart Sync"
subtitle: "A dashboard for the more efficient, modern family."
category: "project"
author: "Jack Meyer"
github: "https://github.com/jackcmeyer/SmartSync"
github2: "https://github.com/KrashLeviathan/SmartSync-Dashboard"
---
<!-- Start Writing Below in Markdown -->
SmartSync is a home management system for synchronizing Internet of Things (IoT)
devices, family members’ online accounts, and other user applications. It runs
as a web application, interfacing with various services to provide a more
efficient home for the modern family. A “dashboard”-style user interface
lets the family see the status of their household at a glance. The goal of the
project was to provide a platform that allows user's to synchronize and manage
multiple IoT devices and services. SmartSync uses a dashboard style webpage
which allows the user to view that status of multiple devices/services
simultaneously.

Throughout the course of this project, we had to consider several different
aspects. We had to consider how to design an software architecture that was
capable of interfacing with many third-party services. Another design challenge
of this project was surrounding the microservice architecture. This was a
foreign concept to the team going into this project, but we quickly learned
how to manage and configure several services running in a distributed way. We
chose the microservice architecture because it gave us the flexibility to
interface with all of of the services we needed to and allowed us to deploy
new changes and features without worrying about breaking unrelated parts
of the project.

This project was built on Spring Boot, Angular 2, and the microservice
architecture. We designed an API which allows all of the components of the
project to communicate with one another.

* Click [here](https://docs.google.com/document/d/1sU9LBpo4IDBQUq_OfeFwLP2wDrL0KGEMhD3aoAdQbTk/pub) to view the architecture document

* Click [here](https://github.com/jackcmeyer/SmartSync) to view the server side code

* Click [here](https://github.com/KrashLeviathan/SmartSync-Dashboard) to view the client side code
