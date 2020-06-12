# 네트워크2

## 지난 강의 복습

1. IP는 Subnet-Mask에 의해 Network와 Host로 분리

2. Network 가 동일하면 Local Area Network

   => L2 Switch가 MAC를 보고 목적지 결정

3. Network 가 다르면 Wide Area Network

   => L3 Router 가 IP를 보고 목적지 결정

4. ARP : Local Area Network에 있는 특정 IP를 가진 Host의 MAC를 얻어온다.

5. ICMP : IP를 가진 Host와 통신이 되는지 확인

   ex) ping 192.233.33.35

### ARP Table

IP 주소가 등록이 되고 IP와 MAC 주소를 채워야함.

MAC 주소를 받아서 L2 Switch로 보내는 것임.

출발지와 도착지의 MAC 어드레스가 있다.

ARP 테이블은 Dos 커맨드에서 아래 명령어로 확인 가능하다!!!

```
arp -a
224.0.0.22
이거는 특수 목적으로 지정해놓은 IP
```

### L2 Switch

- IP를 볼 필요가 없다.
- 앞에 헤더만 보고 어디로 보낼지 결정하면 되는 것임.

패킷을 구성할때 Wan으로 나가는 것인지 Lan으로 나가는 것인지 구별해서 한다.

라우팅 테이블을 만들어둬.

Response 패킷을 만들 수 있어야 한다.

Mac 주소의

```
98:2c:bc 얘는 인텔
여기까지는 제조사를 의미하는 경우가 많다고 한다.
50:77:05 얘는 삼성!
```

IPV4 = Internet Protocol Version 4

ICMP = Internet Control Message Protocol

Wireshark를 개념적으로 알고 있으면 문제해결에 도움이 된다.

ARP를 request하는 것은 broadcast하는 것이고 response는 응답!! 암튼.