# Student Management System

**A RESTful Web API built with C# and ASP.NET Core Web API**

<escape></escape> **Project Status:** In Development

## About the Project

The Student Management System is a backend development project I am building to improve how student information is stored and managed within an educational institution.

The idea behind this project is simple: create a system where student records can be managed through a structured API instead of relying on manual record-keeping.

I chose this project because I wanted to move beyond writing small code examples and start building something practical that reflects how backend applications are developed in real-world environments.

I am using C#, ASP.NET Core Web API and .NET 10 to build the application. My main focus is understanding how to design API endpoints, organize application code, handle data and follow good software development practices.

This is an ongoing learning project, and I am developing it step by step as I improve my backend development skills.

## What I Want to Achieve

The main goal is to build a functional Student Management System that can:

- Register new students.
- Retrieve all registered students.
- Retrieve an individual student using their ID.
- Update existing student information.
- Delete student records.
- Store and manage student information efficiently.

Beyond the functionality, I also want to understand how different parts of a backend application work together, from receiving HTTP requests to processing data and returning appropriate responses.

## Technologies Used

| Technology | How I Use It |
|---|---|
| C# | Writing the backend application logic |
| .NET 10 | Framework for building the application |
| ASP.NET Core Web API | Creating REST API endpoints |
| SQL Server | Planned database integration |
| Entity Framework Core | Planned database access and management |
| Visual Studio Code | Writing and managing code |
| Git | Tracking changes during development |
| GitHub | Hosting and managing the project repository |

## Project Structure

I am keeping the project organized by separating different responsibilities into their own folders.

```text
StudentManagement.Api/
│
├── Controllers/
│
├── DTOs/
│
├── Entities/
│
├── Data/
│
├── Services/
│
├── Middleware/
│
├── Program.cs
└── appsettings.json
```

### Understanding the Structure

As the application grows, I am using the following organization:

- **Controllers:** Responsible for handling HTTP requests and returning responses.
- **DTOs:** Used to define what data is received and returned by the API.
- **Entities:** Represent the main data models used by the application.
- **Data:** Will contain database-related configuration and the database context.
- **Services:** Will contain business logic, keeping controllers focused on handling requests.
- **Middleware:** Provides a place for handling application-wide HTTP concerns.
- **Program.cs:** Configures and starts the application.

I am following this structure to keep the code readable, organized and easier to maintain.

## Development Progress

I am building the application incrementally rather than trying to implement every feature at once.

My development roadmap includes:

- [x] Create the ASP.NET Core Web API project.
- [ ] Create the Student entity.
- [ ] Implement student registration.
- [ ] Implement retrieving all students.
- [ ] Implement retrieving a student by ID.
- [ ] Implement updating student information.
- [ ] Implement deleting student records.
- [ ] Add request validation.
- [ ] Integrate SQL Server using Entity Framework Core.
- [ ] Implement proper exception handling.
- [ ] Add unit tests.
- [ ] Configure API documentation with Swagger.

*Note: The checklist should be updated as features are actually completed.*

## Running the Project Locally

If you want to explore or run the project on your local machine, follow these steps.

### Requirements

- .NET 10 SDK
- Visual Studio Code or another compatible IDE
- Git
- C# Dev Kit extension (recommended)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/student-management-system.git
```

### 2. Navigate to the Project

```bash
cd student-management-system/StudentManagement.Api
```

### 3. Restore Dependencies

```bash
dotnet restore
```

### 4. Build the Application

```bash
dotnet build
```

### 5. Run the Application

```bash
dotnet run
```

The application will start at the development URL displayed in your terminal.

If Swagger is configured, you can use the Swagger interface to explore and test the API endpoints.

## What I Am Learning

Building this project is helping me understand the practical side of backend development.

Some of the concepts I am working on include:

- Building RESTful APIs using ASP.NET Core.
- Understanding HTTP methods and status codes.
- Applying object-oriented programming in C#.
- Organizing code using controllers, services and DTOs.
- Understanding dependency injection.
- Working with data models.
- Learning database integration with Entity Framework Core.
- Using Git to manage changes and track development progress.
- Writing code that is easier to read, understand and maintain.

I believe understanding the reasoning behind the code is just as important as getting the application to work.

## Future Improvements

Once the core student management functionality is complete, I plan to extend the application with:

- User registration and authentication.
- Role-based authorization for administrators and staff.
- Course and subject management.
- Student enrollment.
- Academic results management.
- Attendance tracking.
- Search and filtering.
- Automated testing.

These improvements will allow me to explore more advanced backend development concepts as the project progresses.

## Why I Built This Project

I built this project as part of my journey towards becoming a professional backend developer.

I wanted to work on something practical where I could apply what I have learned, encounter real development challenges and improve my problem-solving skills.

I understand that becoming a good developer takes more than knowing a programming language. It requires understanding how applications are structured, how data flows through a system, how to solve problems and how to write code that other developers can work with.

That is exactly what I want to develop through this project.

I am continuously learning, improving and adding functionality as my understanding grows.

---

**Developer:** Junior Backend Developer

**Primary Focus:** C# | ASP.NET Core Web API | Backend Development

**Project Status:** In Development
