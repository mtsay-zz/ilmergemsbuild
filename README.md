Steps to Build
---
- Download `nuget.exe` from [NuGet](https://nuget.org/nuget.exe) and place it
  inside the folder `.nuget`.
- Open `ILMergeMSBuild.sln` with Visual Studio.
- Go to Build -> Configuration Manager... and set Active solution configuration
  to Release.
- Build the solution.
- The output artifact will be placed in `MsBuild.ILMerge.Task\bin\Release`.
