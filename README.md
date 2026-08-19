# Web Application Tutorial

A .NET web application tutorial project structured as a Visual Studio solution and ASP.NET application.

## Overview

The repository is organized around the standard .NET solution/application structure and is intended for learning web application development with the Microsoft stack.

## Development

Restore dependencies, build the solution, and run the application with the .NET CLI:

```bash
dotnet restore
dotnet build
dotnet run
```

Run tests when test projects are present:

```bash
dotnet test
```

## Project Structure

- `WebApplicationTutorial.sln` — solution definition
- `WebApplicationTutorial/` — application source
- `.gitignore` — generated/build files excluded from source control

## Configuration

Use environment-specific configuration for connection strings, credentials, API keys, and other deployment settings. Do not commit secrets.

## Purpose

This project provides a practical foundation for learning and experimenting with .NET web application development.