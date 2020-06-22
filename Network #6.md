# Network #6

### 공유기란

Private IP를 가진 다수의 Host가 Public IP 한 개를 나누어 사용하는 장비

공인 IP는 하나만 받게 되는 것이다!! 그리고 다수의 host들이 이용을 할 것임.

LAN에서 WAN으로 패킷을 보내기 위해서는 Default Gateway가 있어야 한다.

LAN 포트와 WAN 포트를 구분할 수 있다!! 어디와 연결하는지가 중요한 거겠지 ㅎㅎ.

### NAPT

- Network Address Port Translation
- LAN과 WAN을 연결할 때 사용하는 경우가 있다.
- Private IP를 Public IP로 바꾸는게 바로 냅트 기술임
- 그때 그때 사용하지 않는 port를 찾아서 rule을 만드는? 뭐 그런거...

OSI 7계층에 대해서 나중에 공부해보기!!

### Request Packet & Response Packet

L2

L3 ~ L4 : 출발지(source) IP, port 도착지(destination) IP, port

L5 ~ L7 : User의 Data

결국 LAN으로 우리집에서 소통하고 WAN으로 인터넷 회사와 통신하는 건데 request랑 response로 패킷들을 왔다갔다 하면서 주고받는거.

### Kernel

1. Prerouting

   Portforwarding 기능

2. Forward

   Firewall 방화벽 기능

3. Postrouting

   NAT테이블 추가하게 되면, 공유기 등 장비

Rule들을 추가하는 프로그램은 IPtables이다.