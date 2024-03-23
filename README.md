# Assessment Overview: Building a User's and Tasks API

## Introduction
This project focuses on the development of an ASP.NET Core Web API to manage users and tasks. It encompasses API development, authentication, database interaction, filtering tasks based on due dates, testing, Swagger documentation, and submission guidelines.

## Part 1: API Development
- Start by creating a new ASP.NET Core Web API project.
- Define models for User and Task with specified fields.
- Implement CRUD operations for both users and tasks through controllers and endpoints.

## Part 2: Authentication
- Choose between API key or bearer token authentication.
- For API key: Generate a unique key for each user and require it for accessing endpoints.
- For bearer token: Implement JWT authentication, generating and validating tokens.

## Part 3: Database Interaction
- Choose between Entity Framework Core or Dapper for database operations.
- Set up a local database for storing users and tasks.
- Utilize repository patterns for database interactions.

## Part 4: Filtering
- Implement filtering for tasks based on due dates, enabling retrieval of expired, active, or tasks by a certain date.

## Part 5: Testing
- Write unit tests for both API controllers and repository methods using a suitable testing framework.

## Part 6: Swagger Documentation
- Integrate Swagger to automatically generate documentation for all API endpoints.

## Part 7: Submission
- Your final submission should be a public GitHub repository link. Ensure no zip files or Google Drive links are submitted.

### Migration Commands
To facilitate database versioning and updates, use the following Entity Framework commands:
- `Add-Migrations <migration name> -o Data/Migrations` to create migration files.
- `Update-Database` to apply migrations and update the database accordingly.
