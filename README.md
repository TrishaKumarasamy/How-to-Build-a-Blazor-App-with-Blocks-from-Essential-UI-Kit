# Support Portal App with Essential UI Kit

A production-ready support portal application built with **Blazor** and **Essential UI Kit**, demonstrating best practices for customer support ticket management, real-time chat interactions, and responsive design.

## Overview

This project showcases a modern support portal for managing customer queries and support tickets. Built on [ASP.NET Core 8.0](https://learn.microsoft.com/en-us/aspnet/core/?view=aspnetcore-8.0) with [Blazor](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor), it demonstrates how to rapidly assemble a feature-rich, professional support system with pre-designed components and intuitive interfaces.

* The application provides support agents with powerful tools to manage tickets, interact with customers through real-time chat.
* This application tracks satisfaction metrics—all within a responsive, accessible UI built on modern web standards.

## Features

- **Ticket Management** - Create, view, and manage support tickets with multiple status states and filtering options
- **Real-Time Chat** - Interactive communication channel with customers directly within tickets
- **Dashboard Analytics** - Track support metrics including satisfaction ratings, ticket status breakdowns, and response times
- **Multi-View Layouts** - Organize tickets using grid and tile views for flexible browsing
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices with adaptive sidebar navigation
- **Dark Mode Support** - Full dark mode support throughout the application for improved accessibility
- **Rich Components** - Leverages Syncfusion's essential component library including DataGrid, Sidebar, Buttons, Inputs, and more

## Tech Stack

| Technology | Purpose |
|---|---|
| [ASP.NET Core 8.0](https://learn.microsoft.com/en-us/aspnet/core/?view=aspnetcore-8.0) | Backend framework |
| [Blazor](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor) | Interactive Server UI |
| [Syncfusion Essential UI Kit v29.1.33](https://www.syncfusion.com/essential-blazor-ui-kit) | Component library |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| C#, Razor | Languages |

### Syncfusion Components

The application uses the following Syncfusion packages:

- `Syncfusion.Blazor.Grid` - Data display and management
- `Syncfusion.Blazor.Inputs` - Form inputs and text boxes
- `Syncfusion.Blazor.Lists` - List views and navigation
- `Syncfusion.Blazor.Navigations` - Sidebar and navigation components
- `Syncfusion.Blazor.ProgressBar` - Progress indicators
- `Syncfusion.Blazor.RichTextEditor` - Rich text editing
- `Syncfusion.Blazor.Themes` - Theming and styling system

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository
   ```bash
   git clone https://github.com/SyncfusionExamples/How-to-Build-a-Blazor-App-with-Blocks-from-Essential-UI-Kit.git
   cd How-to-Build-a-Blazor-App-with-Blocks-from-Essential-UI-Kit
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

- [Essential UI Kit Documentation](https://blazor.syncfusion.com/documentation/ui-kit/overview)
- [License Key Documentation](https://blazor.syncfusion.com/documentation/getting-started/license-key/overview)
- [Essential UI Kit Demo](https://blazor.syncfusion.com/essential-ui-kit/)