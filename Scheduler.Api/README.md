# Scheduler REST Api
[![Build Status](https://dev.azure.com/v-echo/Scheduler/_apis/build/status/Web%20API%20CI%20Build?branchName=master)](https://dev.azure.com/v-echo/Scheduler/_build/latest?definitionId=4?branchName=master)

## Project setup
```
dotnet restore
```

### Build for development
```
dotnet build --configuration Debug
```

### Build and publish for production
```
dotnet build --configuration Release
dotnet publish --output dist
```

### Run your unit tests
```
dotnet test
```

### More info
https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x