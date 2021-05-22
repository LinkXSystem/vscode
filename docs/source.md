# VSCode 源码

## 结构

- 主要源码

```shell
├── bootstrap-amd.js
├── bootstrap-fork.js
├── bootstrap-node.js
├── bootstrap-window.js
├── bootstrap.js
├── buildfile.js
├── cli.js
├── main.js
├── tsconfig.base.json
├── tsconfig.json
├── tsconfig.monaco.json
├── tsconfig.tsec.json
├── tsec.exemptions.json
├── typings
│   ├── require.d.ts
│   └── thenable.d.ts
└── vs
    ├── base
    │   ├── browser
    │   ├── common
    │   ├── node
    │   ├── parts
    │   ├── test
    │   └── worker
    ├── code
    │   ├── browser
    │   ├── buildfile.js
    │   ├── electron-browser
    │   ├── electron-main
    │   ├── electron-sandbox
    │   └── node
    ├── css.build.js
    ├── css.d.ts
    ├── css.js
    ├── editor
    │   ├── browser
    │   ├── common
    │   ├── contrib
    │   ├── editor.all.ts
    │   ├── editor.api.ts
    │   ├── editor.main.ts
    │   ├── editor.worker.ts
    │   ├── standalone
    │   └── test
    ├── loader.js
    ├── monaco.d.ts
    ├── nls.build.js
    ├── nls.d.ts
    ├── nls.js
    ├── nls.mock.ts
    ├── platform
    │   ├── accessibility
    │   ├── actions
    │   ├── backup
    │   ├── browser
    │   ├── checksum
    │   ├── clipboard
    │   ├── commands
    │   ├── configuration
    │   ├── contextkey
    │   ├── contextview
    │   ├── debug
    │   ├── diagnostics
    │   ├── dialogs
    │   ├── download
    │   ├── driver
    │   ├── editor
    │   ├── encryption
    │   ├── environment
    │   ├── extensionManagement
    │   ├── extensionRecommendations
    │   ├── extensions
    │   ├── externalTerminal
    │   ├── files
    │   ├── instantiation
    │   ├── ipc
    │   ├── issue
    │   ├── jsonschemas
    │   ├── keybinding
    │   ├── keyboardLayout
    │   ├── label
    │   ├── launch
    │   ├── layout
    │   ├── lifecycle
    │   ├── list
    │   ├── localizations
    │   ├── log
    │   ├── markers
    │   ├── menubar
    │   ├── native
    │   ├── notification
    │   ├── opener
    │   ├── product
    │   ├── progress
    │   ├── protocol
    │   ├── quickinput
    │   ├── registry
    │   ├── remote
    │   ├── request
    │   ├── serviceMachineId
    │   ├── severityIcon
    │   ├── sharedProcess
    │   ├── sign
    │   ├── state
    │   ├── storage
    │   ├── telemetry
    │   ├── terminal
    │   ├── theme
    │   ├── undoRedo
    │   ├── update
    │   ├── url
    │   ├── userDataSync
    │   ├── webview
    │   ├── windows
    │   ├── workspace
    │   └── workspaces
    ├── vscode.d.ts
    ├── vscode.proposed.d.ts
    └── workbench
        ├── api
        ├── browser
        ├── buildfile.desktop.js
        ├── buildfile.web.js
        ├── common
        ├── contrib
        ├── electron-browser
        ├── electron-sandbox
        ├── services
        ├── test
        ├── workbench.common.main.ts
        ├── workbench.desktop.main.css
        ├── workbench.desktop.main.nls.js
        ├── workbench.desktop.main.ts
        ├── workbench.desktop.sandbox.main.ts
        ├── workbench.sandbox.main.ts
        ├── workbench.web.api.css
        ├── workbench.web.api.nls.js
        ├── workbench.web.api.ts
        └── workbench.web.main.ts
```
