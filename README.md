# Complete DevOps CI/CD Pipeline

A Flask application deployed using an automated CI/CD pipeline with Docker, GitHub Actions, Docker Hub, and AWS EC2.

## CI/CD Flow

GitHub → GitHub Actions → pytest → Docker Build → Docker Hub → AWS EC2 → Deployment

## Technologies

- Python / Flask
- Docker
- GitHub Actions
- Docker Hub
- AWS EC2
- pytest
- Gunicorn
- Linux

## What I Built

- Containerized the Flask application using Docker
- Added automated testing with pytest
- Built a GitHub Actions CI/CD pipeline
- Published Docker images to Docker Hub using Git commit SHA tags
- Automated deployment to AWS EC2 using SSH
- Configured the container to run as a non-root user

## Run Locally

```bash
git clone https://github.com/Yasirshafi1/complete-devops-pipeline.git
cd complete-devops-pipeline
pip install -r requirements.txt
pytest
python app.py
