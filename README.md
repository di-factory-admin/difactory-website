# Data Intelligence Factory Website

> Official website for Data Intelligence Factory (∂i~ƒ) - Crafting AI Models for your Business Needs

## Overview

This repository contains the code for the Data Intelligence Factory website, featuring a modern design with gradient elements and a clean, professional look.

## Technology Stack

- Django 5.0.x
- PostgreSQL
- Bootstrap 5
- Django REST Framework
- WhiteNoise for static files

## Features

- Modern gradient-rich design
- Responsive layout
- Information about our three service lines:
  - ML models tailored to business needs
  - MVP development for digital business ideas
  - Business consulting for digital ventures
- Industry-specific information
- Resources section with blog, case studies, and whitepapers
- Client portal

## Getting Started

### Prerequisites

- Python 3.11+
- PostgreSQL
- Virtual environment

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/di-factory-admin/difactory-website.git
   cd difactory-website
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Create a .env file with the necessary environment variables
   ```
   DEBUG=True
   SECRET_KEY=your-secret-key
   DATABASE_URL=postgres://user:password@localhost:5432/difactory
   ```

5. Run migrations
   ```bash
   python manage.py migrate
   ```

6. Start the development server
   ```bash
   python manage.py runserver
   ```

## Project Structure

The website follows a modular structure with Django apps for each main section:

- core: Homepage and shared functionality
- about: About Us section and subpages
- services: Three service lines and their subpages
- industries: Industry-specific content
- resources: Blog, case studies, whitepapers, and FAQs
- contact: Contact forms and lead generation
- accounts: User management and client portal
- design: Design system components and utilities

## Design System

The website uses a gradient-rich modern design with:

- Primary Blue (#2a4b8c)
- Accent Teal (#2a9d8f)
- White (#ffffff)
- Light Gray (#f8f9fa)

Gradient elements include buttons, cards with accent edges, section dividers, and flowing data visualization elements.
