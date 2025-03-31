# Manual Installation of RenderDragon Shaders on Android

This process requires reinstalling Minecraft, so please make sure to [back up your data](#backup) first.  

1. First, install [APKtool](https://maximoff.su/apktool/?lang=en).
2. In APKtool, go to the **Application** tab at the top, select Minecraft under 'Installed Applications', and choose Antisplit.
3. In Antisplit, select "Use aapt2" and under "Select a signature file", choose "Don't sign".
4. APK extraction will begin after this. It may take some time.  
   It can run in the background, so you may use other apps as long as you don’t close APKtool or turn off the phone.
5. Once extraction is complete, go to the [MT Manager](https://mt2.cn/download) download page.
6. Click the blue text **本地下载** on the download page to download the MT Manager APK file.
> [!NOTE]
> During the installation process, MT Manager might be flagged as a potentially dangerous app and show a warning or fail to install.  
> This is because MT Manager is a comprehensive tool made in China for modding apps on phones, which requires many permissions. It is safe to install.

7. After installing MT Manager, open `APKtool_M` folder in one tab, and in the other tab, open the shader file you downloaded.  
(If the file is in `.mcpack` format, open it with Archive Viewer, then navigate to the `renderer/materials` folder to find the shader files.)
8. In the `APKtool_M` folder, tap the APK file and choose VIEW.
9. Once the APK opens, navigate to the `assets/renderer/materials` folder.
10. Long press the `.material.bin` file from the shader folder, tap the **+Add** button, check the AUTO SIGN box, and then tap OK.
11. Repeat this process for all `.material.bin` files in the shader folder.  
12. After adding all files, go back, select the APK again, and go to the FUNCTION menu.
13. Select **APK Sign** and press OK.
14. Now, install the signed APK. You will see the shaders applied in-game.

[Video Tutorial](https://youtu.be/MYlnjqnFBgw?si=uE6-c8qUwx2cjUAn)

---

## Backup

Minecraft save data is stored in:  
```
0\Android\data\com.mojang.minecraftpe
```

You cannot access folders beyond Android/data with regular file explorers. You need a file explorer that can access these folders.  
You can use `MT Manager` mentioned in step 6 to access this path.

If you already have a capable file explorer, you can temporarily move the `files` folder under `com.mojang.minecraftpe` to another location.  
Note: If you just installed Minecraft, the `files` folder may be empty.

On some specific devices or Android versions, it may be completely impossible to access `Android/data` from the phone itself.  
In such cases, you must connect your device to a PC using a USB-C to USB cable and access the `com.mojang.minecraftpe` folder from the PC.
