# Zazu for VS Code: releases

Signed builds of the Zazu chat extension. Installed copies check this repository and update themselves.

To install by hand, download `zazu-vscode-<version>.vsix` from the latest release, then in VS Code use Extensions, `…`, **Install from VSIX…** (or `code --install-extension zazu-vscode-<version>.vsix`).

Each release also carries `latest.json`, which lists the version, the SHA-256 of the package and an Ed25519 signature. The extension only installs an update whose signature matches the release key built into it.
