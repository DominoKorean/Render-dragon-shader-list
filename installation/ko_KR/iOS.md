
# iOS 렌더드래곤 셰이더 설치법

## 목차

* [IPA 추출](#ipa-추출)
* [Filza 사용](#filza-사용)
* [IPA Sideload](#ipa-sideload)

## IPA 추출
렌더드래곤 셰이더를 설치하기 위해서는 마인크래프트의 렌더파일을 수정해주어야합니다.  
그러기위해서는 마인크래프트를 IPA로 추출한 뒤 다시 설치해주어야하며 이를 위해서는  
PC가 필요합니다. (탈옥을 한경우에는 Filza를 사용하는것을 추천드립니다. [Filza 사용](#filza-사용))

Windows에서는 iMazing을 이용해 추출할 수 있습니다.  
먼저 [iMazing](https://imazing.com/?gad=1&gclid=Cj0KCQjwoK2mBhDzARIsADGbjeoNt1rkkKWWJVaawEFnsUmV3QjthBa3UjxAL7h_cefyqWyxDuxRis8aAvGIEALw_wcB)을 설치해줍니다.  
그 후 아이폰을 USB를 통해 PC에 연결해줍니다.  
iMazing의 설치가 다되었다면 평가판 계속 사용하기를 누른 후 앱 관리에 들어가줍니다.  
그 후 앱관리에서 마인크래프트를 우클릭 한 뒤 .IPA파일을 설치를 눌러줍니다. (프로그램 내에 한국어 번역이 잘못돼있음)  
IPA를 추출하였다면 Bandizip과 같이 압축파일을 열 수 있는 프로그램을 통해 파일을 열어줍니다.  
그 후
```
Payload\minecraft.app\data\renderer\materials
```
폴더로 들어가 다운로드 받은 material.bin 셰이더파일을 덮어씌워줍니다.  
마지막으로 마인크래프트를 Sideload를 통해 다시 설치해주면 됩니다.

## Filza 사용
먼저 [Filza](https://filzadownload.com/)를 설치해줍니다. (탈옥이 안된 기기일 경우 외부 PC를 통해 Sideload 해주어야 합니다.)  
Filza를 설치했다면
```
var\containers\Bundle\Application\Mincraft\minecraftpe.app\data\renderer\materials
```
폴더에서 materials 폴더를 백업해줍니다.  
그 후 다운로드받은 렌더드래곤 셰이더 파일을 선택 한 후 복사 해준 뒤  
다시 위 경로로 가 material.bin 파일을 덮어씌워줍니다.

## IPA Sideload
탈옥하지 않은 기기의 경우 IPA를 설치하기 위해 외부 PC를 통해 Sideload 해와야합니다.    
Sideload 프로그램을 통해 가능하며 아래와 같은 프로그램이 있습니다.
* [AltStore](https://altstore.io)
* [Sideloadly](https://sideloadly.io)