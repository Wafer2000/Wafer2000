# Multi-Provider Playlist Platform

## Overview

A web platform designed to connect user-authorized music accounts and manage playlists across multiple services.

The application supports playlist discovery, creation, transfer and splitting workflows while handling plan limits, account sessions and provider-specific behavior.

## Engineering focus

- **Web stack:** Next.js, React and TypeScript.
- **Backend / data:** Supabase Auth and PostgreSQL.
- **Deployment:** Vercel.
- **Integrations:** OAuth and provider APIs for supported music platforms.
- **Product rules:** Free / Basic / Pro capabilities, transfer limits and administrative workflows.
- **Internationalization:** multilingual interface support.

## Core engineering challenges

- Normalizing behavior across different provider APIs.
- Paginated playlist retrieval.
- Matching tracks across catalogs.
- Transfer workflows between providers.
- Split-playlist logic while preserving order.
- Session/device management.
- Backend enforcement of plan restrictions.
- Protecting provider tokens and sensitive server-side state.

## Security-oriented design

The system uses user-authorized OAuth flows instead of requesting provider passwords. Sensitive tokens remain backend-side, and mutable operations include validation and quota controls.

## What this project demonstrates

This project demonstrates **API integration and SaaS engineering** across:

- OAuth.
- External APIs.
- Data normalization.
- Business rules.
- Backend authorization.
- Multi-provider workflows.
- Subscription-style product limits.

> The complete application remains private because it contains product and commercial implementation details.
