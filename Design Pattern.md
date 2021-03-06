# Design Pattern

GoF의 디자인 패턴 이라는 책이 있다

- 건축물을 짓는 몇 가지 패턴을 이야기한 책의 제목
- Gang of Four(OOS에 큰 기여)
- 23개 패턴 기재
- 생성
- 구조
- 행위

### 디자인 패턴

- 일종의 설계 노하우의 모음
- 선배들로부터 배우는 문제 해결 방법
- 만병통치약은 아님, 적절하게 쓰일 때 위력적

자료구조, 알고리즘, 디자인 패턴이 원래 3인방이었다!!

### 약간 퇴보한 이유

- 프레임워크 내에서의 프로젝트 수행 환경으로 접할 기회 적어짐
- 프레임워크는 디자인 패턴이 적용된 반제품
- 프레임워크 이해와 OOS 개발을 위해 필요

### 언제 사용하는가?

- 서버에 캐시 저장소를 직접 구현해야 하는 상황
- 데이터를 다루는 저장소이기에 유일한 인스턴스여야 함
- "선배들의 발자취를 따라가보자" == "디자인 패턴을 들여다 보자"
- 'Singleton pattern' 과의 만남

### 특징

- 언어에 종속적이지 않음
- 문제 해결법 공유 관점에서 알고리즘과 유사
- 개발 환경마다 최적화된 구현체 존재 가능

### Observer

- 한 객체의 상태가 바뀌면 그 객체에 의존하는 다른 객체들에게 연락
- push, poll 데이터 전달 2가지 방식

### 확장

- 오픈 소스 분산 메세징 시스템
- 발행-구독(publish-subscribe) 모델을 기반으로 동작
- 하나의 개념 >> 프레임워크 / 아키텍쳐로 확장

### 남용

- '남용', '겉멋'은 금물

## 결론

1. 디자인 패턴은 '스타일'이 아니고 OOS를 할 때의 설계.

2. 객체 지향 소프트웨어 구현 시에 주요 고민 포인트 정리.

   내가 뭘 해야 나아질지에 대한 고민을 선배들이 해둔 것이다.

3. 내가 뭘 생각해 봐야 할 지에 대해 요약.

4. 단순한 코딩을 넘어 객체 설계에 대한 관심 필요

5. 힘을 빼고 접근하는 것도 중요.

