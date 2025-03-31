# iOS RenderDragon Shader Installation Guide

> [!NOTE]  
> The iOS environment is highly unstable, and shaders may not function properly.

## Table of Contents

- [iOS RenderDragon Shader Installation Guide](#ios-renderdragon-shader-installation-guide)
  - [Table of Contents](#table-of-contents)
  - [IPA Extraction](#ipa-extraction)
  - [Using Filza](#using-filza)
  - [IPA Sideload](#ipa-sideload)

## IPA Extraction
To install RenderDragon shaders, you need to modify Minecraft's render files.  
To do this, you must extract Minecraft as an IPA file and reinstall it, which requires a PC.  
(If your device is jailbroken, it is recommended to use Filza. See [Using Filza](#using-filza))

On Windows, you can use iMazing to extract the IPA file.  
First, install [iMazing](https://imazing.com/?gad=1&gclid=Cj0KCQjwoK2mBhDzARIsADGbjeoNt1rkkKWWJVaawEFnsUmV3QjthBa3UjxAL7h_cefyqWyxDuxRis8aAvGIEALw_wcB).  
Then, connect your iPhone to the PC via USB.  
Once iMazing is installed, go to "Manage Apps."  
Right-click Minecraft in the Manage Apps list and select "Export .IPA."  
(Note: the Korean translation in the program may be incorrect.)  

After extracting the IPA file, open it using an archive program such as Bandizip.  
Navigate to:
```
Payload\minecraft.app\data\renderer\materials
```
Then, overwrite the `material.bin` shader file with the downloaded one.  
Finally, reinstall Minecraft via Sideload.

## Using Filza
First, install [Filza](https://filzadownload.com/).  
(If your device is not jailbroken, you'll need to sideload it using a PC.)  

Once Filza is installed, back up the `materials` folder found at:
```
var\containers\Bundle\Application\Minecraft\minecraftpe.app\data\renderer\materials
```
Then, copy the downloaded RenderDragon shader file and overwrite the existing `material.bin` file in the same folder.

## IPA Sideload
If your device is not jailbroken, you need to sideload the IPA using a PC.  
You can use one of the following sideload programs:

* [AltStore](https://altstore.io)  
* [Sideloadly](https://sideloadly.io)

If your iOS version is 14.0 or higher, [TrollStore](https://github.com/opa334/TrollStore) is required.

