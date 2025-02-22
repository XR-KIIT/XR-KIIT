
# Extended Reality KIIT

This account will be the joint directory for XR projects and Game Development projects at KIIT. 


## Authors

These repositories are created and used by the following entities:

- [@Uday N. Chakraborty](https://www.github.com/uday-nc)
- [@G K Prudhvi Raj](https://www.github.com/PrudhviRajGK)
- [@Archi Kanungo](https://www.github.com/archiik04)
- [@Aditya Vishwakarma](https://www.github.com/XR-KIIT)

## Tech Stack

**Engine:** Unity, Unreal, Godot

**Web Frameworks:** ThreeJS, A-Frame, HTML, CSS, JS 

**Augmented Reality:** MindAR, ARFoundation, Zappar, Vuforia, Niantic

**Virtual Reality:** OpenXR, MetaXR, Oculus XR, Meta SDK, MRTK


## Deployment

### Unity Project

#### Clone Repository
```bash
git clone https://github.com/username/project-name.git
cd project-name
```

#### Setup & Run in Unity
    1. Open Unity Hub
    2. Click "Add" button
    3. Browse to cloned repository folder
    4. Select the project folder (containing Assets folder)
    5. Select appropriate Unity version (check  README or ProjectSettings/ProjectVersion.txt)
    6. Click the project to open

#### Alternative Setup (Command Line)
```bash
# On Windows
"C:\Program Files\Unity\Hub\Editor\2022.3.17f1\Editor\Unity.exe" -projectPath "C:\path\to\cloned\repo"

# On macOS
/Applications/Unity/Hub/Editor/2022.3.17f1/Unity.app/Contents/MacOS/Unity -projectPath /path/to/cloned/repo
```

#### Common Issues
- If using Git LFS: Run `git lfs pull` to download large assets
- Missing .meta files: Enable visible meta files in project settings
- Different Unity version: Install required version via Unity Hub

### Unreal Engine Project

#### Clone Repository
```bash
git clone https://github.com/username/project-name.git
cd project-name
```

#### Setup & Run
    1. Locate the .uproject file in the cloned directory
    2. Right-click the .uproject file and select "Generate Visual Studio project files" (Windows)
    3. Double-click the .uproject file to open in Unreal Engine

#### Command Line Setup
```bash
# Generate project files (Windows)
"C:\Program Files\Epic Games\UE_5.2\Engine\Binaries\DotNET\UnrealBuildTool\UnrealBuildTool.exe" -projectfiles -project="C:\path\to\cloned\repo\ProjectName.uproject" -game -engine

# Launch project (Windows)
"C:\Program Files\Epic Games\UE_5.2\Engine\Binaries\Win64\UnrealEditor.exe" "C:\path\to\cloned\repo\ProjectName.uproject"

# Launch project (macOS)
open /path/to/cloned/repo/ProjectName.uproject
```

#### Large Repository Setup
If repo uses Git LFS:
```bash
git lfs install
git lfs pull
```

#### Rebuilding Modules
If C++ code exists:
```bash
# Windows
"C:\Program Files\Epic Games\UE_5.2\Engine\Build\BatchFiles\Build.bat" ProjectNameEditor Win64 Development "C:\path\to\cloned\repo\ProjectName.uproject"

# macOS/Linux
/path/to/UE_5.2/Engine/Build/BatchFiles/Mac/Build.sh ProjectNameEditor Mac Development /path/to/cloned/repo/ProjectName.uproject
```

### Godot Project

#### Clone Repository
```bash
git clone https://github.com/username/project-name.git
cd project-name
```

#### Setup & Run
    1. Open Godot Engine
    2. Click "Import" in the Project Manager
    3. Browse to the cloned repository folder
    4. Locate and select the project.godot file
    5. Click "Import & Edit"

#### Command Line Launch
```bash
# Windows
"C:\Program Files\Godot\Godot_v4.2.exe" --path "C:\path\to\cloned\repo"

# macOS
/Applications/Godot.app/Contents/MacOS/Godot --path /path/to/cloned/repo

# Linux
godot --path /path/to/cloned/repo
```

#### Version-Specific Issues
- Godot 3.x project won't open in Godot 4.x (not backward compatible)
- Check project's required Godot version in README or project.godot file

#### Git LFS Support
If repository uses Git LFS:
```bash
git lfs install
git lfs pull
```

#### Import Errors
If assets fail to import:
```bash
# Force reimport all resources
godot --path /path/to/cloned/repo --reimport-all
```
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to all the project's `code of conduct`.


## Acknowledgements

 - [MLSA KIIT Chapter](https://mlsakiit.com/)
 - [Unity Engine](https://unity.com/)
 - [Unreal Engine](https://www.unrealengine.com/en-US)

