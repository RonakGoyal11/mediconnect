# MediConnect — Healthcare Appointment Platform

MediConnect is a full-stack healthcare appointment platform designed to simplify doctor discovery, appointment scheduling, and appointment management through a modern web application.

The application provides separate workflows for patients, doctors, and administrators, with a focus on reusable UI components, responsive design, reliable appointment flows, and clean frontend architecture.

## Features

### Patient

- Patient registration and authentication
- Browse and search doctors
- View doctor profiles
- Explore doctor availability
- Schedule appointments
- View upcoming appointments
- View appointment history
- Cancel appointments
- Manage personal information

### Doctor

- Doctor authentication
- Doctor profile management
- Manage availability
- View upcoming appointments
- Manage appointment status
- View patient appointment information

### Admin

- Administrative dashboard
- Manage doctors
- Manage patients
- View and manage appointments
- Monitor appointment activity
- Manage appointment scheduling workflows

## Core Application Flow

```text
Patient
   │
   ├── Register / Login
   │
   ├── Discover Doctors
   │
   ├── Search / Filter
   │
   ├── View Doctor Profile
   │
   ├── Check Availability
   │
   ├── Select Date & Time
   │
   └── Book Appointment
              │
              ▼
       Appointment System
              │
       ┌──────┴──────┐
       ▼             ▼
   Patient        Doctor
   Dashboard      Dashboard
```

## Tech Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CS
