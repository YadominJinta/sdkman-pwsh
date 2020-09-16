# SDKMAN-Pwsh

> The Software Development Kit Manager

**SDKMAN-Pwsh** is a tool for managing parallel versions of multiple Software Development Kits on windows. It's inspired by **[SKDMAN!](https://sdkman.io)**, which only support unix systems.

_The Project is WIP_

## Installation

``` powershell
Install-Module sdkman-pwsh
```

## Usage

``` powershell
# Get SDK candicates
Get-SDKList
# Get versions of a candicates
Get-SDKList -Candicate Java
# Install a candicate
Install-SDK -Candicate Java -Version 14.0.2.hs-adpt
# Switch a version
Set-SDK -Candicate Java -Version 8.0.265.hs-adpt
# Set Default
Set-SDK -Candicate Java -Version 8.0.265.hs-adpt -asDefault
# Remove SDK
Remove-SDK -Candicate Java -Version 8.0.265.hs-adpt
```