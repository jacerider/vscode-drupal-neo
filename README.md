# Setup

In the site root, run:

```bash

composer config --json --merge extra.installer-paths '{".vscode/extensions/{$name}": ["type:vscode-extension"]}' && composer config scripts.vscode-setup "vscode_drupal\\Vscode::postPackageInstall" && composer require jacerider/vscode-neo && composer vscode-setup

```
