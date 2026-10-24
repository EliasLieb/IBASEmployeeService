# IBAS Employee Service

Studieprojekt: et medarbejder-API bygget med ASP.NET Core og C#.

## Indhold

- `Controllers/EmployeeController.cs`: API-controller til medarbejdere.
- `Models/`: datamodeller.
- `Program.cs`: opsætning af applikationen.
- `Dockerfile`: definition til containerbygning.
- `IBASEmployeeService.http`: HTTP-forespørgsler til afprøvning.

## Lokal udvikling

1. Klon projektet: `git clone https://github.com/EliasLieb/IBASEmployeeService.git`.
2. Installer .NET SDK-versionen, som projektfilens `TargetFramework` kræver.
3. Gennemgå `appsettings.json` og konfigurer eventuelle nødvendige tjenester lokalt. Brug user secrets eller miljøvariabler til hemmeligheder.
4. Kør `dotnet restore` og `dotnet run` fra projektmappen.
5. Brug adressen fra terminalen ved afprøvning af API'et.

## Status

Studieprojekt. Build, eksterne tjenester og deployment er ikke verificeret som del af repository-oprydningen.
