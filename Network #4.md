# Network #4

## 목차

1. 복습 : 오류, 흐름제어
2. 혼잡 제어
3. Kernel 내부 구조, Streaming
4. 3-Way, 4-Way handshake
5. Wire shark

### MSS

1. Maximum Segment Size
2. TCP에서 전송하는 User Date(L5 ~ L7)의 최대 크기
3. MSS = MTU - L3 Header size - L4 Header size
4. 연결 시(3-way hand), MSS 교환 후 작은 것 사용

### Streaming

- Data가 MSS로 나누어 전송되는 것.

송신 전, 수신 측의 MSS, RWND 필요, Kernel mem에서 기능들 생성

네트워크는 다른 강의나 정리 다시 한번 봐야할 듯...

쉽게 정리된 블로그 보는게 가장 좋을 것 같다!