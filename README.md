# Arcade

## Overview

Arcade is intended to provide well-understood and consistent mechanisms for consuming, updating, and sharing infrastructure across the .NET Core team. For more details about Arcade, please see the [Overview](./Documentation/Overview.md) documentation.

## Build & Test Status

Azure DevOps [![Build Status](https://dev.azure.com/dnceng/public/_apis/build/status/dotnet/arcade/arcade-ci)](https://dev.azure.com/dnceng/public/_build/latest?definitionId=208)

## Validation & Dependency Flow Status

### Current Version of Arcade in `.NET Eng - Latest`

[Link](https://maestro-prod.westus2.cloudapp.azure.com/2/https:%2F%2Fgithub.com%2Fdotnet%2Farcade/latest/graph) to BARViz

### Latest Version of Arcade Being Validated

[Link](https://maestro-prod.westus2.cloudapp.azure.com/9/https:%2F%2Fdev.azure.com%2Fdnceng%2Finternal%2F_git%2Fdotnet-arcade/latest/graph) to BARViz. 

### Status of Latest Version of Arcade Being Validated

- Could not validate against `dotnet/aspnetcore` at this time

[Result](https://dnceng.visualstudio.com/internal/_build/results?buildId=593995&view=results) of latest Arcade Validation run on 4/8/2020 at 5:00pm PDT

## Getting Started

Packages are published daily to our tools feed:

> `https://pkgs.dev.azure.com/dnceng/public/_packaging/dotnet-eng/nuget/v3/index.json`

This feed is browsable from here:

> https://dev.azure.com/dnceng/public/_packaging?_a=feed&feed=dotnet-eng

### Source Code

`git clone https://github.com/dotnet/arcade.git`

### How to use Arcade

Documentation, tutorials, and guides may be found in the [Start Here](Documentation/StartHere.md) index. 

### How to contribute

- [How to contribute to Arcade guide](Documentation/Policy/ArcadeContributorGuidance.md)

- [Pull requests](https://github.com/dotnet/arcade/pulls): [Open](https://github.com/dotnet/arcade/pulls?q=is%3Aopen+is%3Apr)/[Closed](https://github.com/dotnet/arcade/pulls?q=is%3Apr+is%3Aclosed)

- [Issues](https://github.com/dotnet/arcade/issues)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).  For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### License

.NET Core (including the Arcade repo) is licensed under the [MIT license](LICENSE.TXT). 
