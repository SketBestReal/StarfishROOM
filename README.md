# Starfish ROOM — Official Community Modding & Project Guide

Welcome to the Starfish ROOM project repository!

This guide explains how to download the project, open it in the official GDevelop 5 editor, make changes, export builds, and share compatible community projects or mods.

> **Important:** This repository contains editable project files, not necessarily ready-to-play builds for every platform. Open the GDevelop project and export a build for your target platform.

## Contents
- [About the project](#about-the-project)
- [Requirements](#requirements)
- [1. Download the repository](#1-download-the-repository)
- [2. Open it in GDevelop 5](#2-open-it-in-gdevelop-5)
- [3. Modify the project](#3-modify-the-project)
- [4. Export or rebuild the game](#4-export-or-rebuild-the-game)
- [5. Publish on mod.io](#5-publish-on-modio)
- [6. Share elsewhere](#6-share-elsewhere)
- [Credits, permissions and safety](#credits-permissions-and-safety)

## About the project

**Starfish ROOM: WELCOME TO LOOP ETERNAL** is an arcade action game made with GDevelop 5.

Community-made versions are not automatically official releases. Clearly identify your work as a fan-made or modified version.

## Requirements

- The official GDevelop editor: <https://gdevelop.io/download>
- A computer is recommended for editing and exporting.
- Git is optional; you can also download the repository as a ZIP.

Browser editor: <https://editor.gdevelop.io/>

## 1. Download the repository

### Option A — Download ZIP (no Git required)

1. Visit <https://github.com/SketBestReal/StarfishROOM>.
2. Click **Code**.
3. Choose **Download ZIP**.
4. Extract the ZIP to a folder.
5. Keep the folder structure intact.

### Option B — Clone with Git

```bash
git clone https://github.com/SketBestReal/StarfishROOM.git
```

To get later updates:

```bash
cd StarfishROOM
git pull
```

Back up your modified work before pulling updates. Git may report conflicts if both versions changed the same files.

## 2. Open it in GDevelop 5

1. Install and launch the official GDevelop editor.
2. Choose **Open a project**.
3. Browse to the extracted or cloned repository folder.
4. Select the GDevelop project file (normally a `.json` file).
5. Wait for the project and its resources to load.
6. Use **Preview** to test it.

If you cannot find the project file, search the folder for `.json` files. Do not open an exported `index.html` or compiled executable when your goal is to edit the source project.

**Tip:** Make a backup copy before editing.

## 3. Modify the project

GDevelop lets you inspect and modify scenes, objects, events, behaviors, animations, and resources.

Good practices:
- Keep an untouched backup of the original project.
- Give your modified version its own name and version number.
- Track which files you changed.
- Test after significant changes.
- Do not use third-party assets or code unless their licenses allow it.

A modified full project may need to be rebuilt as a complete game. It is not automatically a plug-and-play in-game mod; that depends on the game's mod-loading structure.

## 4. Export or rebuild the game

Open the project in GDevelop and use its export/publishing options. Menu labels can vary between editor versions.

| Target | Typical output |
|---|---|
| Web | HTML5 game folder |
| Windows | Desktop application/package |
| Linux | Desktop application/package, such as an AppImage |
| macOS | macOS application/package |
| Android | Android build/package |
| iOS | iOS build prepared for Apple's build and signing requirements |

Platform availability and build requirements depend on your GDevelop version, account, operating system, and required tools. Exporting does not guarantee compatibility with every device or OS version. Test the build on its target platform before distributing it.

Official guides:
- Publishing overview: <https://wiki.gdevelop.io/gdevelop5/publishing/>
- Windows, macOS and Linux: <https://wiki.gdevelop.io/gdevelop5/publishing/windows-macos-linux/>
- Manual desktop export with Electron: <https://wiki.gdevelop.io/gdevelop5/publishing/windows-macos-linux-with-electron/>
- HTML5 export: <https://wiki.gdevelop.io/gdevelop5/publishing/html5_game_in_a_local_folder/>

For Steam or mobile stores, also follow the store's packaging, signing, review, and submission requirements.

## 5. Publish on mod.io

You can use mod.io to host and organize community-created content. **A game does not need an in-game mod browser merely for creators to upload files to a mod.io game page**, provided that the game page allows submissions.

Before uploading:
1. Check whether a Starfish ROOM game page exists on mod.io.
2. Read its submission rules and the permissions that apply to this repository.
3. Prepare and test your mod.
4. Create a ZIP containing the files required by that mod.
5. Add a clear description, version number, installation instructions, and credits.
6. Submit through the mod.io website if community submissions are enabled.

Official mod.io documentation:
- Documentation: <https://docs.mod.io/>
- REST API introduction: <https://docs.mod.io/restapi/introduction>
- Upload a mod file: <https://docs.mod.io/restapi/docs/add-modfile>
- Upload a source mod file: <https://docs.mod.io/restapi/docs/add-source-modfile>

### Do I need the mod.io API?

**Not just to host a mod on the website.** API integration is relevant when the game or an external tool needs to automate mod discovery, uploads, downloads, authentication, or other mod.io operations.

### What should I upload?

- **Mod/release package:** files players need to install or use the modification, in the structure required by the game.
- **Source package:** editable source files, when you intend to share them and have permission.

Do not assume that uploading the entire GDevelop project makes it installable as an ordinary in-game mod. Unless the game has a defined mod-loading system, describe a rebuilt modified project as a **standalone fan build**.

## 6. Share elsewhere

Depending on the file format and each site's rules, you may share your work through:
- **GitHub:** project files, source, documentation, and version history.
- **itch.io:** downloadable builds, prototypes, and standalone fan projects.
- **Game Jolt:** game builds and community projects.
- **Your own website or file host:** downloads and documentation.
- **Other mod platforms:** only when their rules and the game's permissions allow it.

Always state which Starfish ROOM version your work is based on and include installation instructions.

## Troubleshooting

**GDevelop does not show the project**
- Extract the ZIP first.
- Look for the GDevelop project `.json` file.
- Open that file from inside GDevelop.
- Do not select an executable or exported `index.html` to edit the source.

**Missing resources**
- Preserve the original folder structure.
- Re-download the repository if files were moved or deleted.
- Check whether required resources are stored outside the repository.

**The exported build does not start**
- Test the project in GDevelop Preview first.
- Export again for the correct operating system.
- Consult the official platform guide and test on the target device.

**Git reports conflicts**
- Back up modified files before merging.
- If you are unfamiliar with Git, download a fresh ZIP into a separate folder rather than overwriting your working copy.

## Credits, permissions and safety

- **Game:** Starfish ROOM: WELCOME TO LOOP ETERNAL
- **Original creator:** SketBR
- **Game page:** <https://kittycreampuff.itch.io/starfish-room-final>
- **Creator:** <https://x.com/sketBR>
- **GitHub repository:** <https://github.com/SketBestReal/StarfishROOM>

Please credit the original project when sharing derivative work. Do not claim a fan-made build is an official release.

**License notice:** Unless this repository contains a `LICENSE` file that explicitly grants reuse rights, public visibility on GitHub does not automatically grant permission to redistribute, modify, or commercially use every included asset or file. Check applicable licenses and obtain permission where necessary before publishing derivative work or uploading it to third-party services.

Never upload passwords, access tokens, private keys, or personal information to GitHub or mod.io.

---

*Platform export options and third-party submission rules may change. Check the official documentation linked above before publishing.*
