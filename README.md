# MyPlugin-Template (Single Addon)

Minimal starter template for one standalone Novadesk addon.

## Files
- `MyPlugin.sln` - Visual Studio solution
- `MyPlugin/MyPlugin.vcxproj` - Visual Studio project
- `MyPlugin/main.cpp` - addon entry points and exported API
- `MyPlugin/MyPlugin.rc` / `MyPlugin/resource.h` - version metadata resource
- `NovadeskAPI/novadesk_addon.h` - addon API header
- `NovadeskAddon.props` - common build props

## How to use
1. Open `MyPlugin.sln` in Visual Studio 2019+.
2. Build `Debug|x64` or `Release|x64`.
3. Output DLL will be under `dist\x64\...`.
4. Rename strings in `MyPlugin/main.cpp` and `MyPlugin/MyPlugin.rc` to match your addon name.

## Build from terminal
```powershell
.\Build.ps1
.\Build.ps1 -Configuration Release
```
