# PC

## 목차
- [PC](#pc)
  - [목차](#목차)
  - [MaterialBinLoader](#materialbinloader)
  - [직접 설치](#직접-설치)
  - [Vanilla2Deferred](#vanilla2deferred)
  - [YSS Special Edition](#yss-special-edition)
  - [BetterRTX](#betterrtx)

## MaterialBinLoader
MaterialBinLoader는 셰이더 파일인 material.bin파일을 기존의 HAL 엔진처럼  
리소스팩으로 불러올 수 있게 해주는 프로그램입니다.  
Windows에서는 BetterRenderDragon을 통해 손쉽게 사용할 수 있습니다.  
[BetterRenderDragon](https://github.com/ddf8196/BetterRenderDragon)의 가장 최신버전을 다운로드한 후  
압축을 푼다음 bat파일을 실행시켜주기만 하면 됩니다.  
BetterRenderDragon에서 MaterialBinLoader은 기본적으로 켜져있으며  
MaterialBinLoader를 지원하는 셰이더를 리소스팩으로 적용해주기만 하면 됩니다.

## 직접 설치
MaterialBinLoader를 지원하지 않는 경우 직접 마인크래프트의 렌더파일을 수정해 주어야 합니다.  
먼저 Bedrock Launcher를 설치해야합니다.  
Bedrock Launcher는 버전을 바꿀 수 있는 기능을 제공하는데  
이때 마인크래프트 파일을 쉽게 접근할 수 있는 곳으로 번경합니다.  
상단의 Installations에서 New installation을 통해  
원하는 버전을 선택해준 후 Create해준 다음  
해당 버전을 플레이하면  
만약 따로 폴더를 경로를 번경하지 않았다면
```
C:\Users\user\AppData\Roaming\.minecraft_bedrock\versions
```
에 설치가 됩니다.  
참고로 이떄 파일이 손상될 수 있으니 먼저  
```
C:\Users\user\AppData\Local\Packages\Microsoft.MinecraftUWP_(유저마다 다름)\LocalState\games\com.mojang
```
에 들어가서 com.mojang폴더 통째로 잠시 백업해두시는걸 추천드립니다.  
이제 설치한 버전폴더로 들어간 뒤 data\renderer\material 에 들어가서  
material.bin 셰이더 파일을 덮어씌우기 해주시면됩니다.  
(이때 Bedrock Launcher로 실행하지 않아도 해당 경로의 파일로 실행되니 덮어씌우기 전에 원본 파일을 백업해두시는걸 추천드립니다.)
이제 마인크래프트를 실행하면 셰이더가 적용된 모습을 보실 수 있습니다.

추가로 추가로 만약 셰이더 파일에 base.mcpack같은 리소스팩 파일이 같이 있다면  
같이 적용해주시면 됩니다.

## Vanilla2Deferred

레이트레이싱 옵션을 해제하고 Deferred Rendering으로 대체하는 프로그램입니다.

**참고:**

* 이 프로그램은 이제 BetterRenderDragon: https://github.com/ddf8196/BetterRenderDragon에 내장되어 있습니다.
* 1.20.10 이상 버전에서는 레이트레이싱 옵션을 해제하지 않아도 됩니다. 대신, 세계에 참여하면 자동으로 켜지게됩니다.

## YSS Special Edition
YSS Special Edition은 1.19.40 ~ 1.19.63 에서만 작동합니다.  
먼저 1.19.40 ~ 1.19.63사이의 버전을 Bedrock Launcher로 설치한 뒤  
[직접 설치](#직접-설치)에 써진대로 따라 셰이더를 설치합니다.  
그 뒤 [RTX2Deferred 1.2.0](https://github.com/ddf8196/BetterRenderDragon/releases/tag/v1.2.0)을 다운로드 후 bat파일을 실행시켜줍니다.  

## BetterRTX
material.bin을 [직접 설치](#직접-설치)에 따라 직접 설치하거나  
BetterRTX에서 [공식적으로 지원하는 Installer](https://github.com/BetterRTX/BetterRTX-Installer)을 이용할 수 있습니다.  
Installer의 경우 PowerShell 스크립트파일(ps1)으로 제공되며  
우클릭 후 관리자 권한으로 열어 Windows PowerShell로 작동시키거나  
Vscode에서 PowerShell 익스텐션을 설치해 실행시킬 수 있습니다.  
또한 작동전에 무조건 [IObit Unlocker](https://www.iobit.com/en/iobit-unlocker.php)가 설치되어 있어야합니다.