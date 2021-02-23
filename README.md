***HOW TO CREATE NEW PROJECT .NET***
1. Download .NET Runtime (needed if you using vscode)
2. Create new folder
3. Open new terminal to the folder
4. Run command `dotnet new <template>`
5. Check [this](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new?view=aspnetcore-5.0#web-others) to possible value of \<template>

***HOW TO RUN CODE IN VISUAL STUDIO CODE***
1. Press `F5` or `Alt` + `F5`
2. Choose the environment, in this case is .NET
3. Fill the `launch.json` that automatically created, when you run step 2.  
Fill the `<target-framework>` to your .net version, in this case `net4.0` and `<project-name.dll>`, example `dotnetreact.dll` because dotnetreact is this project.