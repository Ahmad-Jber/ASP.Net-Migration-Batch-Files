# Documentation

- Here is batch files for add and remove migrations, these files must be added in /src/ file
- Here is the command structure for add the migration:

```console
.\Add-Migration [Project-Name] [Migration-Name]
```
  
- Here is the command structure for remove last migration:

```console
.\Remove-Migration [Project-Name]
```

- These command found without files in NuGet Manager Console using EntityFrameworkCore, but you must to use the files in CMD or PowerShell.

## Requirements:

1. ASP.Net Core 7.0 or higher
2. EntityFrameWorkCore 7.0 or higher
