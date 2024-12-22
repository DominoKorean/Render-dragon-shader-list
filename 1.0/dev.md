# Dev

This document contains materials necessary for RenderDragon shader development.
<br/>

- [Dev](#dev)
  - [RenderDragon Shaders - Docs](#renderdragon-shaders---docs)
  - [ShaderLABS](#shaderlabs)
  - [Lazurite](#lazurite)
  - [mcbe-shader-codebase](#mcbe-shader-codebase)
  - [RenderDragonSourceCodeInv](#renderdragonsourcecodeinv)
  - [MaterialBinLoader](#materialbinloader)
  - [Simple MCRTX PostFX Shader](#simple-mcrtx-postfx-shader)
  - [MaterialBinTool](#materialbintool)
  - [Mcbe Shader Redirector (MCBER)](#mcbe-shader-redirector-mcber)
  - [Material updater](#material-updater)

<br/>

## RenderDragon Shaders - Docs
https://devendrn.github.io/renderdragon-shaders/docs/start.html

[RenderDragon Shaders](https://devendrn.github.io/renderdragon-shaders) is a website that contains various resources related to RenderDragon shaders, including the RenderDragon Shader List. In the [Docs](https://devendrn.github.io/renderdragon-shaders/docs/start.html), you can find detailed explanations of RenderDragon shader pack development written by [devendrn](https://github.com/devendrn), the developer of the [NewbX](https://github.com/devendrn/newb-x-mcbe) shader pack.

<br/>
<br/>

## ShaderLABS
https://discord.gg/RpzWN9S  

ShaderLABS is a community where developers and users involved in the graphics of Minecraft, including shader packs, resource packs, and mods, gather.  
If you need assistance in creating the RenderDragon shader, you can seek help from various developers in the [bedrock-shaders](https://discord.com/channels/237199950235041794/327203882180542484) channel.

<br/>
<br/>

## Lazurite
https://github.com/veka0/lazurite

Unofficial shader development tool for Minecraft: Bedrock Edition with RenderDragon graphics engine.  
It helps package and compile RenderDragon shaders, providing various helpful features.

<br/>
<br/>

## mcbe-shader-codebase
https://github.com/Veka0/mcbe-shader-codebase

This repository provides a comprehensive codebase for Minecraft Bedrock Edition shader development. It includes valuable resources, samples, and guidelines aimed at helping developers understand and create shaders for the Bedrock Edition of Minecraft. Whether you're just starting out or looking to expand your shader knowledge, this repository offers a strong foundation for working with RenderDragon and other shader-related tasks.

<br/>
<br/>

## RenderDragonSourceCodeInv
https://github.com/SurvivalApparatusCommunication/RenderDragonSourceCodeInv
 
This repository includes the internal files of material.bin and provides a way to rebuild them back into material.bin.


<br/>
<br/>

## MaterialBinLoader
https://github.com/ddf8196/MaterialBinLoader

Open source .so modification for Android that allows you to load shaders directly from resource packs. Actively maintained by [ENDERMANYK](https://github.com/ENDERMANYK) [here.](https://github.com/ENDERMANYK/MaterialBinLoader)
Supports armeabi-v7a and arm64-v8a as of April 29 2024.

APKs patched with Mbinloader can be found [here](#patched-app)

<br/>
<br/>

## Simple MCRTX PostFX Shader
https://github.com/veka0/simple-mcrtx-postfx-shader

Just a basic template shader written from scratch for Bedrock RTX that modifies PostFX materials (bloom and tonemapping).

<br/>
<br/>

## MaterialBinTool
https://github.com/ddf8196/MaterialBinTool

RenderDragon .material.bin unpacking/packaging/compilation tool

<br/>
<br/>

## Mcbe Shader Redirector (MCBER)
https://github.com/mcbegamerxx954/mcbe_shader_redirector

This crate is made to redirect MCBE shaders to ones from resource packs externally so that it can work with any mcbe version and even multiple platforms.  
It serves a similar role to the existing MaterialBinTool.

<br/>
<br/>

## Material updater
https://github.com/mcbegamerxx954/material-updater

This tool can update shader packs to latest version. Or downgrade them as you wish.

parsing code ported to rust from the tool [MaterialBinTool](https://github.com/ddf8196/MaterialBinTool) made by [ddf8196](https://github.com/ddf8196)
