# Documentation

- These are batch files to add and remove migrations, these files must be added in: ###/src/file
- Here is the command structure to add the migration:

```console
.\Add-Migration [Project-Name] [Migration-Name]
```
  
- Here is the command structure to remove the last added migration:

```console
.\Remove-Migration [Project-Name]
```

- These commands found without using files in NuGet Manager Console using EntityFrameworkCore, but you must to use the files in CMD or PowerShell.

## Requirements:

1. ASP.Net Core 7.0 or higher
2. EntityFrameWorkCore 7.0 or higher
