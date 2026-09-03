# NYVORA

## Health & Wellness Management Platform

Nyvora is a full-stack web application developed for patient management, biometric monitoring, clinical history tracking, and health-related data visualization through a centralized and responsive interface.

The project was developed as part of the **SC-502 Web Client/Server Environment** course at **Universidad Fidélitas** by a four-member team, integrating frontend, backend, database, and containerized development components into a functional web application.

---

## Project Overview

Nyvora provides healthcare-oriented functionality for managing patients and monitoring biometric information through multiple interconnected modules.

The final implementation integrates a frontend built with **HTML5, CSS3, and JavaScript**, a **PHP backend**, and a **MySQL database**, with **Docker** used for the development environment.

The project provided practical experience in full-stack integration, collaborative development, responsive interface design, database connectivity, and modular web application development.

---

## Key Features

- User authentication
- Patient management
- Dashboard with KPIs and dynamic information
- Data visualization with Chart.js
- Biometric metrics management
- Automatic BMI calculation
- Clinical history
- Patient progress tracking
- Preventive alerts
- Search and filtering
- Settings and user preferences
- Spanish / English login interface
- Backend integration with PHP
- Persistent data storage with MySQL
- Database-connected application workflows
- Responsive user interface

---

## Technology Stack

| Layer | Technologies |
| --- | --- |
| Frontend | HTML5, CSS3, JavaScript |
| Data Visualization | Chart.js |
| Backend | PHP |
| Database | MySQL |
| Development Environment | Docker |
| Version Control | Git, GitHub |

---

## Architecture

The application follows a client-server architecture:

```text
User
  │
  ▼
Frontend
HTML5 · CSS3 · JavaScript
  │
  ▼
Backend
PHP
  │
  ▼
Database
MySQL
```

The frontend handles the user interface and client-side interaction, while the PHP backend manages application logic and communication with the MySQL database.

---

## Core Modules

### Authentication

- User login
- Session management
- Role validation
- Database-connected authentication
- Spanish / English login interface

### Dashboard

- General KPIs
- Dynamic statistics
- Patient summaries
- Active alerts
- Chart.js visualizations
- Daily appointment information
- Patient weight evolution

### Patient Management

- Patient registration
- Patient editing
- Patient information
- Patient search
- Patient filtering
- Patient deactivation

### Biometric Metrics

Manual registration and monitoring of:

- Weight
- Body Mass Index (BMI)
- Body fat percentage
- Heart rate
- Sleep hours
- Daily steps

Additional functionality includes:

- Automatic BMI calculation
- Input validation
- Historical metric tracking
- Dynamic interface updates

### Clinical History

- Historical patient records
- Date filtering
- Patient progress
- Clinical observations
- Metric evolution

### Preventive Alerts

- Rule-based alerts
- Alert priorities
- Alert status
- Patient tracking
- Clinical history access

### Settings

- General configuration
- User preferences
- Platform options

---

## Repository Structure

```text
Nyvora
│
├── frontend/
│   ├── assets/
│   ├── css/
│   ├── js/
│   ├── pages/
│   └── index.html
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── services/
│
├── database/
│
├── docs/
│
├── README.md
│
└── docker-compose.yml
```

---

## Development Team

| Team Member | Role |
| --- | --- |
| Josué David Montero Hernández | Frontend Developer / Solution Architecture |
| Kevin Jiménez Sánchez | Frontend Developer |
| Derek Stuard Vega Barquero | Backend Developer |
| Sebastián Gondrez Acuña | Database Developer |

### My Contribution

My primary contribution to Nyvora focused on **Frontend Development and UX/UI**.

I developed and refined a significant portion of the application's user-facing interfaces, including multiple modules and responsive layouts, while maintaining visual consistency across the platform.

I also contributed to the integration between the frontend and the PHP/MySQL backend and participated in the overall application architecture and collaborative development workflow.

---

## Development Workflow

The project was developed collaboratively using **Git and GitHub**.

The team worked across frontend, backend, and database responsibilities while progressively integrating each layer into the final application.

The project provided hands-on experience with:

- Collaborative Git workflows
- Branch-based development
- Frontend/backend integration
- Database integration
- Modular development
- Debugging and validation
- Responsive web design
- Team-based software development

---

## Project Status

**Status: Completed**

The academic project reached its final implementation with the main frontend modules, PHP backend, MySQL database integration, and application workflows implemented.

The resulting system represents a functional full-stack academic application connecting the frontend, backend, and database layers.

---

## Future Evolution

Nyvora was designed with the possibility of future expansion beyond the original academic scope.

Potential future integrations include:

- Google Health Connect
- Wearable devices
- Advanced analytics
- Intelligent recommendations
- External APIs
- Automated data synchronization
- Cloud services
- Mobile companion applications

These capabilities are **not part of the current implementation** and are presented only as potential future extensions.

---

## Academic Context

Nyvora was developed as the final project for the **SC-502 Web Client/Server Environment** course at **Universidad Fidélitas**.

The project provided practical experience applying concepts related to frontend development, backend development, relational databases, client-server architecture, responsive design, version control, and collaborative software development.

---

## License

This project was developed for academic and educational purposes as part of the SC-502 course at Universidad Fidélitas.

Commercial use is not permitted without authorization from the project authors.
