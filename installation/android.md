# Android Render Dragon Shader Installation Guide

## Table of Contents
* [MaterialBinLoader](#materialbinloader)
* [Manual Installation](#manual-installation)
* [Backup](#backup)

## MaterialBinLoader

MaterialBinLoader is a program that allows you to load the shader file material.bin as a resource pack, similar to the existing HAL engine. While you can modify the Minecraft APK file and install it directly, it is more convenient to install the APK of the Patched APP prepared in advance by developer [@ENDERMANYK](https://github.com/ENDERMANYK). You can download the Patched APP from this location: [Patched APP](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/patchedapp.md).

If your existing Minecraft version is lower than the Patched APP version due to not having updated yet, you can simply install the APK and update it. However, if the Patched APP version is lower or the same as your current Minecraft version, you must first remove the existing Minecraft and then install the Patched APP. Therefore, it is essential to [back up](#백업) your Minecraft before the removal process.

## Manual Installation

If MaterialBinLoader is not supported, you will need to modify the Minecraft render file directly. During this process, reinstalling Minecraft will be necessary, so please make sure to [back up](#백업) your Minecraft before proceeding.

To modify the Minecraft render file, you will need Apktool M and MT Manager. Here's a step-by-step guide:

1. First, install [APKtool](https://maximoff.su/apktool/?lang=en).
2. Open APKtool and go to the Application tab. Then, select Minecraft from the Installed Applications list and choose "Antisplit."
3. Enable "Use aapt2" and select "Don't sign" under "Select a signature file."
4. The APK extraction process may take some time. You can use other apps on your phone or leave APKtool running in the background without closing it.

Once the installation of APKtool is complete, proceed with the following steps:

5. Install [MT Manager](https://mt2.cn/download) by clicking on the blue 本地下载 (Local Download) link on the website.
6. Open MT Manager and open the APKtool_M folder on one side and the downloaded shader file on the other side.
7. Press on the Anti-Split APK file in the APKtool_M folder and click on VIEW.
8. Navigate to assets/rnderer/materials to find the material.bin file in the shader folder.
9. Long-press the material.bin file, click on the +Add button, and check the AUTO SIGN checkbox before clicking OK.
10. If there are multiple material.bin files, repeat the same process for each of them.
11. Go back to the previous menu, select the APK file again, and go to FUNCTION.
12. Choose APK Sign and click OK.
13. Now, you can install the modified APK, and you will see the shaders applied in-game.

If there are additional files like base.mcpack accompanying the shader file, follow these steps:

14. Select the base.mcpack file and click on TYPE at the bottom left. Choose ALL, then select Minecraft to open it.
15. Once the resource pack is loaded, apply the resource pack, and the process will be complete.

For a visual guide, you can refer to this [video tutorial](https://youtu.be/MYlnjqnFBgw).
<!---
The provided links are subject to change or may be in a different language, as this is a translation. Please use similar guides in your preferred language if necessary.
--->

## Backup

For Minecraft saved data, it is stored in the following directory:

```
0\Android\data\com.mojang.minecraftpe
```

However, accessing folders beyond Android/data is not possible using a regular file explorer. You will need to install a file explorer that allows access to these folders. [MT Manager](https://mt2.cn/download) is recommended for this purpose. You can download it by clicking on the 本地下载 (Local Download) link on the website.

Once you have a file explorer that allows access to these folders:

1. Navigate to `com.mojang.minecraftpe` and locate the `files` folder.
2. Temporarily move the `files` folder to a different location to create a backup. Please note that if you recently installed Minecraft, the `files` folder might be empty.

In some specific device models or Android versions, access to the Android/data folder might be entirely restricted within the phone's filesystem. In such cases, you will need to connect your phone to a PC via USB or another method to access the `com.mojang.minecraftpe` folder and create a backup.