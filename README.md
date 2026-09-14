# FitFlow Redesign

Redesign of the FitFlow fitness-tracking application, produced for IT3060 – Human Computer Interaction (SLIIT).

## Project summary
FitFlow lost users and store rating over the past year. This project follows a full human-centred design process — user research, analysis, prototyping, usability testing, technology selection, and architecture design — to rebuild the application around AI-personalized workouts, fast camera-based nutrition logging, and private, positive social support.

## Repository structure
- `frontend/` – React Native + React Native Web client
- `backend/` – Node.js/NestJS microservices (workout, nutrition, social, notification)
- `ai-service/` – Python/FastAPI AI microservice and computer vision service
- `docs/` – tech stack summary, comparison matrix, and architecture diagram

## Technology stack
- Frontend: React Native, React Native Web
- Backend: Node.js / NestJS, Python / FastAPI (AI microservice only)
- Databases: PostgreSQL (system of record), Firebase Firestore (real-time/social)
- Auth: Firebase Auth
- AI/CV: TensorFlow Lite, ML Kit

See `docs/tech-stack-summary.md` and `docs/comparison-matrix.xlsx` for the full justification, and `docs/architecture-diagram.png` for the system architecture.

## Related lab reports
- Lab 01 – User Research
- Lab 02 – Research Analysis and Requirements
- Lab 03 – Interface Design and Prototyping
- Lab 04 – Usability Testing Plan and Evaluation
- Lab 05 – Technology Selection and Architecture Design (this repository)

## Author
IT23829992 – Jayathunga I.T.N. – Group 2.1 WD
