# Blazor DataGrid — Customize Background Color for Grid Exported Excel File

A sample Blazor application demonstrating how to customize the background color of the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component when exporting data to Excel files.

## Overview

This repository demonstrates how to apply custom styling to a Blazor DataGrid when exporting it to an Excel file. Instead of using default colors, the sample shows how to use the `ExcelTheme` and `ExcelStyle` APIs to customize the background color of different grid elements (headers, records, and captions) in the exported Excel output.

The sample includes:

- A fully functional Blazor Server application with an interactive datagrid
- Example order data with multiple columns (Order ID, Customer Name, Order Date, and Freight)
- Toolbar button for triggering Excel export with custom styling
- Reusable code patterns for applying themes during export operations

## Features

- **Custom Excel Styling** - Apply custom background colors to headers, records, and captions during export
- **Theme Customization** - Use the `ExcelTheme` API to define consistent styling across exported documents
- **Flexible Export** - One-click toolbar button for seamless Excel export with custom styling
- **Sorting & Pagination** - Built-in sorting and pagination support to handle large datasets efficiently
- **Dynamic Data Binding** - Seamlessly bind collections to the grid with automatic updates
- **Responsive Design** - Works seamlessly across desktop, tablet, and mobile browsers

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`GridExportExcelFile.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-customize-background-color-for-grid-exported-excel-file
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/excel-exporting

**Online example**: https://blazor.syncfusion.com/demos/datagrid/exporting?theme=fluent2