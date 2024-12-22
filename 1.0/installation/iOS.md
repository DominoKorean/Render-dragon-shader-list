# iOS Render Dragon Shader Installation Guide

## Table of Contents

* [Extract IPA](#extract-ipa)
* [Using Filza](#using-filza)
* [IPA Sideload](#ipa-sideload)

## Extract IPA
To install Render Dragon shaders, you need to modify the Minecraft render file. This requires extracting Minecraft as an IPA, installing it again, and for this, you will need a PC. (If your device is jailbroken, we recommend using Filza. [Using Filza](#using-filza))

On Windows, you can use iMazing for IPA extraction. Here's how:

1. First, install [iMazing](https://imazing.com/?gad=1&gclid=Cj0KCQjwoK2mBhDzARIsADGbjeoNt1rkkKWWJVaawEFnsUmV3QjthBa3UjxAL7h_cefyqWyxDuxRis8aAvGIEALw_wcB).
2. Connect your iPhone to the PC via USB.
3. Once iMazing is installed, click "Continue with the Free Trial" and go to App Management.
4. Right-click on Minecraft and click "Install .IPA" (Note: The Korean translation within the program might be incorrect).
5. After extracting the IPA, open the file using a program like Bandizip (or any program that can handle compressed files).
6. Navigate to `Payload\minecraft.app\data\renderer\materials`.
7. Replace the existing material.bin shader file with the downloaded material.bin shader file.
8. Finally, sideload Minecraft back onto your device.

## Using Filza
First, install [Filza](https://filzadownload.com/) (Note: If your device is not jailbroken, you will need to sideload it from an external PC).

After installing Filza:

1. Go to `var\containers\Bundle\Application\Minecraft\minecraftpe.app\data\renderer\materials`.
2. Backup the materials folder.
3. Select the downloaded Render Dragon shader file, copy it.
4. Go back to the previous location and replace the material.bin file with the copied shader file.

## IPA Sideload
For non-jailbroken devices, you need to sideload the IPA using an external PC. You can use sideloading tools like:

* [AltStore](https://altstore.io)
* [Sideloadly](https://sideloadly.io)

Please refer to the respective instructions provided by each sideloading tool for the installation process.