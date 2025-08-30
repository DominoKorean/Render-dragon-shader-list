# How to Install RenderDragon Shaders

This document explains how to install RenderDragon shaders.

- [Back to RenderDragon Shader List](/README.md)

<br>

> [!NOTE]
> If you want real-time shadows, reflections of surrounding objects on water and iron blocks, and dynamic colored lighting, what you're looking for is not the RenderDragon shader, but **Vibrant Visuals (Deferred Rendering)**.

> What is the difference between the RenderDragon shader and Vibrant Visuals?  
> How do I apply Vibrant Visuals?  
> > [Instructions and Explanation for Applying Vibrant Visuals](/docs/virbrant_visuals.md)

<br>

> [!NOTE]
> Most utility mods that allow loading RenderDragon shaders from resource packs may not work until they are updated to support the latest version of Minecraft.
>
> If shaders stop working after a Minecraft update, it is recommended to wait until the mod you are using is updated.

<br>

## Mobile

### Android

> Most phones except for Apple devices—such as Samsung Galaxy, Xiaomi, and Google Pixel—use Android.

1. Install [MB Loader](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/README.md#mb-loader).
2. Press the `Load to mbl2` button to launch the currently installed version of Minecraft.
3. Download a shader pack from the Renderdragon Shader List and load it as a resource pack, then apply it under **Global Resources**.

<br>

#### Using the LeviLaunchroid Mod

Mods that support `.so` files, such as BetterRenderdragon, can be launched using LeviLaunchroid.

1. Install the [LeviLaunchroid](https://github.com/LiteLDev/LeviLaunchroid/releases) APK
2. Download a mod labeled with the `SO` tag from the [Render Dragon Shader Mod / Utilities](https://github.com/DominoKorean/Render-dragon-shader-list?tab=readme-ov-file#render-dragon-shader-mod--utilities) section that is provided as a `.so` file
3. Open LeviLaunchroid, go to the Mods panel in the bottom-left corner, click the `+` button, and select the `.so` mod file using the file explorer
4. Press the `Launch` button to run Minecraft with the mod applied to your currently installed version

> [!NOTE]
> Each mod may be incompatible with other mods.


<br>

If you want to manually modify the APK and apply shaders, refer to the following document:
* [Manual Installation Guide](android.md)

<br>
<br>

### iOS

> For iPhone and iPad, please refer to this document.

* [RenderDragon Shader Installation on iOS](iOS.md)

<br>
<br>

## PC

### Windows

1. Download the latest version from the [BetterRenderDragon](https://github.com/QYCottage/BetterRenderDragon/releases) Releases page.
2. Extract the `BetterRenderDragon.zip` file and run `mcbe_injector.exe`.
3. Download a shader pack from the Renderdragon Shader List, load it as a resource pack, and apply it as a **global resource**.

> [!NOTE]
> Since Windows and Chrome may detect `mcbe_injector.exe` as a virus, you will need to temporarily disable Chrome's real-time security and Windows Defender's real-time protection.
> The detection is triggered by the executable file used to run the mod, not by the mod file itself — the mod file is safe.
> If Windows Defender's real-time protection is not disabled, `mcbe_injector.exe` may still be deleted even after extracting the ZIP file. In that case, you can prevent this by using [Fzul's BRD Updater Script](https://github.com/faizul726/brd-updater-script).

<br>

### Using DLL Mod Files

You can use DLL-format mod files through **mc-w10-version-launcher**.

1. Download the latest version of [mc-w10-version-launcher](https://github.com/QYCottage/mc-w10-version-launcher/releases).
2. Extract the ZIP file and run `MCLauncher.exe`.
3. Download the desired Minecraft version.
4. Download a mod labeled with the `DLL` tag from the [RenderDragon Shader Mods / Utilities](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/language/ko_kr/README.md#%EB%A0%8C%EB%8D%94%EB%93%9C%EB%9E%98%EA%B3%A4-%EC%85%B0%EC%9D%B4%EB%8D%94-%EB%AA%A8%EB%93%9C--%EC%9C%A0%ED%8B%B8%EB%A6%AC%ED%8B%B0) section.
5. Place the downloaded `.dll` mod file in the following folder inside the extracted directory:
   `imported_versions\Microsoft.MinecraftUWP "version__package name".Appx\mods`
   Then relaunch `MCLauncher.exe` and start Minecraft.
6. Download a shader pack from the Renderdragon Shader List, load it as a resource pack, and apply it as a **global resource**.

<br>

### Manual Installation

You can manually replace the `material.bin` file using [IObit Unlocker](https://www.iobit.com/en/iobit-unlocker.php).
After extracting the resource pack, you can find the `material.bin` file in the following path:

```
🖼️ pack_icon.png
🗒️ manifest.json
📁 renderer
    ↳ 📁 materials
        ↳  .material.bin
```

In vanilla Bedrock Minecraft, the `.material.bin` can be found at:

```
C:\Program Files\WindowsApps\Microsoft.MinecraftUWP_1.21.9401.0_x64__8wekyb3d8bbwe\data\renderer\materials
```

<br>
<br>

## Troubleshooting

> - **Only the water or sky in the shader pack is applied, or those effects are missing.**  
> Restarting Minecraft usually solves the problem.

> - **Shaders do not work when I join a server.**  
> Shaders may not function properly on servers due to server resource packs.

> - **Shaders don’t work when I apply them to a map.**  
> Please make sure to apply them via Global Resources.

> - **I used a mod app on mobile, and now my worlds, resource packs, and other data seem to be missing.**  
> Your data hasn't been deleted. MB Loader and LeviLaunchroid use a different storage location than the default Minecraft, so if you open the official Minecraft app again, you'll see that your files are still there.


> [!NOTE]  
> For issues or bugs not listed above, please contact the shader developer.

---

* [Back to English](/docs/installation/README.md)
