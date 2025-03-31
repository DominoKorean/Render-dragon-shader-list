# 안드로이드 렌더드래곤 셰이더 수동 설치법


이 과정은 마인크래프트를 재설치하는 과정이 필요하기 때문에 [백업](#백업)을 먼저 진행해주시길 바랍니다.  

1. 먼저 [APKtool](https://maximoff.su/apktool/?lang=en)을 설치해줍니다.
2. APKtool에서 상단에 **Application** 탭으로 가준 다음 'Installed Applications' 에서 Minecraft를 선택한 후 Antisplit을 선택해줍니다.  
3. Antisplit에서 Use aapt2를 선택해주고  
Select a signature file에서 Don't sign을 선택해 줍니다.  
4. 이 후 APK를 추출하게 되는데 시간이 좀 걸릴 수 있습니다.  
백그라운드에서 실행이 가능하니 폰을 끄거나 APKtool을 끄지 않는 한에서 다른 어플을 사용할 수 있습니다.  
5. 추출이 다되었다면 [MT Manager](https://mt2.cn/download)다운로드 페이지로 가줍니다.
6. 다운로드 링크에서 파란색 글씨로 된 **本地下载**를 눌러주면 MT Manager APK파일을 받을 수 있습니다.
> [!NOTE]
> MT Manager을 설치하는 과정에서 위험한 어플로 감지되어 경고를 띄우거나 설치가 안될 수 있습니다.  
> 이는 MT Manager가 중국에서 어플을 폰으로 모딩하기 위해 제작된 광범위 툴이므로 그만큼 많은 권한이 필요해서이기 떄문에 설치해도 괜찮습니다.

7. MT Manager을 설치한 후 MT Manager에서 한쪽 탭에서는 `APKtool_M` 폴더를 열고
다른 한쪽에는 다운로드 받은 셰이더 파일을 열어줍니다.  
( 만약 `.mcpack` 파일 형태로 받았다면 파일을 눌러 Archive Viewer로 들어가준 후 `renderer/materials`폴더로 들어가면 셰이더 파일을 찾을 수 있습니다. )
1. `APKtool_M` 폴더에 APK 파일을 눌르고 VIEW를 눌러줍니다.  
2. APK 파일이 열렸다면 `assets/rnderer/materials` 경로로 폴더를 들어가줍니다.
3. 셰이더 파일에 있던 `.material.bin`파일을 꾹 누른 후 **+Add** 버튼을 눌러준 뒤 AUTO SIGN 체크 박스를 선택한 후 OK를 눌러줍니다.  
4. 셰이더 폴더에 있던 모든 .material.bin파일에 동일한 작업이 끝났다면 뒤로가기로 나가서 APK를 다시 선택해 준 후 FUNCTION에 들어가줍니다.  
5. **APK Sign**을 선택하고 OK를 눌러줍니다.  
6. 이제 해당 APK를 설치하면 인게임에서 셰이더가 적용된 모습을 보실 수 있습니다.  

[영상 설명](https://youtu.be/MYlnjqnFBgw)

## 백업

마인크래프트의 저장 데이터의 경우  
```
0\Android\data\com.mojang.minecraftpe
```
에 저장됩니다.  
Android/data이상의 폴더는 일반적인 파일탐색기로는 접근이 불가능하며 해당 폴더에 접근이 가능한 다른 파일탐색기를 설치해야합니다.  
위 가이드에서 필요한 `MT Manager`을 사용해 접근이 가능합니다. (6번 항목 확인)

접근이 가능한 파일탐색기를 가지고 계시다면 `com.mojang.minecraftpe`에 있는 files폴더를 잠시 다른 폴더에 옮겨두시면 됩니다.  
단, 이때 마인크래프트를 설치한지 얼마 지나지 않았을경우 files폴더에 아무것도 없을 수 있습니다.

특정 기종의 특정 안드로이드 버전에서는 폰 내에서 `Android\data`이상의 폴더가 접근이 아예 불가능 할 수 있습니다.  
이 경우 PC에 C to USB등의 케이블로 유선 연결하여   com.mojang.minecraftpe폴더에 접근해야합니다.