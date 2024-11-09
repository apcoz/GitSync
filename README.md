# **LiveLink: Real-Time Sync for ROBLOX Studio**

LiveLink is a real-time sync tool designed for ROBLOX developers seeking seamless integration between their code editor and ROBLOX Studio. With LiveLink, changes made to scripts, modules, and assets in a GitHub repository are instantly reflected in ROBLOX Studio without needing to enter Play mode. Designed to enhance productivity and streamline collaboration, LiveLink bridges the gap between your codebase and the ROBLOX engine.

## Features

- **Automatic Sync**: Instantly updates scripts, modules, and folders directly in ROBLOX Studio as you edit files in your repository.
- **Custom Folder Mapping**: Supports structured folder mapping with separate directories for client and server scripts.
- **Flexible Naming Conventions**: Recognizes script types based on file naming (e.g., `local.<name>.luau`, `module.<name>.luau`), making organization easy.
- **Lightweight and Fast**: Runs in the background with minimal setup and system impact.

## How to Create and Name Items

To ensure your files sync correctly in ROBLOX Studio, use the following naming conventions:

- **Folder**: Create a folder with any name, like `folder.<name>`, to organize scripts and modules.
- **Local Script**: Name the local script `local.<name>.luau`, where `<name>` can be anything, to identify it as a local script.
- **Script**: Name the script `script.<name>.luau`, where `<name>` can be anything, for regular server scripts.
- **Module Script**: Name the module script `module.<name>.luau`, where `<name>` can be anything, for module scripts.

Whether you’re a solo developer or part of a team, LiveLink provides a robust, real-time connection between your code editor and ROBLOX Studio, keeping your workflow efficient and your game scripts up-to-date.
