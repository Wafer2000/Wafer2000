# Container Operations Platform

## Overview

A web/PWA platform for container registration, operational evidence, assignment and approval workflows.

Internal workers can register container activity and supporting media, while organization-level users can review, approve, reject and sign operational records.

## Engineering focus

- **Frontend:** Next.js, React, TypeScript and Tailwind CSS.
- **Backend / data:** Supabase with PostgreSQL, Auth, Storage and Edge Functions.
- **Offline support:** Service Worker and IndexedDB-backed workflows.
- **Authorization:** multiple user roles and row-level security.
- **Reporting:** PDF and Excel generation.
- **Validation / testing:** Zod, Jest and targeted tests.

## Application roles

The system separates responsibilities across roles such as:

- Super administrators.
- Internal administrators.
- Workers.
- Organization users.

The authorization model is supported by application-level permissions and database policies.

## What this project demonstrates

This project is strong evidence of **enterprise-style Full-Stack engineering** because it combines:

- Role-based access.
- Database security.
- Offline-capable PWA behavior.
- File/media workflows.
- Reporting.
- Multi-organization operations.
- Testing and migration tooling.

> The complete source remains private because the application contains organization-specific operational logic.
