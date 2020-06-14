# Network #5

## 방화벽이란

외부 네트워크(WAN)에서의 공격(해킹, 악성코드 등)으로부터 내부 네트워크(LAN)을 보호하는 방어 도구 및 시스템

## 종류

- Packet filter
- IDS / IPS
- Web Application Firewall

보통 L3 라우터와 하나의 시스템으로 나오는 방화벽이 많다!

## Netfilter

- 커널 모듈
- 패킷이 통과하는 5개의 Hooking 지점
- Filter, NAT, Mangle 등 Table 존재
- iptables 로 Table에 Rule 추가
- 방화벽, 공유기, 포트 포워딩 등 개발