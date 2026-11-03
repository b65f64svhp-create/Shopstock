# ShopStock releases

This repository hosts signed ShopStock software update files and release notes. It does not contain the private application source code.

ShopStock runs on a local server. Employee accounts, inventory, stock history, credentials and backups stay with that installation and are not uploaded here.

## Current status

**0.4.0 Dell pilot** is available to commissioned test installations through the [signed pilot channel](channels/debian13-amd64-pilot.json). It passed 281 automated tests. Hardware, interrupted-update recovery and browser USB acceptance remain separate. It is not a stable production release.

Updates will be installed through the Admin controls in ShopStock after signature, hardware compatibility and recovery checks. USB screen installation and network updates are separate operations.

Do not upload databases, configuration files, private signing keys, device backups or Wi-Fi credentials to this repository.
