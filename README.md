# SPA Template for ASP.NET Core 2.1 with VueJS and TypeScript

This is a modified template based upon official Microsoft.AspNetCore.SpaTemplate::*

**IMPORTANT** It's strongly recommended to use Bootstrap 4.1.3 or newer. It's relatively easy to migrate.

As of now, official template uses Webpack 2 and older NPM packages, and it hasn't been migrated to .Net Core 2.1.

## This template has the following changes:

- Migrated to .Net Core 2.1
- Updated NPM packages
- Supports Bootstrap 4
- Supports WebPack 4
- Added Serilog

Other than that it has minor changes to VueJS original files.

## How to install:

Just clone or download this repo, and install as follows:

```
dotnet new --install <path to this template directory>
```
You can see it listed `dotnet new -l` with the shortname `vuets` so in order to create new projects using this template just use that shortname.

```
dotnet new vuets -n myspa -o myspa
cd myspa
dotnet restore
npm install
dotnet run
```
To publish, just as usual: `dotnet publish -c release`