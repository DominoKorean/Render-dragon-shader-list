# Android Render Dragon Shader Installation Guide [WIP]

## Table of Contents
- [Android Render Dragon Shader Installation Guide](#android-render-dragon-shader-installation-guide)
  - [Table of Contents](#table-of-contents)
  - [MaterialBinLoader](#materialbinloader)
  - [Manual Installation](#manual-installation)
  - [Backup](#backup)

## MaterialBinLoader

MaterialBinLoader is a program that allows you to load the shader file material.bin as a resource pack, similar to the existing HAL engine. While you can modify the Minecraft APK file and install it directly, it is more convenient to install the APK of the Patched APP prepared in advance by developer [@ENDERMANYK](https://github.com/ENDERMANYK). You can download the Patched APP from this location: [Patched APP](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/patchedapp.md).

~~If your phone uses 32-bit, it may not work. Check the model of your phone and install the Patched APP.~~
Starting from 1.20.51 Minecraft Patched also supports 32 bit along 64 bit Androids. Check which one your devices supports using [64Bit Checker](https://play.google.com/store/apps/details?id=com.danielpolish.a64bitchecker) by [DanielPolish](https://play.google.com/store/apps/dev?id=8043830287709235004).
Also, the creator of PatchApp also provides combined 32+64 bit apk. Means if the apk you're downloading says arm32+arm64 something like that then it should work fine on your device.

## Manual Installation

If MaterialBinLoader is not supported, you will need to modify Minecraft apk yourself to directly replace shader files. During this process, reinstalling Minecraft will be necessary, so please make sure to [back up](#backup) your Minecraft before proceeding.

To replace shader files in Minecraft APK, you will need Apktool M and [MT Manager](https://mt2.cn/download/). Here's a step-by-step guide:

0. Backup your Minecraft APK using SAI [[Play Store]](https://play.google.com/store/apps/details?id=com.aefyr.sai) [[GitHub]](https://github.com/Aefyr/SAI/releases/latest)
1. First, install [APKtool](https://maximoff.su/apktool/?lang=en).
2. Open APKtool and go to the Application tab. Then, select Minecraft from the Installed Applications list and choose "Antisplit."
3. Enable "Use aapt2" and select "Don't sign" under "Select a signature file."
4. The APK extraction process may take some time. You can use other apps on your phone or leave APKtool running in the background without closing it.

Once the installation of APKtool is complete, proceed with the following steps:

5. Install [MT Manager](https://mt2.cn/download) by clicking on the blue 本地下载 (Local Download) link on the website.
6. Open MT Manager and open the APKtool_M folder on one side and the downloaded shader file on the other side.
7. Press on the Anti-Split APK file in the APKtool_M folder and click on VIEW.
8. Navigate to assets/assets/renderer/materials to find the material.bin file in the shader folder.
9. Long-press the material.bin file, click on the +Add button, and check the AUTO SIGN checkbox before clicking OK.
10. If there are multiple material.bin files, instead of signing each time, slide one bin and then select all others by clicking, then hold and do the same as before. Make sure to have Auto Sign ticked.
11. Go back to the previous menu, select the APK file again, and go to FUNCTION.
12. Choose APK Sign and click OK.
> **NOTE:** Signing again isn't required if you use auto sign during the process. (11-12)
13. Now, you can install the modified APK, and you will see the shaders applied in-game.

If there are additional files like base.mcpack accompanying the shader file, follow these steps:

14. Select the base.mcpack file and click on TYPE at the bottom left. Choose ALL, then select Minecraft to open it.
15. Once the resource pack is loaded, apply the resource pack, and the process will be complete.

For a visual guide, you can refer to this [video tutorial](https://youtu.be/MYlnjqnFBgw).
<!---
The provided links are subject to change or may be in a different language, as this is a translation. Please use similar guides in your preferred language if necessary.
--->

## Backup

If you have set data location to **External** in the game then the files will be available in: 

```
0\Android\data\com.mojang.minecraftpe\files
```

If you have set data location to **Application** in the game then the files will be available in:

```
/data/data/com.mojang.minecraftpe/files
```
**Note** Accessing anything in /data/data requires root access. If you don't have root access you take help of this [resource pack](https://llama-studios.github.io/mobile-export/) instead.

However, accessing folders beyond Android/data is not possible using a regular file explorer (Starting from Android 11). You will need to install a file explorer that allows access to these folders. [MT Manager](https://mt2.cn/download) is recommended for this purpose. You can download it by clicking on the 本地下载 (Local Download) link on the website. You may also need Shizuku to grant access to these folders. [[Play Store]](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) [[GitHub]](https://github.com/RikkaApps/Shizuku/releases/latest) [[Shizuku Usage Video]](https://www.youtube.com/shorts/IivUG_itU2Y)

Once you have a file explorer that allows access to these folders:

1. Navigate to `com.mojang.minecraftpe` and locate the `files` folder.
2. Temporarily move the `files` folder to a different location to create a backup. Please note that if you recently installed Minecraft, the `files` folder might be empty.

In some specific device models or Android versions, access to the Android/data folder might be entirely restricted within the phone's filesystem. In such cases, you will need to connect your phone to a PC via USB or another method to access the `com.mojang.minecraftpe` folder and create a backup.
