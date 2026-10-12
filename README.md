# Title

Getting Started with the Blazor Floating Action Button Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Floating Action Button](https://www.syncfusion.com/blazor-components/blazor-fab) component in a Blazor WebAssembly application. The implementation integrates a Floating Action Button (FAB) with a Syncfusion Grid and provides a practical example of performing Grid operations through a floating action control.

The FAB is configured with custom text, an icon, custom styling, and a fixed position within the application. When the user clicks the button, a Grid API is invoked programmatically through a component reference, allowing new records to be added dynamically. This demonstrates how a Floating Action Button can serve as a prominent action trigger for data-entry scenarios.

## Key Features

- Demonstrates the Syncfusion `SfFab` component.
- Displays a Floating Action Button using `Content="ADD"`.
- Shows a built-in icon using `IconCss="e-icons e-plus"`.
- Applies custom styling using `CssClass="e-outline"`.
- Connects the FAB to the Grid using `Target="#Grid"`.
- Handles user interactions through the `OnClick` event.
- Uses a Grid component reference (`@ref="GridReference"`).
- Invokes `AddRecordAsync()` on the Grid when the FAB is clicked.
- Enables record creation through `GridEditSettings AllowAdding="true"`.
- Demonstrates integration between `SfFab` and `SfGrid<DataModel>`.
- Binds Grid data using a strongly typed `DataModel` collection.
- Displays Order ID, Customer ID, Freight, and Ship Country columns through Grid column definitions.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open `ButtonExample.cspro`.
3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the application URL displayed in the terminal.

## Project Structure

- `ButtonExample.csproj` — Blazor WebAssembly project file containing package references and build configuration.

- `Pages/Index.razor` — Demonstrates the Syncfusion Floating Action Button integrated with a Grid. Uses `SfFab`, `SfGrid<DataModel>`, `AddRecordAsync()`, custom positioning, icons, and styling.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/floating-action-button/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.