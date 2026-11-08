# P2 Requirements Index

## Project Documentation

**Official Submission:** [P2.docx](P2.docx) - Primary submission format

**Development Version:** [P2.md](P2.md) - Staged markdown requirements

**Additional Notes:**
- [clyan-notes.md](clyan-notes.md)
- [dara-notes.md](dara-notes.md)
- [makan-notes.md](makan-notes.md)

## Project Overview

Rebaz is a collaborative travel planning and itinerary organizer web app.

**Core Objectives:**
- O1: Complete 5-day itinerary assembly (transport + lodging)
- O2: Real-time member visibility and updates
- O3: 100% time overlap detection
- O4: Offline export in ≤3 actions
- O5: Expense tracking with balance calculation

**Scope:**
- **In Scope:** Account management, trip creation, member invitations, itinerary management, conflict detection, expense tracking, export functionality
- **Out of Scope:** Real bookings/payments, flight tracking, insurance, native mobile apps

**Acceptance Criteria:**
- US-01: Destination search (city name, country, image)
- US-02: Trip creation with validation
- US-03: Member invitations via email
- US-04: Real-time change visibility

**Non-functional Requirements:**
- NFR-01: Itinerary load <2s (95% requests, 100 concurrent users)
- NFR-02: 90% first-time users create trip + 3 items in 5min
- NFR-03: Access control, password hashing, HTTPS
