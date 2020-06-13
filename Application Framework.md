# Application Framework

특정 Platform에서 동작하는 Application이 공통적으로 사용하게 될 라이브러리와 뼈대(Frame)를 이루는 규약을 정의해 모아둔 집합체

## Web Frontend Framework 3대장

- Angular
  - 2010년에 구글에서 처음 출시
- React
  - Facebook에서 나왔고 대부분의 점유율을 차지하는 중
  - Typescript와 뗄레야 뗄 수 없는 관계
- Vuejs
  - 가장 쉬운 프레임워크로 알려져 있음.
  - 개인이 만든 프레임워크

## Mobile Native App Framework

- Android Application Framework
- IOS CocoaTouch

보통은 두가지를 동시에 하는 경우가 없다.

## Mobile Hybrid App Framework

껍데기는 studio로 되어있지만 내부적으로는 Web framework가 적용되어 있다.

- React Native
  - 2013년 Facebook에서 출시됨.
- Flutter
  - 구글에서 나옴
  - 하이브리드 프레임워크
- Ionic
- Xamarin

## Embedded System Application Framework

사람들이 어렵다고 착각하는데 웹앱 적용이 많이 되었다.

특정한 목적으로 프로그래밍된 전용 장비.

라즈베리 파이 - 파이썬을 많이 사용한다.

- MFC Visual C++

  MFC는 어렵고 이를 할 줄 아는 개발자는 각광을 받고 있다.

  터치스크린이나 카페 이런거는 window가 적용된거.

- WinForm C#

- HTML5 + JS

  - 스마트 ++ 로 나오는 것들이 웹기반으로 하는 것이다.
  - NPU가 성능이 비약적으로 향상하면서 웹브라우저를 많이들 사용한다.
  - 앞으로도 미래가 밝다.

- Qt - 굉장히 오래된 시스템

  - 고가 연구장비, 고가 자동차 등에 사용하는 시스템

- GTK +

  - 공짜인데 의외로 많이 상업용으로는 사용하지 않고, 교육용으로 사용함.

과거에는 MPU 성능이 PC에 비해 너무나 낮아 모바일 및 임베디드 시스템에서는 각 MPU에 최적화된 바이너리 형태로 S/W가 개발될 수 밖에 없었다.

고성능 웹브라우저 엔진 출시

- Webkit
- Chromium

SPA / PWA 등장으로 웹기반 어플리케이션에서 정교한 Life-cycle 및 Event Handling 구현 가능

모바일 / 임베디드 분야에서도 웹앱 / 하이브리드앱의 폭발적인 점유율 증가가 진행중

React / Vue.js 등으로 웹프론트 개발만 하였더라도 모바일앱 / 임베디드 Application 개발이 가능함

SPA를 할 줄 아는 것이 중요한 거지, 어떤 프레임워크를 사용했는지가 중요한 것이 아니다.