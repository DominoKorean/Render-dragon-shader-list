# 안드로이드 렌더드래곤 셰이더 설치법

## 목차
- [안드로이드 렌더드래곤 셰이더 설치법](#안드로이드-렌더드래곤-셰이더-설치법)
  - [목차](#목차)
  - [MaterialBinLoader](#materialbinloader)
  - [직접 설치](#직접-설치)
  - [백업](#백업)

## MaterialBinLoader
MaterialBinLoader는 셰이더 파일인 material.bin파일을 기존의 HAL 엔진처럼  
리소스팩으로 불러올 수 있게 해주는 프로그램입니다.  
마인크래프트 파일의 APK를 수정해 직접 설치할 수도 있으나  
[@ENDERMANYK](https://github.com/ENDERMANYK)개발자가 미리 준비해준   Patched APP의 APK를 설치하는 것이 가장 편리합니다.  
Patched APP은 이곳에서 받을 수 있습니다.  
https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/patchedapp.md  

## 직접 설치
MaterialBinLoader를 지원하지 않는 경우 직접 마인크래프트의 렌더파일을 수정해 주어야 합니다.  
이 과정에서 마인크래프트를 재설치하는 과정이 필요하기 때문에 [백업](#백업)을 먼저 해주시길 바랍니다.  

마인크래프트의 렌더파일을 수정하기 위해선 먼저 Apktool M과 MT Manager가 필요합니다.  
먼저 [APKtool](https://maximoff.su/apktool/?lang=en)을 설치해줍니다.
그 후 APKtool에서 상단에 Application 탭으로 가준 다음  
Installed Applications 에서 Minecraft를 선택한 후 Antisplit을 선택해줍니다.  
그 후 Use aapt2를 선택해주고  
Select a signature file에서 Don't sign을 선택해 줍니다.  
이 후 APK를 추출하게 되는데 시간이 좀 걸릴 수 있습니다.  
백그라운드에서 실행이 가능하니 폰을 끄거나 APKtool을 끄지 않는 한에서 다른 어플을 사용할 수 있습니다.  

설치가 다되었다면 이제[MT Manager](https://mt2.cn/download)을 설치해주시면됩니다.  
링크에서 파란색 글씨로 된 本地下载를 눌러주시면 됩니다.  
그 후 MT Manager에서 한쪽 탭에서는 APKtool_M 폴더를 열고
다른 한쪽에는 다운로드 받은 셰이더 파일을 열어줍니다.  
이제 APKtool_M폴더에 Anti Split된 APK 파일을 눌르고 VIEW를 눌러줍니다.  
그 후 assets/rnderer/materials 순으로 폴더를 들어가줍니다.
이제 셰이더 파일에 있던 material.bin파일을 꾹누른 후  
+Add 버튼 눌러준 뒤 AUTO SIGN 체크 박스 선택한 후 OK눌러줍니다.  
모든 material.bin파일에 동일한 작업이 끝났다면 뒤로가기로 나가서  
APK다시 선택해 준 후 FUNCTION에 들어가줍니다.  
그 후 APK Sign선택하고 OK눌러주시면 됩니다.  
이제 APK를 설치하면 인게임에서 셰이더가 적용된 모습을 보실 수 있습니다.  

추가로 만약 셰이더 파일에 base.mcpack같은 파일이 같이 있다면  
선택 후 왼쪽 하단 TYPE에서 ALL선택 후  
MInecraft선택해서 열어주신다음  
리소스팩이 불러와지면 리소스팩 적용해주시면 됩니다.

[영상 설명](https://youtu.be/MYlnjqnFBgw)




## 백업
마인크래프트의 저장 데이터의 경우  
```
0\Android\data\com.mojang.minecraftpe
```
에 저장됩니다.  
Android/data이상의 폴더는 일반적인 파일탐색기로는 접근이 불가능하며  
해당 폴더에 접근이 가능한 다른 파일탐색기를 설치해야합니다.  
( [MT Manager](https://mt2.cn/download)을 추천드립니다. 링크에 들어가서 本地下载를 누르면 다운로드됩니다. )

접근이 가능한 파일탐색기를 가지고 계시다면  
com.mojang.minecraftpe에 있는 files폴더를 잠시 다른 폴더에 옮겨두시면 됩니다.  
단, 이때 마인크래프트를 설치한지 얼마 지나지 않았을경우 files폴더에 아무것도 없을 수 있습니다.

특정 기종의 특정 안드로이드 버전에서는 폰 내에서 Android\data이상의 폴더가 접근이 아예 불가능 할 수 있습니다.  
이 경우 PC에 USB등을통해 연결하여  
com.mojang.minecraftpe폴더에 접근해야합니다.