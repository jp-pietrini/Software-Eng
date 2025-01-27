# TrustMe: Connecting Families with Trustworthy Construction Workers

## Project Overview

**TrustMe** is a digital marketplace designed to connect families with reliable construction workers and handymen. In the initial phases, the platform will focus exclusively on low-complexity, single-day jobs in three key municipalities of Mexico City. These areas were chosen due to their significant renovation market demand and higher willingness to pay for such services. As we gain experience and streamline operations, we plan to expand into more complex projects and serve areas with lower payment capacities. This project leverages Python and modern software engineering principles to develop a robust, user-friendly platform. It emphasizes version control, clean code practices, and thorough testing to address this real-world challenge effectively.

### Target Audience

- **Primary users**:
  - Middle-income families in Mexico City.
  - Female heads of families, young professionals, couples, and remote workers.
  - Elderly heads of households supported by tech-savvy family members.

### Core Problem

According to INFONAVIT, Mexico’s government housing department, and the IDB, 64% of Mexican families construct their homes without professional assistance from architects or engineers due to the high costs of hiring them. These professionals typically cater to large-scale projects, industrial buildings, or high-income clients, leaving middle-income families underserved. After conducting two years of field research and 140 interviews, we found that the biggest challenge for families is the lack of trustworthy information—a critical gap when dealing with what is often the largest financial investment of their lives.

Families require reliable and skilled professionals they can trust to help them build, repair, or renovate their homes. On the other hand, construction workers need a consistent and dependable source of income. Our research shows that experienced and reliable workers can often deliver results comparable to those of average engineers, but at significantly lower costs.

Families frequently struggle to find trustworthy construction workers, exposing them to risks of poor-quality work, scams, or delays. TrustMe solves this problem by offering a curated and transparent marketplace where vetted profiles, reviews, and consistent quality assurance build the trust that both families and workers need.

## Key Features

### User Profiles

- **Clients**:
  - Create a wishlist with photos and descriptions of future projects. Clients can choose to mark specific wishlist items as public, enabling workers to view and provide bids, while keeping the rest private for personal planning.
  - Maintain a gamified dashboard showing completed projects, connections, and reviews.
  - Store payment methods and manage public/private visibility of wishlist items.
  - Edit profiles and upload photos.
- **Workers**:
  - Upload verified profiles, portfolios, certifications, and client reviews.
  - Provide a video introduction and list job specialties.
  - Use a gamified dashboard to track completed jobs and certifications.

### Admin Dashboard

- Monitor job metrics, user activity, and platform analytics.
- Handle complaints, view high-demand jobs, and track worker performance.

### Core Functionalities

- **Search & Booking System**:
  - Search for workers by job type, location, and ratings.
  - Calendar integration for booking appointments, akin to Calendly.
- **Messaging System**:
  - Facilitate communication between clients, workers, and admins.
- **Chatbot**:
  - Integrated with Lama 3.3 API, or other open source model, which leverages natural language processing to provide instant and context-aware assistance, enhancing the chatbot's ability to respond to user inquiries effectively and accurately.
  - Trainable with platform policies, prices, and services.
- **Email Automation**:
  - Password reset, verification, booking confirmations, and downloadable PDFs.

### Services Offered

1. **Advisory Sessions**:
   - 20-minute video consultations to diagnose problems and provide pricing estimates.
   - Cost: \$5 USD.
2. **Turbo Service**:
   - Immediate booking of vetted workers with guaranteed pricing.
3. **Matching Service**:
   - Receive bids from handymen for wishlist items or specific requests.

## Project Guidelines Alignment

### System Design

- Modular architecture using Python frameworks like Flask/Django.
- Database design (PostgreSQL/SQLite) to manage structured data for user profiles, projects, and bookings.
- Integration of APIs for chatbot functionality and email automation.

### Version Control

- Use GitHub for repository management, including branching, merging, and pull requests.
- Maintain a project board to track tasks and progress.

### Clean Code Principles

- Use proper naming conventions, inline documentation, and modular design for maintainable code.

### Testing Strategies

- Implement unit tests for individual features using Pytest.
- Test user flows, including account creation, booking, and payments.
- Conduct integration tests to verify seamless interactions between components.

## Deliverables

1. A fully functional Python-based application hosted on GitHub, including documentation and test results.
2. A presentation slide deck showcasing the app’s functionality, challenges, and solutions.
3. A live demo of the app’s core features.

