# 렌더드래곤 셰이더 설치법

렌더드래곤 셰이더 설치법에 대한 문서입니다.

- [렌더드래곤 셰이더 리스트로 돌아가기](/language/ko_kr/README.md)

<br>

> [!NOTE]
> 실시간 그림자, 물과 철블록에 반사돼는 주변 사물, 동적 색 조명등을 원한다면 찾으시는게 렌더드래곤 셰이더가 아닌 선명한 비주얼일 것입니다.
선명한 비주얼은 설정에서 키실 수 있습니다.

> 렌더드래곤 셰이더와 Virbrant Visuals의 차이가 뭔가요?  
> Virbrant Visuals는 어떻게 적용하나요?
> > [Virbrant Visuals 적용법및 설명](/language/ko_kr/docs/virbrant_visuals.md)

<br>

> [!NOTE]
> 렌더드래곤 셰이더를 리소스팩에서 불러올 수 있게하는 대부분의 유틸리티 모드는 마인크래프가 업데이트함에 따라 그에 맞춰 업데이트하기 전까지 작동을 하지 않을 수도 있습니다.  
> 
> 만약 마인크래프트가 업데이트가 된 후 셰이더가 작동하지 않는다면 사용중인 모드가 업데이트를 할때까지 기다리는것을 추천드립니다.

<br>

## 모바일

### 안드로이드

> 삼성 갤럭시, 샤오미, 구글 픽셀등 애플의 제품을 제외한 거의 대부분의 폰은 안드로이드를 사용합니다.

1. [MB Loader](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/language/ko_kr/README.md#mb-loader)를 설치합니다.
2. `Load to mbl2`버튼을 누르면 현제 설치돼있는 마인크래프트로 실행됩니다.
3. Renderdragon Shader List에서 셰이더팩을 다운받아 리소스팩을 불러와 **글로벌 리소스**로 적용합니다.

<br>

#### LeviLaunchroid 모드 사용
BetterRenderdragon과 같이 .so파일을 지원하는 모드는 LeviLaunchroid를 통해 실행 할 수 있습니다.

1. [LeviLaunchroid](https://github.com/LiteLDev/LeviLaunchroid/releases) apk 를 설치합니다.
2. [렌더드래곤 셰이더 모드 / 유틸리티](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/language/ko_kr/README.md#%EB%A0%8C%EB%8D%94%EB%93%9C%EB%9E%98%EA%B3%A4-%EC%85%B0%EC%9D%B4%EB%8D%94-%EB%AA%A8%EB%93%9C--%EC%9C%A0%ED%8B%B8%EB%A6%AC%ED%8B%B0)에서 `SO`태그가 있는 모드의 `.so`파일로 된 모드를 다운로드합니다.
3. LeviLaunchroid를 실행한 후 왼쪽 하단 Mods패널에서 `+`버튼을 누른 후 `.so`파일로 된 모드파일을 파일탐색기에서 선택합니다.
4. `Launch`버튼을 누르면 현제 설치돼있는 마인크래프트로 모드가 적용돼어 실행됩니다.

> [!NOTE]
> 각 모드는 모드끼리 서로 호환이 안될 수 있습니다.

<br>

APK를 직접 수정하여 적용하는 수동 설치를 원한다면 다음 문서를 참고해주세요.
* [수동 설치 가이드](android.md)

<br>
<br>

### iOS

> 아이폰, 아이패드는 이 문서를 참고해주세요.

* [iOS 렌더드래곤 셰이더 설치법](iOS.md)

<br>
<br>

## PC

### 윈도우

1. [BetterRenderDragon](https://github.com/QYCottage/BetterRenderDragon/releases)의 Realeses에서 가장 최신 버전을 다운로드합니다.
2. `BetterRenderDragon.zip`의 압축을 풀고 `mcbe_injector.exe`파일을 실행합니다.
3. Renderdragon Shader List에서 셰이더팩을 다운받아 리소스팩을 불러와 **글로벌 리소스**로 적용합니다.

> [!NOTE]
> 윈도우 및 크롬이 mcbe_injector.exe를 바이러스로 인식하기 때문에 크롬의 실시간 보안 및 Windows 보안의 실시간 보호 기능을 잠시 해체해야 합니다.  
> BetterRenderDragon 모드파일이 아닌 모드를 마인크래프트에 적용하고 실행하는 exe파일이 걸리는 것이기 때문에 모드에 바이러스가 진짜로 있지는 않습니다.  
> Windows 보안의 실시간 보호 기능이 해제돼어있지 않은경우 zip압축을 푼 이후에도 mcbe_injector.exe가 제거될 수 있습니다. 이경우 [Fzul's BRD Updater Script](https://github.com/faizul726/brd-updater-script)를 통해 방지할 수 있습니다.

<br>

### DLL 모드파일 사용
mc-w10-version-launcher을 통해 DLL형태의 모드파일을 사용할 수 있습니다.

1. 최신버전의 [mc-w10-version-launcher](https://github.com/QYCottage/mc-w10-version-launcher/releases)다운로드합니다.
2. zip압축을 풀고 MCLauncher.exe를 실행합니다.
3. 원하는 버전을 다운로드합니다.
4. [렌더드래곤 셰이더 모드 / 유틸리티](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/language/ko_kr/README.md#%EB%A0%8C%EB%8D%94%EB%93%9C%EB%9E%98%EA%B3%A4-%EC%85%B0%EC%9D%B4%EB%8D%94-%EB%AA%A8%EB%93%9C--%EC%9C%A0%ED%8B%B8%EB%A6%AC%ED%8B%B0)에서 `DLL`태그가 있는 모드의 `.dll`파일로 된 모드를 다운로드합니다.
5. zip 압축을 푼 폴더에서  
`imported_versions\Microsoft.MinecraftUWP "버전__패키지 이름".Appx\mods`  
경로에 dll 모드파일을 넣고 다시 MCLauncher.exe를 키고 마인크래프트를 실행합니다.
6. Renderdragon Shader List에서 셰이더팩을 다운받아 리소스팩을 불러와 **글로벌 리소스**로 적용합니다.

<br>

**BetterRenderDragon**을 사용하지 못하는 경우 수동설치를 위해 [**Matject**](https://github.com/faizul726/matject)을 사용할 수 있습니다.

<br>

Matject가 작동하지 않을경우 [IObit Unlocker](https://www.iobit.com/en/iobit-unlocker.php)을 통해 `material.bin`파일을 수동으로 교체할 수 있습니다.  
`materiall.bin`파일은 리소스팩의 압축을 푼 후
```
🖼️ pack_icon.png
🗒️ manifest.json
📁 renderer
    ↳ 📁 materials
        ↳  .material.bin
```
이 경로에서 찾을 수 있습니다.

바닐라 베드락 마인크래프트의 `.materail.bin`는  
```
C:\Program Files\WindowsApps\Microsoft.MinecraftUWP_1.21.9401.0_x64__8wekyb3d8bbwe\data\renderer\materials
```
이곳에서 찾을 수 있습니다.

<br>
<br>

## 문제 해결

> - **셰이더팩의 물, 하늘만 적용됩니다, 물, 하늘이 적용이 안됩니다.**  
> 마인크래프트를 재시작하면 대부분 해결됩니다.

> - **서버에 들어갔더니 셰이더가 작동하지 않습니다.**  
> 서버에 적용돼있는 리소스팩으로 인해 셰이더는 서버에서 제대로 작동하지 않을 수 있습니다.

> - **맵에 리소스팩을 적용했더니 세이더가 작동하지 않습니다.**  
> 글로벌 리소스로 활성화해주세요.

> - **모바일에서 모드 앱을 사용했더니 플레이하던 맵, 리소스팩등의 데이터가 사라졌습니다.**  
>  데이터가 사라진 것이 아닙니다. MB Loader와 LeviLaunchroid는 기존 마인크래프트와 다른 저장공간을 사용하기 때문에 기본 마인크래프트를 다시 실행하면 정상적으로 파일이 존재하는것을 볼 수 있습니다.

> [!NOTE]
> 위 사항 외의 버그 또는 문제는 셰이더 개발자에게 문의하세요.

---
* [Back to English](/docs/installation/README.md)