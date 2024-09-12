# Module Setup

In the site root, run:

```bash

composer config --json --merge extra.installer-paths '{".vscode/extensions/{$name}": ["type:vscode-extension"]}' && composer config --json --merge extra.installer-types '["vscode-extension"]' && composer config scripts.vscode-setup "VscodeDrupal\\Install::postPackageInstall" && composer require jacerider/vscode-neo && composer vscode-setup

```

# Visual Studio Code Setup

Visit your extensions panel within VSCode and install the "Drupal Extension Pack" and the "Drupal Neo Extension Pack".
