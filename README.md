# PackSense - AI-Based Intelligent Food Packaging Material Recommendation System

https://sahipack-app.web.app

PackSense is an AI-powered decision-support system designed for SIH26236. It recommends optimal food packaging materials and specifications based on food commodity properties, storage environments, shelf-life requirements, and sustainability considerations.

> **Note**: PackSense is a decision-support prototype intended for evaluation and research purposes, NOT a certified engineering or laboratory validation system.

## Project Structure

```
PackSense/
├── frontend/             # HTML/CSS/JS User Interface
├── backend/              # Flask Backend API & Business Services
│   ├── routes/           # REST API Route Blueprints
│   ├── services/         # Decoupled Domain Services (Food, Materials, MAP, Shelf-Life, etc.)
│   ├── models/           # Data Access Layer & Models
│   ├── utils/            # Helper utilities and validators
│   ├── config.py         # Application configuration
│   └── app.py            # Flask Application Factory
├── database/             # Relational Database Schemas and Seed Scripts
├── ml/                   # ML-Ready Recommendation & Explainability Engine Architecture
│   ├── recommendation/   # Modular recommendation strategy/engine
│   └── explainability/   # Decision factor explainer
├── tests/                # Unit, Integration, and Architecture Validation Tests
└── docs/                 # System Architecture & Documentation
```

## Setup & Running

Instructions for setup will be updated as backend and frontend services are integrated across stages.
