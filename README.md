# XMod

## About

XMod is a physics sandbox game where you can build anything you can imagine.

## Getting Started

1. Download the latest release from [itch.io](https://oramix.itch.io/xmod)
2. Extract the archive
3. Run the executable (`.exe` on Windows or `.x86_64` on Linux)

> **Linux:** Before running, mark the game file as an executable.
> **Note:** macOS is not supported.

## Modding

XMod supports community mods.

Place mods in the following folder:

- **Windows:** `C:\Users\%USER%\AppData\LocalLow\OramiX\XMod\Mods`
- **Linux:** `/home/<user>/.config/unity3d/OramiX/XMod/Mods`

> **Note:** These folders are hidden by default.
> On Linux, press `Ctrl + H` to show hidden files.
> On Windows, enable **Show hidden files** in Folder Options.

## Building from Source

### Requirements

- Unity **2022.3.62f3** (exactly this version)

### Steps

1. Clone the repository:
   git clone https://github.com/OramicGIT/XMod-repo.git
2. Prepare the project
3. Create a new Unity project, then replace the Assets, Packages and ProjectSettings with unpacked folders, and remove the Library and Temp folder before starting Unity again.
4. Open the final project in Unity.
5. Open the main scene (`Menu`) and hit **Play** to test, or build via **File → Build Settings**

## Contributing

Contributions are welcome! Feel free to open an issue!

- [GitHub Pages](https://oramicgit.github.io/XMod)
- [itch.io](https://oramix.itch.io/xmod)
