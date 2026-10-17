VMCPCSS — binary distributions
=============================

Download the VMCPCSS installer .unitypackage from Releases.
This repository contains distribution documentation and binary releases only.
The implementation source is maintained separately in a private repository.
GitHub-generated source archives for this repository contain documentation only.

Requirements: Unity 2022.3 LTS and lilToon (install separately).
Tested with Unity 2022.3.22f1 and lilToon 2.3.2.

Installation:
1. Install lilToon in a new Unity 2022.3 project.
2. Import VMCPCSS-Installer-v0.1.0-preview.1.unitypackage.
3. Wait for Unity to import and compile. The installer extracts the tool DLLs,
   runtime DLL and embedded shaders into Assets/VMCPCSS.
4. Open VMC PCSS > Setup Window.
If lilToon was missing, install it and use VMC PCSS > Installer > Install / Verify.

The package installs VMCPCSS.Installer.dll into Assets/Editor with Editor-only
plugin settings. Existing source-based installations are blocked; use a clean
project. Source-to-DLL scene migration is not provided in this preview.
VMCReplaceAvatar, VMCSpout, PhysicsConverter and avatar assets are not included.
VMC export requires compatible separately installed mod/exporter integration.

The DLL contains embedded shader text needed by Unity. Compiled DLLs can be
inspected/decompiled; keeping the source repository private is not encryption.

SimpleAvatarMeshBaker source and its package:
https://github.com/emirumilk3dsrc-pixel/SimpleAvatarMeshBaker
