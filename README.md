# Row Drag-and-Drop in TreeGrid with Remote Data Binding

A comprehensive sample demonstrating server-side row drag-and-drop operations in [TreeGrid](https://www.syncfusion.com/blazor-components/blazor-tree-grid) component with remote data binding via URL Adaptor in ASP.NET Core.

## Overview

This project showcases how to build a responsive TreeGrid component that fetches data dynamically from a remote server and supports interactive row drag-and-drop operations. The application demonstrates best practices for handling hierarchical data, managing parent-child relationships, and persisting changes on the server.

The architecture uses:
- **Frontend**: TreeGrid with client-side drag-and-drop
- **Backend**: ASP.NET Core with data management and drag-drop logic
- **Communication**: URL Adaptor pattern for remote data binding

## Features

- **Remote Data Binding**: Fetch hierarchical data on-demand using URL Adaptor
- **Row Drag-and-Drop**: Intuitive drag-and-drop interface for reordering rows
- **Server-Side Processing**: Handle drag operations with automatic parent-child relationship management
- **CRUD Operations**: Create, read, update, and delete rows with server persistence
- **Dynamic Data Loading**: Load child records on demand for better performance
- **Hierarchical Data Support**: Automatic handling of parent and child relationships

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/row-drag-and-drop-in-treegrid-with-remote-data-binding.git
cd row-drag-and-drop-in-treegrid-with-remote-data-binding
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- [TreeGrid Documentation](https://blazor.syncfusion.com/documentation/treegrid/getting-started-webapp)
- [Row Drag and Drop](https://blazor.syncfusion.com/documentation/treegrid/rows/row-drag-and-drop)
- [ Data Binding](https://blazor.syncfusion.com/documentation/treegrid/data-binding)




