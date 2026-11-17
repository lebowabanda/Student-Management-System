Student Management System
A student management system built with ASP.NET Core Web API. The project is intended to provide a backend for managing student information and, as it develops, related operations such as creating, viewing, updating, and deleting student records.
Technology
- C#
- ASP.NET Core Web API
- .NET 10 (LTS)
- Visual Studio Code
- Git and GitHub
Prerequisites
Install the following before running the project:
- .NET 10 SDK
- Visual Studio Code
- C# Dev Kit extension for VS Code
- Git
Check that the .NET SDK and Git are available:
dotnet --version
git --version
Getting started
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/student-management-system.git
cd student-management-system
Replace YOUR-USERNAME with the GitHub account that owns the repository.
2. Create the API project (if it has not been created yet)
From the repository root, run:
dotnet new webapi --use-controllers -n StudentManagement.Api
This creates the API project in the StudentManagement.Api directory. If the project already exists in the repository, skip this step.
3. Restore dependencies
cd StudentManagement.Api
dotnet restore
4. Build the project
dotnet build
5. Run the API
dotnet run
Use the local URL printed in the terminal. If the project maps the health-check endpoint, you can check it at:
/api/health
For example, if the application reports that it is listening at https://localhost:7001, open https://localhost:7001/api/health in your browser. Use the actual URL and port printed by your application.
Project structure
The API is organized by responsibility. Add these folders as the corresponding features are implemented:
student-management-system/
├── .gitignore
├── README.md
└── StudentManagement.Api/
    ├── Controllers/
    ├── Data/
    ├── DTOs/
    ├── Entities/
    ├── Middleware/
    ├── Services/
    ├── Program.cs
    └── appsettings.json
Configuration and secrets
- Keep environment-specific settings in the appropriate appsettings files.
- Do not commit passwords, API keys, connection-string credentials, certificates, or other secrets.
- For local development, use .NET User Secrets or environment variables.
- If you add required environment variables, document their names and safe example values here or in an .env.example file. Never put real secret values in .env.example.
Development workflow
Create a feature branch for each change:
git switch -c feature/your-feature-name
After making and testing your changes:
git status
git add .
git commit -m "Describe your change"
git push -u origin feature/your-feature-name
Then open a pull request on GitHub and merge it into main after review.
Current status
This repository is the starting point for the Student Management System API. Add details here as features, endpoints, tests, and deployment instructions are implemented.
