# FakLogistics - Project Documentation

## Overview
FakLogistics is a modern 3PL (Third-Party Logistics) website built with React and Vite. It showcases logistics services, pricing, and company information with a premium, responsive design.

## Technology Stack
- **Framework:** React + Vite
- **Language:** TypeScript
- **Styling:** Tailwind CSS + shadcn/ui
- **Routing:** React Router DOM
- **Icons:** Lucide React

## Features
- **Responsive Design:** Fully optimized for desktop, tablet, and mobile.
- **Pages:**
  - **Home:** Landing page with hero section, testimonials, and CTA.
  - **Services:** Detailed list of logistics services.
  - **About:** Company history, mission, and team.
  - **Pricing:** Transparent pricing tiers and delivery calculator.
  - **Contact:** Contact form and location information.
  - **Login/Signup:** Prototype authentication pages.

## Setup & Installation
1.  **Prerequisites:** Node.js installed.
2.  **Install Dependencies:**
    ```bash
    npm install
    ```
3.  **Run Development Server:**
    ```bash
    npm run dev
    ```
4.  **Build for Production:**
    ```bash
    npm run build
    ```

## Current Limitations (Prototype Status)
- **Authentication:** The Login and Signup pages are **simulations**. They accept any credentials and do not connect to a real backend. Data is not saved.
- **Forms:** The Contact form simulates submission and does not actually send emails.
- **Data Persistence:** All data (user sessions, form inputs) is temporary and resets on page refresh.

## Project Structure
- `/src/components`: Reusable UI components (Navbar, Footer, etc.).
- `/src/pages`: Individual page components (Home, About, Login, etc.).
- `/src/lib`: Utility functions.
