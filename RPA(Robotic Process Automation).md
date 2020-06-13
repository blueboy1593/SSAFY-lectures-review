# RPA(Robotic Process Automation)

테스트 자동화가 발달되어 업무의 처리 과정을 자동으로 해 주는 기술을 의미

- 빈도가 많고 대량으로 발생하는 작업
- 정해진 업무를 반복하는 작업
  - 자동으로 내용을 채워 발송되는 안내 메일
  - 자동으로 일정 양식에 금액을 입력하는 시스템(ERP시스템 등)

삼성 SDS에서 RPA 사업에 뛰어들었다.

RPA 분야에서 신입사원 채용이 많다고 함!!

## 해외 동향

### 일본 

- 업무개혁관련 법안이 가결되어 '리모트 워크' 및 '업무 자동화'의 니즈 증대

### 미국 

- Automation Anywhere사 및 UI Path사를 중심으로 시장이 46%씩 성장중

## 일반 자동화와 다른 점

1. 프로그래밍적 지식이 필요 없음
2. 소프트웨어를 아우르는 자동화
   - 소프트웨어 하나만 대상이 아닌
   - 여러 가지 소프트웨어를 자동화
3. 기존 시스템을 활용함
4. 저비용

## 3가지 클래스

### Class 1 지정된 업무만 자동화

- Selenium, RobotFramework 등으로 단일 업무 자동화
- EX)
  - MS Office + python WinAPI
  - Selenium, Python RobotFramework <== RPA 전용으로
  - 기타 자동화 프로그램

### Class2 머신러닝 등 AI를 활용

- Class1 방식은 사람이 짜 놓은 스크립트를 그대로 따라감.
- 좀 더 발전한 버전은 AI를 통한 과거 빅데이터 분석을 통해 효과적으로 진행할 수 있음.

### Class3 프로세스 ~ 의사결정 자동화

- 궁극적으로 RPA가 지향하는 단계이며 AI활용이 좀 더 발전한 모습
- 구체적 사용예는 없음.

### UI Path - 미국에서 핫한 회사!

## RPA의 종류

### 데스크톱 형

- 작업자 PC에서만 수행되는 형태
- 규모가 작은 간단한 작업에 적합
- 2017년도까지는 관리가 어려웠으나, 2018년도부터는 PC의 중앙관리가 가능해짐에 따라 많이 늘어남.
- 각각의 PC에 RPA 애플리케이션을 설치해서 사용한다.

### 클라우드 형

- 클라우드에 구축된 로봇을 웹 브라우저를 통해 접속하여 수행하고 결과를 다운받는 형태
- 온 프레미스 형태에 비해 도입 비용이 저렴
- IT 엔지니어가 아니더라도 쉽게 사용할 수 있는 UI

### 온 프레미스 형

- 사내 네트워크 내부에서 로봇이 수행되는 형태
- 이 형태 이외에 최근에는 AWS를 활용한 클라우드 + 온프레미스 형태도 많이 사용됨.

## 활용 사례

### 일본의 Dip 사

- 아르바이트 전문 사이트 baitoru.com 운영
- 동영상 업로드시 검수 작업에 RPA 활용
- RPA 프로세스 안에 AI를 심어서 사용한다.

### NH 농협은행

- 로봇은행원의 RPA를 도입
- 온프레미스형 서버를 사용한 것이다 아마도.
- 서울 서대문 NH농협은행 본점 4층에서 진행됨.
- 과거 Data를 가지고 AI를 통해서 3분만에 심사를 끝낸다.

Workflow라는 시스템이 발전되고 발전돼서 온거임.