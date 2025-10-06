# ETL Dashboard — FlowForge

A modern ETL (Extract → Transform → Load) dashboard built with **Next.js**, **TypeScript**, and **PostgreSQL**, designed to refresh and deepen my full-stack development skills.  
This project focuses on secure user authentication, data validation, and database interactions while applying clean UI design generated with AI and **shadcn/ui**.

---

## Overview

**FlowForge** is a micro web app that allows users to:

- Upload raw data (CSV files)
- Validate and transform the data using schema-based rules
- Load the cleaned data into a PostgreSQL database
- Explore basic analytics or export results

The goal of this project is to reinforce end-to-end full-stack fundamentals — from data handling and validation to UI/UX and security.

---

## Tech Stack

### Frontend

- Next.js 15 (App Router, Server Actions)
- TypeScript
- shadcn/ui + Tailwind CSS
- Zod — type-safe validation and sanitation
- Recharts — simple data visualization

### Backend

- Prisma ORM
- PostgreSQL (optionally SQLite for local development)
- NextAuth.js (Auth.js) — authentication via credentials & OAuth
- Node.js / Next.js API routes

### Tooling and Quality

- ESLint + Prettier
- Vitest (unit testing)
- Playwright (end-to-end testing)
- Pino (structured logging)
- envsafe / zod-env — type-safe environment variables

---

## Key Features

| Feature                | Description                                      |
| ---------------------- | ------------------------------------------------ |
| File Upload            | Upload CSV files for ETL processing              |
| Data Validation        | Validate and sanitize data with Zod schemas      |
| Transformation         | Apply lightweight transformations before loading |
| Database Storage       | Persist processed data using Prisma & PostgreSQL |
| Dashboard View         | View summary analytics and charts                |
| Authentication         | Secure access with NextAuth.js                   |
| Configurable Pipelines | Extend transformations or add new ones easily    |

---

## Learning Goals

- Refresh and solidify TypeScript + Next.js full-stack development
- Understand ETL pipelines and data flow patterns
- Practice schema-driven validation and input sanitation
- Explore SQL fundamentals using PostgreSQL
- Build a secure, modern, minimal web app with proper architecture
- Experiment with AI-assisted frontend design (using shadcn-generated components)

---

## Project Structure
