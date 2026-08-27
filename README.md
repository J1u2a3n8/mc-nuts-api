# mc-nuts-api

> Full-Stack REST API in .NET

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/mc-nuts-api)
![License](https://img.shields.io/github/license/J1u2a3n8/mc-nuts-api)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/mc-nuts-api)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/mc-nuts-api?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/mc-nuts-api)

## Description

A production-ready REST API built with ASP.NET Core 8, featuring Clean Architecture, Entity Framework Core, JWT authentication, OpenAPI/Swagger documentation, and comprehensive test coverage.

## Architecture

Clean Architecture: Controllers → Services → Domain → Infrastructure (EF Core, SQL Server)

## Quick Start

### Prerequisites

.NET 8 SDK, Visual Studio 2022 / VS Code with C# Dev Kit

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/mc-nuts-api.git
cd mc-nuts-api

dotnet restore
# dotnet build
# dotnet ef database update
```

### Usage

```bash
dotnet run --project src/MCNutsAPI
```

## Testing

```bash
dotnet test
```

## Project Structure

```
mc-nuts-api/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

C#, .NET 8, ASP.NET Core, Entity Framework Core, SQL Server, Swagger, JWT, xUnit

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://linkedin.com/in/juanluiscanedo)

---

⭐ If you found this project useful, give it a star!
