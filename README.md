# FitFlow Redesign

FitFlow is a fitness application redesign developed for the IT3060 Human Computer Interaction module.

The proposed system provides a cross-platform fitness experience for Android, iOS, and web users.

## Main Features

- AI-powered personalized workout planning
- Fitness progress tracking
- Nutrition tracking
- Community and social sharing
- Real-time updates
- Secure user authentication

## Selected Technology Stack

| Component | Technology |
|---|---|
| Frontend | Flutter |
| Backend | NestJS |
| AI Service | Python FastAPI |
| Database | PostgreSQL |
| Cache / Real-Time | Redis + WebSockets |
| Authentication | Firebase Authentication |
| Media Storage | Object Storage |

## Project Structure

fitflow-redesign/
- frontend/
- backend/
- ai-service/
- docs/

## Architecture

The system uses Flutter as the cross-platform frontend and NestJS as the main backend API.

PostgreSQL stores structured application data, while Redis supports caching and real-time functionality.

A separate FastAPI AI microservice handles personalized workout recommendations.

Firebase Authentication provides secure user authentication.

See the `docs` folder for the technology comparison, decision matrix, and high-level architecture.

## Module

IT3060 – Human Computer Interaction  
BSc (Hons) in Information Technology  
Year 3 – Semester 2
