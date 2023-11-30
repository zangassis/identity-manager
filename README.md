# Identity Manager - ASP.NET Core Minimal API 🚀

**This project contains a sample ASP.NET Core app. This app is an example of the article I produced for the Telerik Blog (telerik.com/blogs).**

## Overview

Identity Manager is an ASP.NET Core Minimal API built on .NET 8, leveraging Identity features for seamless user authentication and authorization. The application utilizes SQLite as its database and EF Core.

## Features

- 🛡️ **Identity Integration:** Seamlessly manage user authentication and authorization with ASP.NET Core Identity.

- 📦 **SQLite Database:** Utilize the lightweight and efficient SQLite database for storing user information.

- 🚀 **EF Core:** Leverage the power of Entity Framework Core for efficient data access and management.

## Getting Started

Follow these steps to get started with Identity Manager:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/zangassis/identity-manager.git
   ```

2. **Navigate to the Project:**
   ```bash
   cd identity-manager
   ```

3. **Install Dependencies:**
   ```bash
   dotnet restore
   ```

4. **Run the Application:**
   ```bash
   dotnet run
   ```

The application will be accessible at `https://localhost:PORT/swagger/index.html`.

## Database Migration

Apply the initial database migration to create the necessary tables for Identity Manager.

```bash
dotnet ef database update
```

## API Endpoints

Explore the various API endpoints provided by Identity Manager for user authentication and management.

## Contributing

We welcome contributions! If you find a bug or have an enhancement in mind, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your project's specific details and requirements. Happy coding! 🎉