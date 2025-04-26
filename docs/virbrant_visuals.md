# Virbrant Visuals

## What is Virbrant Visuals (formerly Deferred Rendering)?

Vibrant Visuals is a visual graphics upgrade that will transform the way players experience Minecraft. Initially releasing for Minecraft: Bedrock Edition, it is our developer’s vision for what Minecraft looks like with improved visual elements such as directional lighting, volumetric fog, and more. The result is dazzling – shadows move as the sun arcs across the sky, water reflects the landscape around it, and clouds appear infinite as they stretch far into the distance. 
> Excerpt from https://www.minecraft.net/en-us/article/minecraft-vibrant-visuals

## What is the difference between Virbrant Visuals and the RenderDragon shader?

The RenderDragon shader is a **mod** made by modifying shaders based on the RenderDragon engine in the latest versions of the game. It is not an official feature, has a limited range of possible implementations, and requires direct modification of game files to customize.  
Virbrant Visuals, on the other hand, is a graphics mode officially supported by Mojang. It allows for features far beyond the original limits of Minecraft, such as reflections of surrounding objects, real-time dynamic shadows that change with time and lighting, and underwater light scattering. However, although it provides many built-in graphical enhancements, customization is only possible to a **limited extent via resource packs**. Thus, compared to RenderDragon shaders, it has far fewer customization possibilities.

### About terminology?

Before the name was changed from Deferred Rendering to Virbrant Visuals, efforts were made to clearly distinguish the two names. However, since the term "shader" was officially mentioned during Minecraft Live, calling it a shader is not completely incorrect.  
Nevertheless, it is still appropriate to distinguish between RenderDragon shaders and deferred packs.

Many people misunderstand shaders as merely tools to make graphics prettier, but technically, shaders are mechanisms that compute graphics. The visual effects you see in Minecraft—such as seeing blocks and the environment darkening as the sun sets—are possible because Minecraft already has built-in shaders.

Resource packs that adjust various deferred rendering parameters to change colors or textures do not actually include shader code, so they are called "deferred packs" or "graphics packs."  
This distinction is important not only for accurate terminology but also to prevent confusion with RenderDragon shaders.

In summary:

- **Virbrant Visuals**  
  - It is best to simply refer to it as Virbrant Visuals.

- **Resource packs that activate Virbrant Visuals and modify graphical aspects**  
  - Graphics packs  
  - **Not shader packs!**

- **RenderDragon shaders**  
  - Shaders  
  - Shader packs  
  - RenderDragon shaders  
  - ~~Not RTX~~

## How do I use Virbrant Visuals?

Refer to the `knowledge-hub` of Bedrock Graphics.

[![](/banners/comunity/Bedrock%20Graphics.png)](https://discord.gg/WwUEe7hYBz)

<br>

## I found "deferred shaders" on YouTube—how do I apply them?

![alt text](/screenshots/Years%20static%20shader/YSS%20SE/image.png)  
You might have seen shaders like Years Statics Shaders Special Edition (YSS SE) on YouTube.  
This shader pack was created to utilize the deferred pipeline before it was officially released and has now been discontinued.  
You can find some deferred shaders in the RenderDragon shader list 1.0. Since these shaders use the deferred pipeline, they allow much broader customizations such as dynamic shadows and screen-space reflections, but they are no longer being updated.  
Meanwhile, legacy deferred rendering—now called Virbrant Visuals—is under very active development, with frequent and major changes to graphics. As a result, maintaining deferred shaders has become extremely difficult, and all deferred shader development was discontinued after version 1.20.50.21, with YSS_SE_1.9.8.0 being the last release.  
You can still use deferred render shaders, but you will need to manually downgrade your game version.
