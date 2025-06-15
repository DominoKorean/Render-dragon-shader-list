# 렌더드래곤 셰이더 설치법

렌더드래곤 셰이더 설치법에 대한 문서입니다.

- [렌더드래곤 셰이더 리스트로 돌아가기](/language/ko_kr/README.md)

<br>

> [!NOTE]
> 실시간 그림자, 물과 철블록에 반사돼는 주변 사물, 동적 색 조명등을 원한다면 당신이 원하는것은 렌더드래곤 셰이더가 아닌 Virbrant Visuals(Deffered Rendering)일것입니다.

> 렌더드래곤 셰이더와 Virbrant Visuals의 차이가 뭔가요?  
> Virbrant Visuals는 어떻게 적용하나요?
> > [Virbrant Visuals 적용법및 설명](/language/ko_kr/docs/virbrant_visuals.md)

<br>

## 모바일

### 안드로이드

> 삼성 갤럭시, 샤오미, 구글 픽셀등 애플의 제품을 제외한 거의 대부분의 폰은 안드로이드를 사용합니다.

1. [MB Loader](https://github.com/DominoKorean/Render-dragon-shader-list/blob/main/language/ko_kr/README.md#mb-loader) 설치
2. `Load to mbl2`버튼을 누르면 현제 설치돼있는 마인크래프트로 실행됩니다.
3. Renderdragon Shader List에서 셰이더팩을 다운받아 리소스팩을 불러와 **글로벌 리소스**로 적용합니다.

기존의 Patched APP같은 방식을 원한다면 [Draco Injector](https://github.com/mcbegamerxx954/draco-injector)을 사용하세요.  

APK를 직접 수정하여 적용하는 수동 설치를 원한다면 다음 문서를 참고해주세요.
* [수동 설치 가이드](android.md)

<br>

### iOS

> 아이폰, 아이패드는 이 문서를 참고해주세요.

* [iOS 렌더드래곤 셰이더 설치법](iOS.md)

<br>

## PC

### 윈도우

1. [BetterRenderDragon](https://github.com/dreamguxiang/BetterRenderDragon-xmake)의 Realeses에서 가장 최신 버전을 다운로드합니다.
2. `BetterRenderDragon.zip`의 압축을 풀고 `bat`파일을 실행합니다.
   - 릴리즈 버전일 경우 `LaunchMinecraft.bat`을 실행합니다.
   - 베타/프리뷰 버전일 경우 `LaunchMinecraftPreview.bat`을 실행합니다.
3. Renderdragon Shader List에서 셰이더팩을 다운받아 리소스팩을 불러와 **글로벌 리소스**로 적용합니다.

**BetterRenderDragon**을 사용하지 못하는 경우 [**Matject**](https://github.com/faizul726/matject)을 사용할 수 있습니다.

<br>
<br>

## 문제 해결

> - **셰이더팩의 물, 하늘만 적용됩니다, 물, 하늘이 적용이 안됩니다.**  
> 마인크래프트를 재시작하면 대부분 해결됩니다.

> - **서버에 들어갔더니 셰이더가 작동하지 않습니다.**  
> 서버에 적용돼있는 리소스팩으로 인해 셰이더는 서버에서 제대로 작동하지 않을 수 있습니다.

> - **맵에 리소스팩을 적용했더니 세이더가 작동하지 않습니다.**  
> 글로벌 리소스로 활성화해주세요.

> [!NOTE]
> 위 사항 외의 버그 또는 문제는 셰이더 개발자에게 문의하세요.

---
* [Back to English](/docs/installation/README.md)