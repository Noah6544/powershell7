# Changelog

All notable changes to this project will be documented in this file.

## Release 0.2.0

**Features**
- Added: able to set the notification policy for Powershell 7 Update checks.
- Added: added metadata.json tags for better visibility of what this module references.

**Bugfixes**
- Fix: powershell7::install exec kept running due to the creates attribute sourcing the wrong file.
- Fix: installation source URLs now allow HTTP as well has HTTPS locations.
- Fix: supported version of puppet was lowered to `6.0.0` as it works across all Puppet 6 versions.

## Release 0.1.0

**Features**
- Added: Able to install PowerShell 7 on Windows Server (2012 R2, 2016, 2019)

**Bugfixes**

**Known Issues**
