![9ba05b63c09f2483916d7ac04379c29a1](https://user-images.githubusercontent.com/75381985/219609891-932a76c6-b85d-44d2-b5a9-82e5b0841ad2.jpg)

## AlwaysFine
>이거 만들 시간에 공부했으면 전교 1등 했다.

**AlwaysFine**은 미세먼지와 초미세먼지 정보를 바탕 화면에 표시하는 [Rainmeter](https://www.rainmeter.net/) 스킨입니다. 대한민국 내 모든 측정소를 지원하며, 누구나 쉽고 빠르고 정확하게, 직관적으로 미세먼지와 초미세먼지 정보를 확인할 수 있습니다.

## 제작 동기
2022년 제물포고등학교 1-2에서 미세먼지 수치를 매일 측정하고 이를 칠판에 기록하는 역할을 담당했는데 그게 귀찮아서 만들었습니다. 사실 봉사시간 때문에 개발하고 나서도 계속 칠판에 기록했습니다. 애플리케이션 개발이 귀찮기도 하고 빠르게 만들고 싶어서 Rainmeter를 사용했는데, 그냥 네이티브 애플리케이션으로 만들 걸 그랬습니다.

## 특징
 * 대한민국 환경부와 WHO 기준이 아닌, 더 엄격한 자체 기준을 사용합니다.
 * 1시간 단위로 자동 갱신되며, 이는 변경이 불가능합니다. (의도된 동작)
 * 측정소 변경을 지원하나 재시작 시 기본값으로 바뀝니다. (의도된 동작)
 * 자동 업데이트를 지원합니다.
 
## 이용 범위
이 스킨은 저작권법으로 보호받고 있으며 저작권자의 동의 없이 이용하실 수 없습니다. 현재 이용이 가능한 곳 중 하나는 2022년 제물포고등학교 1-2 컴퓨터가 있습니다. 이곳의 경우 학년이 바뀌긴 했지만 지우는 걸 깜박해서 그냥 쓰셔도 됩니다. 다른 곳에서 이 스킨의 사용을 원하는 경우 akdwc2843@gmail.com으로 연락하면 답변드립니다.

참고나 학습 용도의 사용은 가능하나 저작권자를 알아볼 수 없게 하는 행위, 무단 배포 등은 금지되어 있습니다.
 
## 사용 방법
![1](https://user-images.githubusercontent.com/75381985/219388588-dd9b30b7-b663-49f6-9942-12f658323cad.png)

스킨을 실행하면 나오는 화면입니다. 미세먼지, 초미세먼지의 수치와 등급이 나오고, 등급에 따라 이모티콘과 배경 색상이 바뀝니다. 측정소는 송림 측정소(제물포고등학교와 가장 가까움)가 기본이며, 등급은 매우 좋음, 좋음, 양호, 보통, 나쁨, 매우 나쁨, 심각, 최악으로 총 8단계입니다.

![2](https://user-images.githubusercontent.com/75381985/219388653-df439cec-fd23-4687-a782-c711826d8c6d.png)

미세먼지와 초미세먼지 수치에 마우스를 올려두면 해당 등급의 범위와 행동 지침을 볼 수 있습니다.

![3](https://user-images.githubusercontent.com/75381985/219388708-74f90d27-c51c-4913-859e-94a7091b27c5.png)

왼쪽 위 아이콘을 누르면 설정창이 열리며 마우스를 올려두면 현재 측정소와 기준 시간이 나옵니다.

![4](https://user-images.githubusercontent.com/75381985/219388756-0e6af852-766f-4964-bfc1-1bbfaa1a1fdf.png)

설정창입니다. 입력창에 원하는 측정소의 이름(예: 송현)을 입력한 후 엔터를 누르면, 측정소 위치가 바뀝니다. 입력창이 사라진 경우 설정창을 닫은 후 다시 여세요. 그 아래는 버전 정보입니다. 인터넷에 문제가 있는 등 특별한 경우가 아니면 자동 업데이트를 지원하기에 항상 최신 버전으로 나오는 것이 정상입니다. 또한 아래의 두 링크는 각각 미세먼지 측정소 목록과 이 페이지로 연결되는 링크입니다.

![5](https://user-images.githubusercontent.com/75381985/218766535-19fb3ba5-335f-43cb-b590-969b0d8ce1e5.png)

측정소가 점검 중이거나 문제가 생긴 경우 다음과 같이 표시됩니다.

## 기타
 * 이후 심각한 버그가 아니면 바빠서 업데이트는 없을 예정입니다. 이 스킨은 제가 보기엔 완벽합니다.
 * 스킨 크기가 지나치게 크고 깨지는 경우 : Rainmeter가 설치된 폴더에 들어가 Rainmeter.exe 우클릭 후 호환성 설정에서 높은 DPI 설정 재정의. Rainmeter는 HiDPI를 지원하지 않아 기존에는 별도의 플러그인을 사용했으나, 외부 코드를 사용하는 것을 원치 않아 제거했습니다. 수동으로 설정해주셔야 합니다.
 * [한국환경공단 에어코리아 대기오염정보 오픈 API](https://www.data.go.kr/data/15073861/openapi.do) 사용.
