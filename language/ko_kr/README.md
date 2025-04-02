![](/images/banner.png)

<!--
> [!WARNING]
> **최신버전이 아님**  
> 이 언어의 문서는 아직 최신 업데이트가 포함돼지 않았습니다.
-->

<!--
This comment is for another language.  
If there are any changes to the RenderDragon shader list, the comment in the other language's documentation will be removed, making the Outdated label visible.
-->

<br>

* [Back to English](/README.md)

<br>

# 렌더드래곤 셰이더 리스트

가짜 셰이더를 다운로드하는것을 방지하고 신뢰할 수 있는 셰이더팩을 찾을 수 있게 하기 위한 깃허브 레퍼지토리입니다.

문서에 문제가 있다면 [issues](https://github.com/DominoKorean/Render-dragon-shader-list/issues)를 이용해주세요.  
문서에 기여하거나 자신의 셰이더를 추가하고 싶다면 [Pull Request](https://github.com/DominoKorean/Render-dragon-shader-list/pulls)를 이용해주세요.

<br>

## 렌더드래곤이 뭔가요?
[마인크래프트 위키](https://minecraft.wiki/RenderDragon)에 따르면, **렌더드래곤**은 Minecraft 베드락 에디션을 위해 만들어진 새로운 렌더링 엔진으로, 이전의 OpenGL/DirectX 엔진을 대체합니다.

렌더드래곤 셰이더란 렌더드래곤 도입으로 공식적으로 써드파티 셰이더의 지원이 중단된 이후 렌더드래곤 파일을 모딩해 커스텀 셰이더를 적용할 수 있게 만든것입니다.

<br>

> [!WARNING]
> `9Minecraft`를 사용하지 마시길 바랍니다.   
> 해당 사이트에서는 가짜 RenderDragon 셰이더가 포함되어 있고 셰이더가 제작자의 허락 없이 배포되고 있으며  
> **가장 중요한 점은, 해당 사이트가 바이러스 및 보안 위험을 초래할 수 있다는 것입니다.**  
> 따라서 절대 사용하지 말고 주변 사람들에게도 그 위험성을 알려주시길 바랍니다.

<br>

## Bedrock Graphics
[![](/banners/comunity/Bedrock%20Graphics.png)](https://discord.gg/WwUEe7hYBz)

<br>

## 어떻게 설치하나요?

- [렌더드래곤 셰이더 설치법](/language/ko_kr/docs/installation/README.md)

<br>

---

- [이용약관](/language/ko_kr/TERMS_OF_USE.md)

<br>

> [!NOTE]
> 이 문서는 RD Shader list 2.0입니다.  
> - [렌더드래곤 셰이더 리스트 **1.0**](/1.0/README.md)
>   - [1.0과 2.0의 차이가 뭔가요?](/docs/about2.0.md)

<br>

---

<br>

<!-- 
다음 목차는 VSCode의 "Markdown All in One" 확장 프로그램에 의해 자동으로 업데이트됩니다. 수정하지 마세요. (수정하더라도 자동으로 원래 상태로 돌아갑니다.)
-->

## 목차
- [렌더드래곤 셰이더 리스트](#렌더드래곤-셰이더-리스트)
  - [렌더드래곤이 뭔가요?](#렌더드래곤이-뭔가요)
  - [Bedrock Graphics](#bedrock-graphics)
  - [어떻게 설치하나요?](#어떻게-설치하나요)
  - [목차](#목차)
- [렌더드래곤 셰이더 모드 / 유틸리티](#렌더드래곤-셰이더-모드--유틸리티)
  - [MB Loader](#mb-loader)
  - [BetterRenderDragon-xmake](#betterrenderdragon-xmake)
  - [Draco Injector](#draco-injector)
  - [Matject](#matject)
  - [Patched app](#patched-app)
- [렌더드래곤 셰이더](#렌더드래곤-셰이더)
  - [Render dragon](#render-dragon)
    - [YSS RD](#yss-rd)
    - [Newb X Legacy](#newb-x-legacy)
    - [Eternity Shader](#eternity-shader)
    - [Vanilla X Enhanced](#vanilla-x-enhanced)
    - [Innovative Shader](#innovative-shader)
    - [Cool Voxel](#cool-voxel)
    - [MLYX 弥浪隐霄 Shader](#mlyx-弥浪隐霄-shader)
    - [Ranzie's Vibrant Shader](#ranzies-vibrant-shader)
    - [AziFy: REVIVE](#azify-revive)
    - [AziFy: REIMAGINED](#azify-reimagined)
    - [AziFy Natural](#azify-natural)
    - [Truly Default](#truly-default)
    - [FHD Shader](#fhd-shader)
  - [RTX](#rtx)
    - [BetterRTX](#betterrtx)
  - [유틸리티 셰이더](#유틸리티-셰이더)
    - [RenderDragon FullBright](#renderdragon-fullbright)
    - [RenderDragonFogRemover](#renderdragonfogremover)
    - [RD Cubemap Fix](#rd-cubemap-fix)
    - [Gray's Night Vision](#grays-night-vision)
    - [HD Font Fix](#hd-font-fix)
    - [Glow Em All](#glow-em-all)
  - [개발](#개발)

---

<br>
<br>

# 렌더드래곤 셰이더 모드 / 유틸리티

<br>

## MB Loader
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  

https://play.google.com/store/apps/details?id=io.bambosan.mbloader

> 한번의 설치만으로 Material Bin Loader을 쓸 수 있는 베드락 런처.

<br>
<br>

## BetterRenderDragon-xmake
![](/language/ko_kr/tags/platform/Windows.svg)  
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  

https://github.com/dreamguxiang/BetterRenderDragon-xmake

> 다음 기능을 제공하는 써드파티 모드입니다.
> - 디퍼드 렌더링 활성화
> - 성능 향상을 위해 레이트레이싱 비활성화
> - 리소스 팩에서 렌더드래곤 셰이더 불러오기
> - 설정 가능한 ImGui

<br>
<br>

## Draco Injector
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
https://github.com/mcbegamerxx954/draco-injector

> 마인크래프트 파일을 추출해서 글로벌 리소스팩으로 셰이더팩을 불러올 수 있게 패치를 자동으로 해주는 프로그램

<br>
<br>

## Matject

![](/language/ko_kr/tags/platform/Windows.svg)  
https://github.com/faizul726/matject

> 마인크래프트 materialbin 파일을 **셰이더 materialbin 파일**로 교체하는 작업을 IObit Unlocker를 이용하여 자동으로 해주는 프로그램.

<br>
<br>

## Patched app

![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
https://discord.gg/yss

> MaterialBinLoader를 기반으로 글로벌 리소스팩에서 렌더드래곤의 `.material.bin` 파일을 로드할 수 있도록 수정된 APK파일.

> [!NOTE]
> Patched APP은 더이상 업데이트 되지 않습니다. 대신 [MB Loader](#mb-loader)을 사용하시길 바랍니다.

<br>
<br>

---

<br>
<br>
<br>
<br>

# 렌더드래곤 셰이더

<br>
<br>

## Render dragon

<br>

### YSS RD
[![](/banners/shader/YSS%20RD.png)](https://discord.gg/years-static-shader-group-738688684223889409)
![Creator](https://img.shields.io/badge/개발자-ENDERMANYK-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/years-static-shader-group-738688684223889409)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)
![](/language/ko_kr/tags/platform/Switch.svg)
![](/language/ko_kr/tags/platform/Xbox.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

[![](/language/ko_kr/tags/etc/Screen_Shots.svg)](screenshots/Years%20static%20shader/YSS%20RD)  

<br>
<br>

### Newb X Legacy
[![](/banners/shader/Newb%20X.png)](https://devendrn.github.io/newb-shader/)
![Creator](https://img.shields.io/badge/개발자-devendrn-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/GitHub.svg)](https://github.com/devendrn/newb-x-mcbe)
[![](/language/ko_kr/tags/link/CurseForge.svg)](https://www.curseforge.com/minecraft-bedrock/texture-packs/newb-shader)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/newb-community-844591537430069279)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)
![](/language/ko_kr/tags/pre_supported_packaging/IPA.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br>
<br>

### Eternity Shader
[![](/banners/shader/Eternity%20Shader.png)](https://mcpedl.com/user/WindsScion)
![Creator](https://img.shields.io/badge/개발자-Wind's_Scion-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/eternity-shader-v1-3-beta-mcpe-renderdragon-support-1-21)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/EdG4x85Sgm)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg) 
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Fantasy.svg)

[![](/language/ko_kr/tags/etc/Screen_Shots.svg)](screenshots/Eternity%20Shader/README.md)  

<br>
<br>

### Vanilla X Enhanced
[![](/banners/shader/Vanilla%20X%20Enhanced.png)](https://mcpedl.com/user/WindsScion)
![Creator](https://img.shields.io/badge/개발자-Wind's_Scion-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/vanilla-x-enhanced-v0-1-for-be-pe)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/EdG4x85Sgm)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg) 
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br>
<br>

### Innovative Shader
[![](/banners/shader/Innovative%20Shader.png)](https://discord.gg/EdG4x85Sgm)
![Creator](https://img.shields.io/badge/개발자-Wind's_Scion-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/EdG4x85Sgm)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg) 
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Realistic.svg)

<br>
<br>

### Cool Voxel
[![](/banners/shader/Cool%20Voxel.png)](https://mcpedl.com/user/WindsScion)
![Creator](https://img.shields.io/badge/개발자-Wind's_Scion-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/cool-voxel-v1-0-for-mcpe-be)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/EdG4x85Sgm)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg) 
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br>
<br>

### MLYX 弥浪隐霄 Shader
[![](/banners/shader/MLYX%20弥浪隐霄%20Shader.png)](https://discord.gg/years-static-shader-group-738688684223889409)
![Creator](https://img.shields.io/badge/개발자-mlyx__chuchu-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/years-static-shader-group-738688684223889409)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg) 
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Semi_Realistic.svg)  

<br>
<br>

### Ranzie's Vibrant Shader
[![](/banners/shader/Ranzie's%20Vibrant%20Shader.png)](https://www.patreon.com/ZnarGeenGuy)
![Creator](https://img.shields.io/badge/개발자-Ranzie-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/Patreon.svg)](https://www.patreon.com/ZnarGeenGuy)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://youtu.be/6Kg9OlggkQU?si=qGxfXsG9Fp-oIvSo)  
![Platform](/language/ko_kr/tags/tag/Platform.svg)
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg) 
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Cartoon.svg)

<br>
<br>

### AziFy: REVIVE
[![](/banners/shader/AziFy%20Revive.png)](https://mcpedl.com/user/azi-angelo-real)
![Creator](https://img.shields.io/badge/개발자-Azi_Angelo_Real-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/user/azi-angelo-real)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://www.youtube.com/@aziangelo)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br/>
<br/>

### AziFy: REIMAGINED
[![](/banners/shader/AziFy%20Reimagined.png)](https://mcpedl.com/user/azi-angelo-real)
![Creator](https://img.shields.io/badge/개발자-Azi_Angelo_Real-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/user/azi-angelo-real)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/MZfYkY8tmD)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://www.youtube.com/@aziangelo)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br/>
<br/>

### AziFy Natural
[![](/banners/shader/AziFy%20Natural.png)](https://mcpedl.com/user/azi-angelo-real)
![Creator](https://img.shields.io/badge/개발자-Azi_Angelo_Real-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/user/azi-angelo-real)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/MZfYkY8tmD)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://www.youtube.com/@aziangelo)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br>
<br>

### Truly Default
[![](/banners/shader/Truly%20Default.png)](https://mcpedl.com/user/azi-angelo-real)
![Creator](https://img.shields.io/badge/개발자-Azi_Angelo_Real-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/user/azi-angelo-real)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/MZfYkY8tmD)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://www.youtube.com/@aziangelo)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br>
<br>

### FHD Shader
[![](/banners/shader/FHD%20Shader.png)](https://mcpedl.com/user/azi-angelo-real)
![Creator](https://img.shields.io/badge/개발자-Azi_Angelo_Real-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/user/azi-angelo-real)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/MZfYkY8tmD)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://www.youtube.com/@aziangelo)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
![Style](/language/ko_kr/tags/tag/Style.svg)
![](/language/ko_kr/tags/style/Vanilla.svg)

<br>
<br>
<br>

## RTX

<br>

### BetterRTX
[![](/banners/shader/BetterRTX.png)](https://github.com/BetterRTX)
![](https://img.shields.io/badge/Bedrock_RTX-윈도우-0078D6?style=flat-square&logo=nvidia) 

<br>

- [설치 프로그램](https://github.com/ABUCKY0/betterrtx-installer)

<br>
<br>

## 유틸리티 셰이더

<br>

### RenderDragon FullBright
![Creator](https://img.shields.io/badge/개발자-Furzide-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/GitHub.svg)](https://github.com/Furzide/RenderDragonFullBright)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
> 화면이 항상 야간투시인것처럼 어두운곳 없이 밝게 해줍니다.

https://github.com/Furzide/RenderDragonFullBright  

<br>
<br>

### RenderDragonFogRemover
![Creator](https://img.shields.io/badge/개발자-Furzide-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/GitHub.svg)](https://github.com/Furzide/RenderDragonFogRemover)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
> 안개를 제거해줍니다.

https://github.com/Furzide/RenderDragonFogRemover  

<br>
<br>

### RD Cubemap Fix
![Creator](https://img.shields.io/badge/개발자-Furzide-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/GitHub.svg)](https://github.com/Furzide/RenderDragonCubemapFix)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
> 기존의 마인크래프트의 잘못된 큐브맵 위치를 고쳐줍니다.

https://github.com/Furzide/RenderDragonCubemapFix

<br>
<br>

### Gray's Night Vision
![Creator](https://img.shields.io/badge/개발자-Wind's_Scion-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/night-vision-v2-2-for-mcpe-be-v1-21-support-renderdragon/)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/EdG4x85Sgm)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/iOS.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
> 화면이 항상 야간투시인것처럼 어두운곳 없이 밝게 해줍니다.

https://discord.com/channels/660840983117955072/1200077652514586624

<br>
<br>

### HD Font Fix
![Creator](https://img.shields.io/badge/개발자-GameParrot-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/GitHub.svg)](https://github.com/GameParrot/mcpe-hdfont-fix)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)
![](/language/ko_kr/tags/platform/Windows.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)  
> 높은 해상도의 폰트를 사용할때 텍스쳐가 이상하게 보이는걸 고쳐줍니다.

[![](https://img.shields.io/badge/Screen_Shots-click-white?style=social-square)](screenshots/HD%20Font%20Fix/README.md)  

https://github.com/GameParrot/mcpe-hdfont-fix

<br>
<br>

### Glow Em All
![Creator](https://img.shields.io/badge/개발자-Azi_Angelo_Real-3D444D?style=flat-square&labelColor=white)  
![link](/language/ko_kr/tags/tag/link.svg)
[![](/language/ko_kr/tags/link/MCPEDL.svg)](https://mcpedl.com/glow-em-all)
[![](/language/ko_kr/tags/link/Discord.svg)](https://discord.gg/MZfYkY8tmD)
[![](/language/ko_kr/tags/link/YouTube.svg)](https://youtu.be/91xzwza8F84?si=SsgUojdXQTk0v-hF)  
![Platform](/language/ko_kr/tags/tag/Platform.svg) 
![](/language/ko_kr/tags/platform/Android.svg)  
![Pre-Packaging](/language/ko_kr/tags/tag/Pre-Packaging.svg)
![](/language/ko_kr/tags/pre_supported_packaging/MaterialBinLoader.svg)
> 광물을 빛나게 합니다.

[![](https://img.shields.io/badge/Screen_Shots-click-white?style=social-square)](screenshots/Ringo/README.md)  
https://mcpedl.com/glow-em-all

<br>
<br>
<br>

---

<br>
<br>

## 개발
https://github.com/DominoKorean/Render-dragon-shader-list/tree/main/dev.md

이 문서에는 렌더드래곤 셰이더 개발에 필요한 자료들을 모아놨습니다.

<br>
<br>
<br>

---

<br>
<br>

**THIS IS NOT AN OFFICIAL MINECRAFT PRODUCT. IT IS NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**
