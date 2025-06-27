# Todo API

This sample project provides a minimal API backend for managing todo items using ASP.NET Core and Entity Framework Core with PostgreSQL.

## Running

1. Ensure the .NET SDK is installed.
2. Set the `TodoDb` connection string in `appsettings.json` or via environment variables. By default it uses:

```
Host=localhost;Database=todos;Username=postgres;Password=postgres
```

3. Build and run the application:

```bash
dotnet run
```

The API will expose CRUD endpoints under `/todoitems`.
