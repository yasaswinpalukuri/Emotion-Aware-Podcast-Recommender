# Emotion-Aware Podcast Recommender

## Project Overview
An open-source web app that recommends podcast episodes tailored to your current emotion.  
Users provide text or voice input, the system detects their emotion using a Python microservice powered by HuggingFace models, and then recommends podcasts that match that mood.

## Tech Stack
- **Backend:** Java with Spring Boot  
- **Emotion Detection:** Python microservice using HuggingFace transformers  
- **Frontend:** Vue.js (or Thymeleaf templates)  
- **Database:** PostgreSQL for user and emotion mapping  
- **Deployment:** AWS Free Tier (EC2, RDS, S3)

## Features (Roadmap)
- User authentication and profile management  
- Text and voice input support  
- Real-time emotion detection from input  
- Personalized podcast recommendations based on emotion  
- Responsive frontend UI with voice input  
- Deployed on AWS with CI/CD pipeline (planned)

## Getting Started

### Prerequisites
- Java 17+  
- Python 3.8+  
- Node.js 14+ (if using Vue.js frontend)  
- PostgreSQL installed locally or AWS RDS access  

### Repository Structure
- `backend-springboot/` — Java Spring Boot backend service  
- `python-emotion-service/` — Python microservice for emotion detection and voice-to-text  
- `frontend-vue/` — Frontend UI code  
- `docs/` — Documentation files  
- `deployment-scripts/` — AWS deployment scripts and configs  

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

*Feel free to contribute! See [CONTRIBUTING.md](docs/CONTRIBUTING.md) (coming soon).*