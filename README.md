# SKUnityPackages

The repo has these packages :
- [Core](https://github.com/FoxsterDev/SKTools) - Core Editor UI elements on ImGUI + essential utilities to simplify routine
- [EditorCoroutine](https://github.com/FoxsterDev/SKTools.EditorCoroutine) - allow you to run coroutine in Editor + attach progress bar.
- [MenuItemsFinder](https://github.com/FoxsterDev/SKTools.MenuItemsFinder) - has a dependence on [Core], to collect all menuitems in one place and override them by new hotkeys
- [ScriptingDefineManager](https://github.com/FoxsterDev/SKTools.ScriptingDefineManager) - easily save and manage groups of scripting define symbols in player settings

also there is a [Sample project](https://github.com/FoxsterDev/SKSample) to test installations these packages from Unity package manager and differen version Unity editor


### Installation

*Requires Unity 2020.3+*

### Install via UPM (using Git URL)

1. Navigate to your project's Packages folder and open the manifest.json file.
2. Add this line below the "dependencies": { line
    - ```json title="Packages/manifest.json"
      "com.foxsterdev.sktools": "https://github.com/FoxsterDev/SKUnityPackages.git?path=Assets/SKTools#1.0.0",
      ```
3. UPM should now install the package.

## Known issues with UPM

#More about UPM

## [Git dependencies](https://docs.unity3d.com/Manual/upm-git.html)

Syntax:	URL example
Latest default branch	"https://github.example.com/myuser/myrepository.git"
Specific branch	"https://github.example.com/myuser/myrepository.git#my-branch"
Specific version	"https://github.example.com/myuser/myrepository.git#v2.0.0"
Commit hash	"https://github.example.com/myuser/myrepository.git#9e72f9d5a6a3dadc38d813d8399e1b0e86781a49"