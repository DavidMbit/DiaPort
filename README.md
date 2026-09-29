# Vesio
## Consumer Comparator

**Personal Project · Full-Stack Web Application**

A full-stack web application developed to save, organize and compare products and offers, with a particular focus on the second-hand market.

The project aims to simplify product research by allowing users to collect information from different offers in one place, compare alternatives and make more informed purchasing decisions.

The application is being developed under the name **Vesio**, with the long-term goal of evolving into an AI-assisted decision-support platform.

## Current Features

The current implementation includes the core functionalities required to manage products and user data.

* User registration and authentication
* Product categories and categorization
* Product creation, retrieval and deletion
* Product image upload and management
* Product organization and comparison
* Relational data model for different product categories
* REST APIs for frontend-backend communication
* Persistent data storage using MySQL
* Responsive frontend interface
* Dark mode support

## Technical Stack

### Backend

* Java 21
* Spring Boot 3.5.0
* Spring Data JPA
* Spring Security
* REST APIs
* Maven

### Database

* MySQL
* Relational database design
* Entity relationships and constraints
* Data validation and integrity
* Category-based data modeling

### Frontend

* React
* JavaScript
* HTML5
* CSS3
* Vite

### Deployment and Tools

* Docker
* Docker Compose
* Git and GitHub
* Render
* Cloudflare

## Architecture

The application follows a client-server architecture, with a React frontend communicating with a Spring Boot backend through REST APIs.

```text
React Frontend
      │
      ▼
   REST API
      │
      ▼
Spring Boot Backend
      │
      ▼
   MySQL Database
```

The backend handles application logic, authentication, data validation and database operations. The frontend provides the user interface and communicates with the backend through HTTP requests.

Docker and Docker Compose are used to support containerized development and deployment.

## Project Motivation

The project originated from a personal experience while looking for a new PC to purchase.

I was comparing different offers across multiple websites, but the information I needed was scattered between different listings. Comparing products required repeatedly switching between websites and manually collecting specifications, prices and other relevant details.

This led me to the idea of creating a platform where products and offers could be collected, organized and compared in a structured way.

As development progressed, the project evolved beyond its initial purpose. The long-term vision is to develop a decision-support platform that helps users evaluate products and purchasing opportunities based on their individual needs, preferences and available alternatives.

## Planned Evolution

Future development is focused on expanding the application beyond basic product management and comparison.

Planned features include:

* Personalized product evaluation based on user preferences
* Advanced comparison criteria and scoring
* Price history and market analysis
* Identification of potential risks in second-hand purchases
* AI-assisted product analysis and explanations
* Buy / Wait / Avoid recommendations
* Price and availability monitoring
* Notifications and alerts

These features represent the planned direction of the project and are not necessarily available in the current version.

## Current Status

**MVP · Active Development**

The application has progressed from its initial backend and database implementation to a full-stack web application with a React frontend, Spring Boot backend and MySQL database.

The project is deployed online, and development is ongoing. Features, architecture and infrastructure may evolve as new requirements are introduced.

## Live Demo

The application is available at:

**[vesio](https://vesioprogetto.scortaqwert.workers.dev/)**

Some features may still be under development, and availability may depend on the hosting infrastructure.

## Source Code

The source code is maintained in private repositories while development continues.

This repository documents the project's goals, technical architecture, implementation and future development plans.

A public release may be considered in the future.
