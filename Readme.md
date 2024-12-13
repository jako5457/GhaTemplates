# Github actions templates

### About this repository
This repository is a colletion of custom github actions.

### Actions in this repository
- NugetSetup.yml: Setup dotnet and the nuget cli tool.

## NugetSetup.yml

Installs dotnet and the nuget package manager CLI.

#### Example
```yml
jobs:
    - name: Install nuget
      uses: jako5457/GhaTemplates/.github/workflows/NugetSetup.yml@main
      with:
        dotnet-version: 9.x
```
