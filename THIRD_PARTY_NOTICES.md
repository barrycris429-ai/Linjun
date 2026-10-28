# Third-party component

## PresentMon 2.6.0 (x64 console)

- Project: https://github.com/GameTechDev/PresentMon
- Release: https://github.com/GameTechDev/PresentMon/releases/tag/v2.6.0
- Original binary: https://github.com/GameTechDev/PresentMon/releases/download/v2.6.0/PresentMon-2.6.0-x64.exe
- SHA-256: `b2a706bc6ad475749e3b7e3409263aa1e6906d45bdcf993f6dbc0f660188f1af`
- License: MIT. The original license is preserved in `third_party/presentmon/LICENSE.txt` and copied to `tools/PresentMon-LICENSE.txt` alongside the application.

LinjunFRAMGLASS launches the unmodified console executable as its internal ETW collector. The full PresentMon GUI, services, drivers, browser runtime, and installer are not installed by this project.

## Inno Setup 7.1.0 (installer builder)

- Project: https://jrsoftware.org/
- Official release: https://github.com/jrsoftware/issrc/releases/tag/is-7_1_0
- The setup/uninstall engine is provided by Inno Setup; its existing copyright notices are retained.
- Copyright (C) 1997-2026 Jordan Russell. Portions Copyright (C) 2000-2026 Martijn Laan.
- The unmodified Inno Setup license is included as `licenses/InnoSetup-LICENSE.txt` in the installed application.
- The compiler and IDE are build-time dependencies, not installed on recipients' computers.
