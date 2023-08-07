# Windows Render Dragon Shader Installation Guide

## Table of Contents

* [MaterialBinLoader](#materialbinloader)
* [Vanilla2Deferred](#vanilla2deferred)
* [Manual Installation](#manual-installation)
* [YSS Special Edition](#yss-special-edition)
* [BetterRTX](#betterrtx)

## MaterialBinLoader
MaterialBinLoader is a program that allows you to load the shader file material.bin as a resource pack, similar to the existing HAL engine. On Windows, you can easily use MaterialBinLoader through BetterRenderDragon. First, download the latest version of [BetterRenderDragon](https://github.com/ddf8196/BetterRenderDragon), then unzip the downloaded files. After that, simply run the bat file. MaterialBinLoader is enabled by default in BetterRenderDragon, so you just need to apply the shader that supports MaterialBinLoader as a resource pack.

## Manual Installation

If MaterialBinLoader is not supported, you will need to modify the Minecraft render file directly. Here's how:

1. First, install Bedrock Launcher. Bedrock Launcher allows you to change versions of Minecraft and easily access the game files. Create a new installation by selecting your desired version and then play it. If you haven't changed the file path, the installation will be at `C:\Users\user\AppData\Roaming\.minecraft_bedrock\versions`.
2. Before proceeding, it's recommended to back up the `com.mojang` folder located at `C:\Users\user\AppData\Local\Packages\Microsoft.MinecraftUWP_(varies for each user)\LocalState\games\com.mojang` to prevent data loss.
3. Now, go to the version folder you installed, then navigate to `data\renderer\material`.
4. Replace the `material.bin` shader file with your desired shader file. Make sure to back up the original file before overwriting it (You can use Bedrock Launcher without running it to access this folder).
5. Launch Minecraft, and you will see the applied shader.

If the shader file includes additional resource pack files like `base.mcpack`, apply them together as well.

## YSS Special Edition

YSS Special Edition works only for versions 1.19.40 to 1.19.63. Follow the steps mentioned in the [Manual Installation](#manual-installation) for installing the desired version using Bedrock Launcher. After that, download [RTX2Deferred 1.2.0](https://github.com/ddf8196/BetterRenderDragon/releases/tag/v1.2.0) and run the bat file.

## BetterRTX

For BetterRTX, you can either follow the steps in [Manual Installation](#manual-installation) to directly install the `material.bin` or use the [official installer](https://github.com/BetterRTX/BetterRTX-Installer) provided by BetterRTX. The installer comes in the form of a PowerShell script file (ps1). You can right-click on it and open it with Windows PowerShell with administrator privileges. Alternatively, you can use the PowerShell extension in Vscode to run the script. Before running the installer, make sure that [IObit Unlocker](https://www.iobit.com/en/iobit-unlocker.php) is installed on your system.