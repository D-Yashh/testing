# GitEnhance

GitEnhance is a monorepo that combines **GitInsight**, **GitFlowchart**, **GitSummarizer**, **GitDependencyGraph**, and **GitSearchAI** to enhance GitHub repository analysis.

## Features
- **GitInsight**: AI-powered repo analysis.
- **GitFlowchart**: Function call visualization.
- **GitSummarizer**: AI-powered commit summaries.
- **GitDependencyGraph**: Package & dependency mapping.
- **GitSearchAI**: Smart search within repositories.

## Setup
```sh
# Install backend dependencies
cd backend
pip install -r requirements.txt

# Install frontend dependencies
cd frontend
npm install

# Start development environment
docker-compose up --build
```

## Deployment
- Uses **FastAPI for backend**.
- Uses **Next.js for frontend**.
- Supports **Docker & CI/CD workflows**.

