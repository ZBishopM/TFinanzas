# TFinanzas

Trabajo final y parcial de Finanzas

## In appsettings.json

``"DefaultConnection": "Server= `` Your_server_name
```;Database=DbBonos; ... "```

## To Database
```
dotnet ef database update -c ApplicationDbContext --project BonosCalculadora

dotnet ef database update -c DbBonosContext --project BonosCalculadora
```
## To Run
```
dotnet -run --project BonosCalculadora
```

## Development mode

```
$ dotnet watch --project BonosCalculadora run
```
