# @dx-cli-toolbox/sfdx-toolbox-package-utils

Utilities to better manage SalesforceDX Packages

# Contents

<!-- toc -->

- [@dx-cli-toolbox/sfdx-toolbox-package-utils](#dx-cli-toolboxsfdx-toolbox-package-utils)
- [Contents](#contents)
- [Setup](#setup)
- [Commands](#commands)

<!-- tocstop -->

# Setup

### **Install as a SalesforceDX Plugin**

```
sfdx plugins:install @dx-cli-toolbox/sfdx-toolbox-package-utils
```

You will be prompted to confirm that you want to install an unsigned plugin. Choose "yes"

```
This plugin is not digitally signed and its authenticity cannot be verified. Continue installation y/n?: y
```

To whitelist this plugin, [add an entry for it in $HOME/.config/sfdx/unsignedPluginWhiteList.json](https://developer.salesforce.com/blogs/2017/10/salesforce-dx-cli-plugin-update.html).

### **Install from source**

1. Clone the repository

```
git clone https://github.com/ImJohnMDaniel/sfdx-toolbox-package-utils.git
```

2. Link the plugin:

```
sfdx plugins:link .
```

# Commands

<!-- commands -->

<!-- commandsstop -->

# Code
find src -name '*.ts' | xargs wc -l 
      70 src/shared/packageUtils.ts
      25 src/schemas/packageDirs.ts
     453 src/commands/toolbox/package/dependencies/install.ts
     170 src/commands/toolbox/package/version/cleanup.ts
       1 src/index.ts
     719 total
