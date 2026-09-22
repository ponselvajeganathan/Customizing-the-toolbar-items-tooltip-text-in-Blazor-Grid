# Customizing the Toolbar Items Tooltip Text in Blazor DataGrid

## Overview

This sample demonstrates how to customize the tooltip text displayed for toolbar items in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid). Toolbar commands provide quick access to common grid actions, and customized tooltip text can improve usability by providing clearer descriptions of each action. The sample shows how toolbar-related UI elements can be tailored to match application-specific terminology while preserving the standard DataGrid toolbar behavior.

## Key Features

- Uses the Syncfusion Blazor DataGrid component (`SfGrid`) to display data with a toolbar interface.
- Demonstrates customization of the tooltip text displayed for DataGrid toolbar items.
- Shows how built-in toolbar commands can provide user-friendly descriptions through custom tooltips.
- Improves accessibility and discoverability of toolbar actions by displaying meaningful tooltip content.
- Demonstrates DataGrid toolbar customization without changing the underlying functionality of the toolbar commands.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `CustomToolbarItems.sln`.
3. Restore all NuGet packages.
4. Set the `CustomToolbarItems` project as the startup project if required.
5. Build the solution.
6. Run the project using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/` — contains the Razor page that hosts the Syncfusion Blazor DataGrid and toolbar customization implementation.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid Toolbar documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/toolbar-items

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
