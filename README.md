# Update-AzAAHybridWorkerModules

Updates Modules on Hybrid worker based on PSGallery

This Runbook will check installed modules in AA account and attempt to download them from the configured trusted repositories on to the hybrid worker(s).
It can also update modules installed by local configured repositories(using Install-Module) to the newest version available.
The logic will not clean out older versions of modules.
The different behaviors are configurable by manipulating parameters of the Runbook, see the parameter description below for further details.
