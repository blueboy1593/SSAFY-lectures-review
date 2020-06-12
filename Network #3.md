# Network #3

## 목차

1. TCP 정의
2. 네트워크의 문제
3. 흐름 제어, 오류 제어 방법
4. CRC

## TCP

1. 신뢰성 통신

2. Transport Layer

3. 흐름 제어, 오류 제어, 혼잡 제어

   - 에러 제어 : 신호 감쇠(Attenuation), 번개, 지진, 정전, 고장 등 (Disaster)
   - 흐름 제어 : 보내는 곳과 받는 곳의 속도가 다를 때 해결해 주는 것이다. - 처리율 차이(throughput)
   - 혼잡 제어 : 중간에 있는 패킷의 용량이 더 작으면 혼잡 상황이 발생함. - 혼잡(Congestion)

   얘네들이 다 TCP가 필요한 이유!!

4. Streaming, 연결형

MSS - Maximum Segment Size

패킷을 세그먼트 단위로 나눠서 보내는 것이다!!!

### 패킷으로 나눠서 보낼 때 생기는 문제

- 나누어서 보내면 순서대로 보내도 순서대로 도착하지 않을 수 있다.
- TCP에서는 queue에 넣어서 커널 개발자가 순서대로 받을 수 있게끔 한당.

상대방 속도에 맞춰서 ACK로 흐름 제어 해서 보낸다

Stop and Wait - 하나 보내고 기다렸다가 다음꺼 받고 뭐 이런 느낌인가...

### Sliding Window - 조금 더 개선한 방식

TCP에서 사용하는 방식이라고 한다!!!

Seq 값은 Len 값을 더한게 된다.



## 다음 강의

1. 혼잡 제어
2. 3-way handshake
3. 4-way handshake
4. Wire shark