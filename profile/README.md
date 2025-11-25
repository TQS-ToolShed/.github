# TQS-FinalProject-ToolShed
ToolShed is a digital marketplace that enables individuals and small businesses to rent and share tools and equipment easily and securely. The platform connects owners, who can monetize underused tools, with renters who need access to equipment for short-term projects, from power drills and saws to gardening tools and construction gear.


# Introduction

## Overview of the project

This project is developed within the scope of the TQS (Software Testing and Quality) course, where the main objective is to design, implement, and validate a software system while applying systematic Software Quality Assurance and DevOps practices. Throughout the assignment, the team must incorporate continuous integration, automated testing, code quality monitoring, and agile project management.

The product developed for this project is ToolShed, a digital platform that enables users to share and rent tools and equipment securely and efficiently.  
ToolShed connects tool owners, who can monetize underused items, with renters who need temporary access for personal or professional projects. The platform supports searching, booking, managing tool listings, and maintaining trust between participants through a reputation and review system. ToolShed is designed for individuals, hobbyists and small businesses seeking affordable, on-demand access to tools without the need to purchase them.

---

# References and resources

During the development of the ToolShed platform, several technologies, tools, and learning resources were essential to ensure a robust, maintainable, and well-tested solution.

## Core Technologies:

[**React**](https://react.dev/): Used for building the frontend interface. Its component-based structure and extensive documentation made it easier to create reusable UI elements.

[**Spring Boot**](https://spring.io/projects/spring-boot): The foundation of our backend services. Spring Boot’s opinionated, “convention over configuration” approach allowed rapid development of REST APIs.

[**PostgreSQL**](https://www.postgresql.org/): The relational database chosen for storing users, tools, bookings, and platform analytics.

---

## API Development & Documentation:

[**Swagger / OpenAPI**](https://swagger.io/): Used to document and validate our REST API endpoints. This tool made it easier to maintain API consistency, guide frontend–backend integration.

[**NGINX**](https://nginx.org/en/): Used as a reverse proxy and entry point for the platform’s backend API. NGINX allowed us to manage request routing, static asset serving, security headers, and load balancing.

---

## DevOps, Deployment, and CI/CD:

[**Docker**](https://docs.docker.com/): Essential for containerizing the backend, database, and supporting services. Docker ensured consistency between development and deployment environments.

[**GitHub Actions**](https://docs.github.com/en/actions): Used to implement Continuous Integration and Continuous Deployment (CI/CD), running automated tests and build workflows on every commit.

[**SonarQube**](https://www.sonarsource.com/products/sonarqube/): Applied for static code analysis, code smells detection, and monitoring overall code quality and coverage.

---

# Product concept and requirements

## Vision statement

ToolShed aims to solve the accessibility and affordability problem associated with owning specialized tools and equipment. Many individuals and small businesses need occasional access to tools but cannot justify the cost, storage, or maintenance of owning them. ToolShed provides a simple, reliable, and secure digital platform that enables users to rent, share, and manage tools within their community.

As a functional, black-box system, ToolShed enables renters to search for tools, view item details, book rentals, filter listings by location, and handle payments. Tool owners can create listings, update availability, manage booking requests, and track their inventory. The platform also supports core user management, authentication, platform analytics, and a reputation system with ratings and evaluations.

ToolShed is conceptually similar to other rental marketplaces (e.g., Fat Llama), but it differentiates itself through its emphasis on simplicity, a structured owner/renter workflow, and a more focused domain (tool sharing). The system is designed to be extendable to additional categories in the future without significant restructuring.

The requirements were gathered by analyzing typical rental use cases, mapping business needs to user stories, and prioritizing features that support the essential epics: item discovery, booking & scheduling, item management, platform admin operations, and basic user management. The backlog reflects these priorities, ensuring a clear path for delivering a minimal yet functional and testable MVP.

# Architecture
<img width="1600" height="1222" alt="image" src="https://github.com/user-attachments/assets/83a78b41-5ed9-41a1-abbe-93c665a5d446" />
