# NFL Depth chart management

A comprehensive NFL depth chart management system built with .NET. This application allows teams to manage player positions and depth rankings.

## 🧠 Thought Process, Assumptions & Key Decisions

- Implemented Clean Architecture to improve maintainability and ensure a clear separation of concerns.
- To keep the current setup simple, JSON files are used for data storage.
- In a real-world production environment, a database would be used for data storage and retrieval. To support this, a repository implementation of IDepthChartRepository containing database-specific logic would be developed. This approach highlights the benefit of having a loosely coupled system, making such transitions seamless.
- Implemented a comprehensive suite of automated tests to validate functionality across all possible scenarios.


## 🚀 Quick Start

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)

### Running the Application

1. **Clone the repository**
https://github.com/imsangram/sports-depth-chart.git

2. **Run the application**
```
dotnet restore
dotnet run --project src/DepthCharts.Api/DepthCharts.Api.csproj
```


