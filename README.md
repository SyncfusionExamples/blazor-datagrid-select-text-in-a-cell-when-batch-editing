# Blazor DataGrid - Select Text in a Cell When Batch Editing

## Overview

This sample demonstrates how to automatically select the existing text in a cell editor when a user enters edit mode within the Syncfusion Blazor DataGrid. By default, the editor receives focus during editing, but users may need to manually select the current value before replacing it. This example customizes the editing workflow so that the existing text is selected automatically, allowing users to immediately begin typing and replace the current value. The approach improves data-entry efficiency in batch editing scenarios where frequent cell updates are performed.

## Key Features

- Demonstrates a Syncfusion Blazor DataGrid batch-editing scenario.
- Automatically selects existing text when a cell enters edit mode.
- Enables users to replace the current cell value immediately by typing.
- Improves editing efficiency by eliminating the need for manual text selection.
- Uses a dedicated implementation designed to customize the editor focus and selection behavior during Grid editing.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file located inside the `CellTextSelect` project folder.
3. Restore all NuGet packages.
4. Set the appropriate startup project from the solution if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory located inside the `CellTextSelect` folder.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed after the application starts.

## Project Structure

- `CellTextSelect/Pages/` — contains the page that renders the Syncfusion Blazor DataGrid editing scenario.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid editing documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/batch-editing

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.