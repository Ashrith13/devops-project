## Task 1: CI/CD Setup
✅ What We Did
We implemented a basic CI/CD pipeline to automate the build and testing process for the project. The pipeline configuration is stored in the ci-pipeline.yaml file and is triggered on each push to the dev branch.

Key steps included:

Creating a CI/CD configuration file (e.g., GitHub Actions, Jenkinsfile, etc.)

Adding steps to install dependencies and run tests

Configuring the trigger conditions for the pipeline (on push/pull request to dev)

💡 Why We Did It
Continuous Integration (CI) and Continuous Deployment (CD) are essential practices in DevOps to ensure:

Code quality through automated tests

Faster and safer deployments

Reduced manual intervention and human errors

Better team collaboration by catching issues early

Setting up a pipeline early helps enforce a standardized deployment and testing process.

🧪 How to Test / Use It
For GitHub Actions (example):
Ensure the CI config is saved in .github/workflows/ci-pipeline.yaml.

Make a commit to the dev branch or create a PR.

Go to your GitHub repository → Actions tab.

Observe the running or completed workflow.

For Jenkins:
Make sure Jenkinsfile is at the root of the repository.

Commit and push changes.

Jenkins will automatically trigger a build if it's connected to the repository.