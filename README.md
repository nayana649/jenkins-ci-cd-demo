# DevOps Task 2: Create a Simple Jenkins Pipeline for CI/CD

## 🚀 Objective
Set up a basic Jenkins pipeline using a `Jenkinsfile` to automate the process of building, testing, and deploying a Node.js web application[cite: 3].

## 🛠️ Tools Used
* **Jenkins:** Open-source automation server for CI/CD orchestration[cite: 3].
* **Docker:** For application containerization[cite: 3].
* **GitHub:** For version control and source code management.

## 📂 Project Structure
* `app.js` - Sample Node.js web application code.
* `package.json` - Node.js dependencies and scripts configuration.
* `Dockerfile` - Instructions to build the Docker container image for the app.
* `Jenkinsfile` - Declarative/scripted pipeline definition containing stages for Checkout, Install, Test, Build, and Deploy[cite: 3].

## ⚙️ Pipeline Stages
1. **Checkout:** Pulls the latest source code from the GitHub repository.
2. **Install Dependencies:** Installs required packages via `npm install`.
3. **Test:** Runs unit tests to ensure build stability.
4. **Build Docker Image:** Creates a container image of the application.
5. **Deploy:** Pushes the container image to Docker Hub.