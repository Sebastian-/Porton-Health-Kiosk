# Porton Health Kiosk

A full stack web application developed for Porton Health to provide medical clinics a quick and customizable method of checking in their patients. This repo is a combination of all assets created over the course of the project.

Links to each application's repo:

- [Admin client](https://github.com/carrotcorn/PortonHealthKioskAdminFrontend)
- [Kiosk client](https://github.com/carrotcorn/PortonHealthKioskPatientEnd)
- [Server](https://github.com/carrotcorn/PortonHealthKioskBackend)
- [Documentation](https://github.com/carrotcorn/PortonDocumentation)

## Features

- Admin

  - Superadmin
    - Enable/disable clinic accounts
  - Clinic Admin
    - Browse all appointments
    - View appointment check-in status
    - Customize check-in form
  - Role-based navigation

- Kiosk
  - Personalized greeting
  - Dynamic list of upcoming appointments
  - Dynamic check-in form

## Setup/Installation

### Server

```bash
cd server
docker-compose up --build
```

### Admin Client

```bash
cd client-admin
yarn start
```

### Kiosk Client

```bash
cd client-kiosk
yarn start
```

## Technologies/Frameworks

- Server
  - Egg JS (Koa based framework)
  - Docker
  - MongoDB
- Clients
  - React
  - react-router
  - react-hook-form
  - Material-UI
