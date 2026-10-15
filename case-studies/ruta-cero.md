# Ruta Cero — Financial Planning App

## Overview

Ruta Cero is a personal financial planning application focused on debt payoff, scenario simulation and decision support.

Rather than functioning only as an expense tracker, the application contains deterministic domain logic that recalculates plans as financial conditions change.

## Engineering focus

- **Framework:** Flutter.
- **State management:** Riverpod.
- **Navigation:** GoRouter.
- **Local data:** Drift / SQLite.
- **Backend:** Supabase with PostgreSQL, Auth and RLS.
- **Architecture:** lightweight Clean Architecture.
- **Offline-first:** local operation with backend synchronization.
- **Reporting:** PDF and CSV export.
- **Internationalization:** Spanish, English and Portuguese.

## Domain engineering

The application contains separate services for:

- Financial planning.
- Scenario simulation.
- Post-debt decisions.

It supports multiple debt-payment strategies and allows hypothetical scenarios to be evaluated without overwriting the user’s current plan.

## What this project demonstrates

Ruta Cero demonstrates advanced **Flutter / Mobile Engineering** with emphasis on:

- Domain modeling.
- Deterministic business logic.
- Offline-first design.
- Local and remote data coordination.
- State management.
- Multi-environment configuration.
- Reporting and internationalization.

> The source repository remains private while the product continues to evolve.
