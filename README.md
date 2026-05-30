# MealPilot

MealPilot is an AI-powered Family Wellness and Preventive Health Copilot.

## North Star

Reduce decision fatigue around food and healthy habits through AI.

## Product Mission

Help families make healthier decisions with less effort.

## MVP Scope

- Family as tenant
- Chat + UI experience
- Weekly meal planning
- Context-aware meal recommendations
- Weight tracking
- Activity tracking
- Smart shopping lists
- Favorites and preferences
- Calendar reminders
- CRUD + Event Store
- Recommendation Engine + LLM explanation layer

## Architecture

- Domain First
- Modular Monolith
- REST + OpenAPI
- Supabase PostgreSQL
- Expo React Native mobile app
- NestJS backend API
- Google Login
- Google Calendar / Drive integrations
- OpenAI or compatible LLM provider

## Repository Structure

```text
apps/
  api/        # NestJS backend
  mobile/     # Expo React Native app
packages/
  shared/     # Shared contracts and types
specs/
  product/
  discovery/
  domain/
  architecture/
  events/
  adrs/
  api/
  backlog/
docs/
  c4/
  diagrams/
```

## Current Status

Discovery completed. Sprint 0 foundation in progress.
