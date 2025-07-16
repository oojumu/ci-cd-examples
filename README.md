# CI/CD Workflow Templates

Welcome to my collection of CI/CD pipeline templates — designed for real-world deployment using **GitHub Actions** and **Azure DevOps**. These examples demonstrate my experience in automating build, test, and deployment workflows, particularly for **.NET** applications.

---

## 📁 GitHub Actions Workflows

### 🚀 Deploy ASP.NET Core App to Azure Web App

**Path:** [`github-actions/ci-deploy-template.yml`](github-actions/ci-deploy-template.yml)

This workflow:

- Builds and publishes a .NET app using `dotnet build` and `dotnet publish`
- Uploads the published output as an artifact
- Logs into Azure using OIDC credentials
- Deploys to an Azure Web App using `azure/webapps-deploy@v3`

🔒 Uses best practices for secret management and environment permissions.  
💼 Adapted from a production-ready eCommerce solution.

---

## ✅ Technologies Used

- GitHub Actions
- Azure Web Apps
- ASP.NET Core
- OIDC Auth
- YAML Pipelines

---

## 🔗 Showcase

You can find this workflow in use in my project:  
[GorgeousOutfitDemo (private repo)](https://github.com/oojumu/GorgeousOutfitDemo) – an ASP.NET/React eCommerce app deployed to Azure.
