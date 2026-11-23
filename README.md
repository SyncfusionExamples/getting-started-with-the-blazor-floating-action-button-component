# Getting Started with the Blazor Floating Action Button Component

## Project Overview
This sample demonstrates how to add the Syncfusion Blazor Floating Action Button component to a .NET 10 Blazor WebAssembly app. The home page shows a data grid and uses the floating action button to add a new record. The button includes an icon, a custom position, and an outline style.

Example: https://blazor.syncfusion.com/demos/fab/overview?theme=fluent

Documentation: https://blazor.syncfusion.com/documentation/floating-action-button/getting-started

## Features
- Uses the Syncfusion Blazor `SfFab` component with the `SfGrid` component.
- Enables adding records through `GridEditSettings` and `AddRecordAsync`.
- Sets the button label through `Content` and the plus icon through `IconCss`.
- Places the icon on the right through `IconPosition`.
- Anchors the button to the grid through `Target` and places it at the bottom right through `Position`.
- Applies an outline appearance through `CssClass`.

## Prerequisites
Ensure the following requirements are met before running this project:
- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with Blazor

## Installation

### Clone the Repository
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/SyncfusionExamples/getting-started-with-the-blazor-floating-action-button-component.git
```
### Run the Application
**Visual Studio 2022**

1. Open the cloned repository folder.
2. Open the project file:

   `ButtonExample.csproj`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `ButtonExample`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Verify that the order grid and the ADD floating action button are displayed.

**Visual Studio Code**

1. Open the cloned repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory:

```bash
cd getting-started-with-the-blazor-floating-action-button-component
```

4. Restore the NuGet packages:

```bash
dotnet restore
```

5. Run the project:

```bash
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.
7. Verify that the order grid and the ADD floating action button are displayed.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Floating Action Button getting started](https://blazor.syncfusion.com/documentation/floating-action-button/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
