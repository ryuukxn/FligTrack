# FligTrack

**A Web-Based Integrated Platform for Timesheet Tracking and Invoice Management System with AI Chatbot Assistance**

FligTrack brings timesheet tracking, invoice management, and an AI chatbot into one system, so the virtual assistants (VAs) of Fligno Software Philippines Inc. spend less effort on manual time logging and invoice preparation.

This project is part of a research study for the subject **IT Research Methods** (October 2026).

## Features

- **Timesheet tracking:** log time-in and time-out entries with automatic computation of total work hours
- **Invoice management:** generate editable invoices from recorded hours and client rates
- **Reports:** weekly, monthly, and annual timesheet and invoice reports
- **Client management:** store client information, service rates, and invoice terms
- **Centralized dashboard:** one place to view timesheets, invoices, and clients
- **AI chatbot:** answers questions about timesheets, invoices, clients, and how to use the system

> Features are being built in stages. See [Project Status](#project-status).

## Tech Stack

| Area | Technology |
| --- | --- |
| Framework | Django (Python) |
| Frontend | JavaScript |
| Database | MySQL |
| AI chatbot | Gemini API |
| Email | Twilio SendGrid |
| File storage | Cloudinary |
| Editor | Visual Studio Code |

### Prerequisites

- Python 3.x (added to PATH)
- MySQL (for example, through Laragon)

## Evaluation

The system will go through functional testing, including a comparison of computed hours and invoice amounts against manual calculations. Usability and functionality will then be evaluated by more than 100 virtual assistants and one management representative using a 5-question survey, along with a comparison of invoice preparation time against the current process.

## Limitations

- Accuracy of computations depends on the completeness and correctness of the data entered.
- The chatbot is limited to questions about FligTrack and does not replace human management support. Its performance depends on the Gemini API and internet connectivity.
- Some functions depend on third-party services (Gemini, Twilio SendGrid, Cloudinary) and on the hosting environment.
