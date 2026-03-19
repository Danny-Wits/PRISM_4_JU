# PRISM (Public Reporting & Issue Status Monitoring)

A modern, serverless web application designed for fast, real-time public reporting and issue status tracking. 

**Live Demo:** [prism4ju.in](https://prism4ju.in)

## Tech Stack

### Frontend
* **Core:** React, Vite
* **UI Framework:** Mantine UI (Mobile-first, responsive design)
* **State Management & Data Fetching:** TanStack Query (Resilient data synchronization, caching, optimistic updates)
* **Mapping:** Leaflet & Browser Geolocation API

### Backend & Infrastructure
* **BaaS:** Supabase (PostgreSQL, Authentication, Storage)
* **AI Integration:** Hugging Face Inference API (Image-to-text auto-captioning)
* **Deployment & CI/CD:** Vercel, GitHub Actions

## Implementation Highlights

* **Serverless Architecture:** Operates as a web-only MVP leveraging Supabase as a Backend-as-a-Service (BaaS). This eliminates the need for a traditional backend server while maintaining robust database, authentication, and storage operations.
* **Real-time Data Synchronization:** Utilizes TanStack Query in tandem with Supabase to handle complex state, providing optimistic UI updates and efficient client-side caching.
* **Automated AI Captioning:** Integrates the Hugging Face Inference API to automatically generate text descriptions from uploaded images of public issues, reducing user friction during the reporting process.
* **Geospatial Tracking:** Directly interfaces with the native Browser Geolocation API, mapped over Leaflet, to accurately pinpoint and display reported issues on a centralized, interactive map.
* 
