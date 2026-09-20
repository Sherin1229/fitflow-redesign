# FitFlow High-Level Architecture

## Overview

The FitFlow architecture consists of a Flutter frontend, NestJS backend, PostgreSQL database, Redis caching and real-time layer, Firebase Authentication, and a FastAPI AI microservice.

## Main Components

### Flutter Frontend
Provides the user interface for Android, iOS, and web.

### Firebase Authentication
Handles user login, registration, and authentication tokens.

### NestJS Backend
Provides the main REST API and application business logic.

### PostgreSQL
Stores users, profiles, workouts, nutrition records, progress information, and community data.

### Redis
Provides caching, rate limiting, and real-time event support.

### FastAPI AI Microservice
Handles AI-based personalized workout recommendations.

### Object Storage
Stores community images, progress photos, and other media.

## Main Data Flows

### Personalized Workout Plan

Flutter → NestJS → PostgreSQL → FastAPI → NestJS → Flutter

### Social Sharing

Flutter → NestJS → PostgreSQL / Object Storage → Redis / WebSocket → Flutter

### Nutrition Tracking

Flutter → NestJS → PostgreSQL → NestJS → Flutter
