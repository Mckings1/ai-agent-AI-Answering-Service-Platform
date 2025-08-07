# AI Answering Service Platform (V1)

## Overview

This is a SaaS platform that provides an AI-powered voice answering service for local repair companies. The platform enables small businesses to offer 24/7 phone support using a natural-sounding AI agent that can answer questions, take messages, and book appointments. It’s built using modern, low-code and cloud-native tools including FlutterFlow, Supabase, Twilio, n8n, and Ultravox.ai.

---

## Features

### For Repair Company Clients:
- Self-service onboarding via web app
- Dedicated phone number for forwarding business calls
- AI call answering with business-specific knowledge
- Live appointment booking synced with Google Calendar
- Call summaries and message logs
- Email and SMS notifications after each call

### For Callers:
- Immediate call pickup with natural conversation
- Ability to ask questions and get answers
- Live appointment booking
- Option to leave detailed voice messages

### For Admin:
- Teable-based internal dashboard to manage clients
- Manual billing and payment status tracking
- View and filter call logs
- High-level system analytics (basic in V1)

---

## Tech Stack

| Layer             | Tool/Service        |
|------------------|---------------------|
| Frontend         | FlutterFlow         |
| Backend          | Supabase            |
| Auth             | Supabase Auth       |
| Database         | Supabase Postgres   |
| File Storage     | Supabase Storage    |
| Workflows        | n8n                 |
| Voice AI         | Ultravox.ai         |
| Telephony        | Twilio              |
| Calendar Sync    | Google Calendar API |
| Notifications    | Twilio (SMS), Email |
| Admin Dashboard  | Teable              |

---

## Directory Structure

