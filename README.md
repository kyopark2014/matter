# Matter

매터(Matter)는 [CSA (Connectivity Standards Alliance)](https://csa-iot.org/all-solutions/matter/)에서 만든 표준으로, 홈디바이스와 같은 IoT 디바이스들이 쉽게 연결될 수 있도록 하는 오픈 소스 기반의 응용계층(application layer) 연결 표준입니다. IP 기반으로 동작하며 WiFi 네트워크를 지원합니다. 국내의 경우를 보면 삼성전자는 스마트싱스를 이용해 접속하고, LG전자는 씽큐를 통해 연결성을 제공하는데, 삼성 TV와 LG 세탁기를 이용한다면 두 IoT 디바이스를 연결하기는 쉽지 않았습니다. 하지만, 삼성전자와 LG전자뿐 아니라 Amazon, Google과 같은 회사들이 매터에 참여하고 있으므로, 향후 디아비스를 통합하여 사용하는 방식에서 많은 개선이 가능할 것으로 보여집니다. 

메터의 Archictecture는 아래와 같으며, IPv6을 기반으로 응용계층(L7)의 프로토콜입니다. 


<img src="https://user-images.githubusercontent.com/52392004/208204331-d1e8d317-f0e5-4b61-a5c4-2d7cc5fc40fe.png" width="700">

## Reference

[CSA](https://csa-iot.org/all-solutions/matter/)

[Matter - GIT](https://github.com/project-chip/connectedhomeip)
