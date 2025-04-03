# Multi-Stage-CI-CD-Pipeline

## 📌 Project Description
This project demonstrates a **multi-stage CI/CD pipeline** using **GitHub Actions**. It automates the build, test, and deployment process for a simple Node.js application with Jest testing. The pipeline ensures efficient **continuous integration** and **continuous deployment** to GitHub Pages.

## 🚀 Features
- **Automated Build Process** using GitHub Actions
- **Jest Testing Integration** for Unit Testing
- **Multi-Stage Workflow** (Build → Test → Deploy)
- **Automatic Deployment** to GitHub Pages

## 🛠️ Technologies Used
- **Node.js** (v18)
- **Jest** (for testing)
- **GitHub Actions** (for CI/CD)
- **GitHub Pages** (for deployment)

## 📂 Project Structure
```
├── __tests__           # Test files
│   ├── index.test.js  # Jest test cases
├── .github/workflows  # GitHub Actions workflow files
│   ├── ci-cd.yml      # Multi-stage pipeline definition
├── src                # Source code
│   ├── index.js       # Main application logic
├── package.json       # Project dependencies & scripts
├── README.md          # Project documentation
```

## 🏗️ CI/CD Pipeline Stages
1. **Build Stage**
   - Checkout the repository
   - Install Node.js and dependencies
2. **Test Stage**
   - Run Jest test cases
3. **Deploy Stage**
   - Upload build artifacts
   - Deploy to GitHub Pages

## 🔧 Setup & Installation
### Prerequisites
- **Node.js v18+** installed
- **Git** installed

### Steps to Run Locally
1. Clone the repository:
   ```sh
   git clone <your-repository-link>
   cd multi-stage-ci-cd-pipeline
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run tests:
   ```sh
   npm test
   ```
4. Manually deploy (optional):
   ```sh
   npm run build
   ```

## 🚀 Deployment
This project is automatically deployed to **GitHub Pages** via GitHub Actions.

## 👨‍💻 Developer
- **Milan P Samuel**
