[![Java CI with Maven](https://github.com/fangjian0423/asa-admin/actions/workflows/maven.yml/badge.svg)](https://github.com/fangjian0423/asa-admin/actions/workflows/maven.yml)

# Introduction - Azure Spring Apps Admin

Spring Boot Admin Server is an application for managing and monitoring microservice applications.

This repository maintains a customized Spring Boot Admin Server - **Azure Spring Apps Admin**, which did some enhancements beyond community Spring Boot Admin.

# What's the benefit of Azure Spring Apps Admin

1. Integrated with Azure Active Directory to secure your dashboard
2. Easily deploy with one click Azure Spring Apps button instead of multiple Azure commands
3. Fully compatible with community Spring Boot Admin

# Run Azure Spring Apps Admin on Azure Spring Apps

To deploy Spring Boot Admin to Azure Spring Apps using the Azure Spring Apps button, you need below prerequisites:

- An Azure subscription
- An Azure AD administrative roles user
- Azure Service Principal client id to enable Azure Active Directory
- Azure Service Principal client secret to enable Azure Active Directory
- Azure Service Principal tenant id to enable Azure Active Directory

Then, you can run this Azure Spring Apps Admin by one click button:

<a href="https://yonghui-apps-dev-nubesgen.azuremicroservices.io/deploy.html?url=https://github.com/fangjian0423/asa-admin" data-linktype="external">
<img src="https://user-images.githubusercontent.com/58474919/236122963-8c0857bb-3822-4485-892a-445fa33f1612.png" alt="Deploy to Azure Spring Apps" width="200px" data-linktype="relative-path">
</a>

