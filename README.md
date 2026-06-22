# MedXpreneur Booking SaaS

> Appointment and Scheduling Management System | Built with Claude Code | Deployed to GitHub

---

## Project Overview

MedXpreneur Booking SaaS is a comprehensive appointment and scheduling platform for healthcare providers. Features include online booking, calendar management, automated reminders, and patient scheduling workflows.

---

## Repository Structure

```
medxpreneur-booking-saas/
|-- src/
|   |-- api/
|   |   |-- v1/
|   |   |-- booking/
|   |   |-- calendar/
|   |   `-- providers/
|   |-- components/
|   |   |-- booking/
|   |   |   |-- calendar/
|   |   |   |-- time-slots/
|   |   |   |-- confirmation/
|   |   |   `-- cancellation/
|   |   |-- dashboard/
|   |   |-- patient-portal/
|   |   `-- common/
|   |-- pages/
|   |   |-- booking/
|   |   |-- dashboard/
|   |   |-- appointments/
|   |   |-- patients/
|   |   `-- settings/
|   |-- services/
|   |   |-- booking/
|   |   |-- calendar/
|   |   |-- notifications/
|   |   |-- payments/
|   |   `-- availability/
|   |-- models/
|   |   |-- appointment/
|   |   |-- provider/
|   |   |-- patient/
|   |   `-- schedule/
|   |-- integrations/
|   |   |-- google-calendar/
|   |   |-- zoom/
|   |   |-- stripe/
|   |   `-- twilio/
|   |-- hooks/
|   |-- utils/
|   |-- store/
|   `-- types/
|
|-- backend/
|   |-- controllers/
|   |-- routes/
|   |-- models/
|   |-- services/
|   |-- jobs/
|   `-- middleware/
|
|-- database/
|   |-- migrations/
|   |-- seeds/
|   `-- schemas/
|
|-- tests/
|   |-- unit/
|   |-- integration/
|   `-- e2e/
|
|-- docs/
|   |-- api/
|   |-- booking-flows/
|   `-- integrations/
|
|-- config/
|   |-- environments/
|   `-- integrations/
|
|-- scripts/
|   |-- build/
|   `-- deploy/
|
|-- public/
|   `-- booking-widget/
|
|-- .github/
|   `-- workflows/
|
|-- .env.example
|-- .gitignore
|-- package.json
|-- tsconfig.json
|-- docker-compose.yml
`-- README.md
```

---

## Key Features

- Online Booking Widget - Embeddable calendar for any website
- Multi-Provider Support - Manage multiple healthcare providers
- Automated Reminders - Email and SMS appointment reminders
- Calendar Sync - Google Calendar and Outlook integration
- Video Appointments - Zoom and Telehealth integration
- Payment Collection - Pre-payment and deposit support
- Waitlist Management - Automated waitlist system
- Analytics Dashboard - Booking insights and reports

---

## Getting Started

```bash
git clone https://github.com/medxpreneur-netizen/medxpreneur-booking-saas.git
cd medxpreneur-booking-saas
npm install
cp .env.example .env
npm run dev
```

---

## Related Repositories

- [medxpreneur-saas](https://github.com/medxpreneur-netizen/medxpreneur-saas) - Main SaaS Platform
- [medxpreneur-emr-saas](https://github.com/medxpreneur-netizen/medxpreneur-emr-saas) - EMR SaaS Platform
- [medxpreneur-plugins](https://github.com/medxpreneur-netizen/medxpreneur-plugins) - Plugins and Extensions
- [medxpreneur-mobile](https://github.com/medxpreneur-netizen/medxpreneur-mobile) - Mobile Application

---

MedXpreneur Team | Built with Claude Code on GitHub
