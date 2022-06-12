# dotnet-publish-multiplatform.sh
Shell script to publish a .NET project for multiple target frameworks and zip each built program at once.
## What it does
1. runs `dotnet publish -c Release -r $arch`. (Which usually? means building self-contained app.) 
2. zips the folder to `./bin/publish`
## Installation (Windows)
1. Install git bush by pressing download button [here](https://gitforwindows.org/)
2. Put publish.sh in the same directory as your project file (.csproj, etc.)
## Usage
```shell
> publish.sh
```
