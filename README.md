# Dotnet Core CodeDeploy Demo Repo

This repository is intended to demonstrate the ability to deploy a sample ASP .NET app to AWS using **GitHub Actions**. The process is as such

1. Changes are made to the repo and pushed onto the `main` branch
2. `deploy.yml` workflow will be executed doing a simple _CI_ job (building) followed by a _CD_ job (deploying).
3. The deployment is made to AWS CodeDeploy, which then sends this information to a VM instance where the application is hosted
4. You can access this application via the IP [3.219.63.62](http://3.219.63.62)
