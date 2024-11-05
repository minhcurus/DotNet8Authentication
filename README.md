# DotNet8Authentication

.NET 8 Authentication with Identity in a Web API with Bearer Tokens & Cookies

## Description

This repository contains a .NET 8 Web API project that demonstrates how to implement authentication using Identity with both Bearer Tokens and Cookies.

## Features

- Secure authentication using Bearer Tokens
- Cookie-based authentication for web clients
- Integration with ASP.NET Core Identity
- Example API endpoints with authentication and authorization

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or any other preferred IDE

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/minhcurus/DotNet8Authentication.git
   ```
2. Navigate to the project directory:
   ```sh
   cd DotNet8Authentication
   ```
3. Restore the dependencies:
   ```sh
   dotnet restore
   ```
### Running the Application
1. Build the project:
   ```sh
   dotnet build
   ```
2. Run the project:
   ```sh
   dotnet run
   ```
### Running the Application
You can use tools like Postman or curl to test the API endpoints. Example request:
 ```sh
   curl -X GET https://localhost:5001/api/secure-endpoint -H "Authorization: Bearer <your_token>"
 ```
### Contributing
Contributions are welcome! Please fork the repository and create a pull request.

### Contact
For any inquiries or support, please open an issue on this repository.
