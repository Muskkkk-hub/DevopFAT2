Five DevOps Concepts

1. Continuous Integration (CI) 🔄

Frequently testing and merging new code into the main branch to avoid conflicts.
CI tools such as GitHub Actions, Jenkins, and GitLab CI automatically test and integrate code.

2. Continuous Deployment (CD) 🚀

Automatically deploying code to production after it passes testing.
This helps in fast, reliable, and error-free software delivery.

3. Version Control (Git) 📘

Git tracks all code changes, supports teamwork, and maintains project history.
Developers can work on different features without affecting each other.

4. Containerization (Docker) 📦

Docker packages applications and all dependencies into containers so they work the same on any system—Windows, Linux, Mac, cloud, or server.

5. Automation ⚙️

Automation removes repetitive manual tasks.
It is used in building, testing, deployment, monitoring, and configuration management.


⭐ How I Completed This Assignment (Extended Explanation)

By: Muskan Singh Rathor

🐳 Docker Commands Used

docker build -t devops-assignment .
docker tag devops-assignment muskanrathor/devops-assignment:v1
docker push muskanrathor/devops-assignment:v1

📌 Explanation

docker build → Creates a Docker image using the Dockerfile

docker tag → Adds a version tag (v1) to the image

docker push → Uploads the image to Docker Hub


These commands helped me learn how to build, version, and publish container images just like real DevOps engineers do.

📝 Git Commands Used

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/MuskanRathor/devops-demo-app
git push -u origin main

📌 Explanation

git init → Creates a new Git repository

git add . → Stages all files

git commit → Saves changes with a message

git remote add origin → Connects my local project to GitHub

git push → Uploads files to GitHub


These steps taught me the fundamentals of version control, which is crucial for any DevOps workflow.

⭐ What I Learned?

✔ Docker Skills

How to build, tag, and push Docker images

How containers run Linux commands

How image versioning works (v1, v2…)


✔ Linux Skills

Understood basic Linux command behavior inside a container


✔ Git & GitHub

How developers manage changes using commits

How pushing to GitHub helps in team collaboration


✔ Real DevOps Workflow

I learned the full DevOps mini-pipeline:

Build → Tag → Push → Pull → Run

✔ Cloud & Automation Concepts

How Docker Hub acts as a cloud registry

How automation reduces manual errors and speeds up deployment

⭐ Repository & Docker Image (Example for Muskan)

📁 GitHub Repository (Public)

👉 https://github.com/MuskanRathor/devops-demo-app

🐳 Docker Hub Image (Public)

👉 https://hub.docker.com/r/muskanrathor/devops-assignment
