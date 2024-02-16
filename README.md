# ProductosNET

dotnet tool install --global dotnet-ef

y luego usar: 

dotnet ef add migration Productos

dotnet ef database update

Install SQL SERVER EXPRESS, open SQLMD and RUN a connection

-------then fix the appsettings.json to update------------

{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*",
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost\\SQLEXPRESS;Database=TuBaseDeDatos;Trusted_Connection=True;MultipleActiveResultSets=true;TrustServerCertificate=true"
  }
}


----------------------------

