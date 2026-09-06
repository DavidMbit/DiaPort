# DiaPort 
# Consumer Comparator 

**Personal Project · Work in Progress**

Web application developed to save, organize and compare products and offers, with a particular focus on the second-hand market.

The project was born from the need to collect information from different offers in a single platform, making it easier to compare products and evaluate the available alternatives.

## Current Features

The current version of the project focuses on the core infrastructure and product management.

* User management
* Product categories
* Product and offer management
* Product comparison
* Tracking of site visits
* Relational data model for different product categories
* REST APIs for the main application functionalities

## Technical Implementation

### Backend

* Java 21
* Spring Boot 3.5.0
* REST API

### Database

* MySQL
* Relational database design
* Entity relationships
* Constraints and data integrity
* Category-specific product data

### Frontend

* HTML
* CSS
* JavaScript

## Architecture

The application is structured around a Spring Boot backend exposing REST APIs and a relational MySQL database.

```text
Frontend
   │
   ▼
REST API
   │
   ▼
Spring Boot
   │
   ▼
MySQL
```

The architecture is being progressively developed with the goal of keeping the application modular and allowing additional functionality to be introduced over time.

## Project Motivation

The project originated from a personal experience while looking for a new PC to purchase.

I was comparing different offers across multiple websites, but the information I needed was scattered between different listings. To compare them effectively, I repeatedly had to switch between websites and copy and paste relevant information into a separate place just to keep the offers side by side.

This led me to the idea of creating a single platform where products and offers could be collected, organized and compared in a structured way.

The initial goal was therefore simple: make the comparison process easier and keep all the relevant information in one place.

As development progressed, the project evolved beyond this initial use case. The long-term goal is to turn the comparator into a more complete decision-support platform, helping users evaluate not only prices and specifications, but also how well a product or offer fits their individual needs.

## Planned Evolution

The long-term goal is to move beyond simple product comparison and provide more personalized decision support.

Planned areas of development include:

* Personalized product evaluation based on user preferences
* More advanced comparison and scoring
* Price history and market analysis
* Evaluation of alternative offers
* Identification of potential risks in second-hand purchases
* AI-assisted analysis and explanations
* Buy / Wait / Avoid recommendations
* Price and availability monitoring
* Notifications and alerts

These features represent the planned direction of the project and are **not yet implemented**.

## Current Status

**MVP / Early Development**

The core backend and database architecture are currently being developed, while the frontend and additional application features are being implemented progressively.

The project is actively evolving and its architecture may change as new requirements and use cases are identified.

## Source Code

The source code is currently private while the project is under development.

This repository is intended to document the project, its architecture, development progress and future direction.

A public demo may be made available in a future release.
