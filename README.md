# CSV Join
A command-line tool for performing full outer joins on CSV files in C# .NET Core:
```
CsvJoin.exe Data sales.csv new_sales.csv > merged_sales.csv
```

## Features:
- Execute SQL against CSV files
- Save results to CSV
- Save auto-generated SQL

## Prerequisites:
- Microsoft Access Database Engine 2016 Redistributable
- .NET Core 3.1
- Visual Studio 2019

## Credits:
- Microsoft Access Database Engine 2016 by https://www.microsoft.com/en-us/download/details.aspx?id=54920 (own license)
- System.Data.OleDb by https://www.nuget.org/packages/System.Data.OleDb (MIT license)
- CsvHelper by https://joshclose.github.io/CsvHelper (MS-PL or Apache-2.0 license)
