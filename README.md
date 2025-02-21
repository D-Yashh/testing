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



## 🚀 Hosting on GitHub Pages

This project is configured to be deployed on **GitHub Pages** using GitHub Actions.

### **🔧 Steps to Deploy**

1️⃣ **Enable GitHub Pages**  
- Go to **Settings → Pages** in your repository.  
- Set the **Source** to `gh-pages` branch.

2️⃣ **Trigger Deployment**  
- Push any changes to the `main` branch to trigger GitHub Actions.

3️⃣ **Check Deployment Status**  
- Navigate to **Actions** → **Deploy to GitHub Pages** workflow to see the status.

4️⃣ **View Live Site**  
- The hosted site will be available at:  
  ```
  https://<your-github-username>.github.io/<your-repo-name>/
  ```

