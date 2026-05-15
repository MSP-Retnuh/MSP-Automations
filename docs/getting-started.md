# Getting Started

## Overview

This repository contains PowerShell automation scripts created during the MSP lead tech role.

## Prerequisites

- PowerShell 5.0 or higher (PowerShell 7+ recommended)
- Appropriate permissions for scripts being executed

## Usage

### Running Scripts

```powershell
# Navigate to the scripts/powershell directory
cd scripts/powershell

# Run a script
.\script-name.ps1
```

### Execution Policy

If you encounter execution policy errors:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

## Security Notes

- Never commit credentials or sensitive data
- Use `.gitignore` for local config files
- Consider using secure credential storage solutions
