AI Systems Portfolio

«Building AI-assisted systems that combine software engineering, conversational AI, backend architecture and human-centered experiences.»

Welcome to my technical portfolio.

I design and develop software systems using AI as an engineering copilot throughout the development process. I define the problems, system behavior, architecture and technical requirements, while using AI tools to accelerate implementation, debugging, testing and iteration.

My background in mechanical engineering and industrial maintenance has strongly influenced the way I approach software: understand the system, identify how its components interact, diagnose failures and build solutions around the complete process.

---
# Project 01 — AI Core Platform

## Overview

This project is the core platform of a broader AI-assisted digital ecosystem.

Its purpose is to combine user management, intelligent interactions, real-time services and human support into a single modular platform.

The system is currently under active development, so the source code remains private. This public case study focuses on architecture, engineering decisions and technical learning.

---

## Problem

The main challenge was not simply building a chatbot.

The goal was to design a system capable of coordinating several components:

- User authentication
- User profiles
- AI-assisted conversations
- Human interaction flows
- Data persistence
- Real-time communication
- Security
- External integrations
- Future payment and subscription services

This required thinking about the platform as a complete system rather than as isolated features.

---

## Architecture

The backend follows a modular architecture.

Main flow:

**Client → API → Backend Services → Database / Cache / AI Services → Response**

The architecture is designed so that different modules can evolve independently while remaining connected through a common backend.

---

## System Architecture Diagram

![AI Core Platform System Architecture](../diagrams/core-architecture.png)

This diagram provides a high-level view of the platform architecture, showing how the client layer, backend services, AI processing, data infrastructure and external integrations work together.

---

## Main Technologies

### Backend

- NestJS
- TypeScript
- REST APIs

### Database

- PostgreSQL
- Prisma ORM

### Authentication

- JWT
- Google OAuth

### Performance & Session Support

- Redis

### Artificial Intelligence

- LLM integration
- Prompt engineering
- Context management
- AI-assisted decision flows

---

## Main Modules

The platform is being designed around several core modules:

### Authentication

Handles registration, login, token management and identity validation.

### Users

Stores user profiles, preferences and application-related information.

### AI Layer

Processes conversational requests and prepares contextual information for the language model.

### Human Support Layer

Designed to connect users with human professionals when AI interaction is not sufficient or when human intervention is required.

### Data Layer

Uses PostgreSQL as the primary database and Prisma as the interface between application logic and persistent data.

### Cache / Fast Data Layer

Redis is used for information that benefits from faster access or temporary storage.

---

## AI Architecture

One of the key areas of the project is understanding how an LLM fits into a larger software system.

The AI is not treated as the entire application.

Instead, it is one component inside a broader pipeline:

**User Input → Context Builder → Rules / Application Logic → LLM → Evaluation → Response**

This approach helps separate deterministic application logic from probabilistic AI-generated responses.

---

## AI-Assisted Engineering Workflow

I developed the project using AI tools as engineering copilots.

AI supported tasks such as:

- Exploring implementation alternatives
- Generating code drafts
- Debugging
- Reviewing errors
- Explaining unfamiliar technologies
- Refactoring
- Testing ideas
- Comparing architectural approaches

However, the system requirements, architecture direction, validation and final technical decisions remained under my responsibility.

---

## Engineering Lessons

### 1. An LLM is not the whole system

One of the most important lessons was understanding that an AI application requires much more than sending prompts to a language model.

APIs, authentication, databases, context, memory, validation and application logic are equally important.

### 2. Context quality matters

AI responses depend heavily on what information reaches the model.

This led me to study concepts such as:

- Context builders
- Memory
- RAG
- APIs
- Retrieval
- Evaluation

### 3. AI output must be validated

A language model can generate plausible answers that are not necessarily correct.

For that reason, AI output should be evaluated before it becomes a system decision.

### 4. Architecture matters more as the project grows

At the beginning, features can be built independently.

As the system grows, modularity becomes essential to avoid tightly coupled components and difficult maintenance.

---

## Current Development Areas

The platform continues evolving in areas such as:

- AI context management
- Conversational memory
- Human escalation flows
- Security
- Real-time communication
- Service integrations
- Observability
- Testing
- Deployment architecture

---

## Repository Status

🔒 Source code: Private  
🚧 Development status: Active  
📄 Public documentation: In progress
