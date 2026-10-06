# PowerShell Administration Lab

## Overview

This lab documents hands-on PowerShell activities performed during infrastructure training. The exercises focused on PowerShell cmdlets, pipelines, aliases, data export, file conversion, and basic automation tasks. :contentReference[oaicite:0]{index=0}

## Lab Environment

- Windows PowerShell
- Command Line Interface
- CSV Files
- JSON Files
- Text Files

## Skills Practiced

- PowerShell Cmdlets
- Pipelines
- Process Monitoring
- Service Monitoring
- Aliases
- CSV Export
- JSON Conversion
- File Manipulation
- Basic Automation

---

## Assignment 1 – Cmdlets and Pipelines

### Tasks Performed

#### Basic Cmdlets

- Used Get-Process to view running processes.
- Used Get-Service to monitor Windows services. :contentReference[oaicite:1]{index=1}

#### Pipelines

- Practiced PowerShell pipelines.
- Filtered process information using Where-Object.

Example:

```powershell
Get-Process | Where-Object {$_.CPU -gt 10}
```

This command displays processes consuming high CPU resources. :contentReference[oaicite:2]{index=2}

#### Aliases

- Explored built-in aliases.
- Created custom aliases for frequently used commands.
- Practiced command simplification techniques. :contentReference[oaicite:3]{index=3}

---

## Assignment 2 – File Conversion and Data Processing

### Tasks Performed

#### Export Process Data to CSV

Example:

```powershell
Get-Process | Export-Csv processes.csv
```

- Exported process information to CSV format.
- Practiced reporting and data collection. :contentReference[oaicite:4]{index=4}

#### Convert CSV to JSON

- Converted CSV data into JSON format.
- Practiced data transformation techniques. :contentReference[oaicite:5]{index=5}

#### Text File Processing

- Read text files using Get-Content.
- Modified file content using Set-Content.
- Practiced file automation tasks. :contentReference[oaicite:6]{index=6}

---

## Tools & Technologies

```text
PowerShell
Get-Process
Get-Service
Where-Object
Export-Csv
Get-Content
Set-Content
CSV
JSON
```

## Key Learnings

- PowerShell command execution
- Process and service monitoring
- Pipeline usage
- Command alias management
- CSV and JSON data handling
- File processing automation
- Basic scripting concepts
