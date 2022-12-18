# Matter

매터(Matter)는 [CSA (Connectivity Standards Alliance)](https://csa-iot.org/all-solutions/matter/)에서 만든 표준으로, 홈디바이스와 같은 IoT 디바이스들이 쉽게 연결될 수 있도록 하는 오픈 소스 기반의 응용계층(application layer) 연결 표준입니다. IP 기반으로 동작하며 WiFi 네트워크를 지원합니다. 국내의 경우를 보면 삼성전자는 스마트싱스를 이용해 접속하고, LG전자는 씽큐를 통해 연결성을 제공하는데, 삼성 TV와 LG 세탁기를 이용한다면 두 IoT 디바이스를 연결하기는 쉽지 않았습니다. 하지만, 삼성전자와 LG전자뿐 아니라 Amazon, Google과 같은 회사들이 매터에 참여하고 있으므로, 향후 디아비스를 통합하여 사용하는 방식에서 많은 개선이 가능할 것으로 보여집니다. 

메터의 Archictecture는 아래와 같으며, IPv6을 기반으로 한 응용계층(L7)의 프로토콜입니다. 


<img src="https://user-images.githubusercontent.com/52392004/208204331-d1e8d317-f0e5-4b61-a5c4-2d7cc5fc40fe.png" width="700">

### Connectivity

매터는 WiFi아 Thread를 주된 무선 연결 프로토콜로서 사용합니다.

#### Thread 

Thread는 배터리를 사용하는 디바이스들이 높은 에너지 효율을 가질수 있도록 해줍니다. 센서나, 도어락, Smart Plug나 전등등이 해당됩니다.

- IPv6 (6LoWPAN)을 이용합니다.
- Low Rate WPAN인 802.15.4 위에서 동작합니다. 

<img src="https://user-images.githubusercontent.com/52392004/208269729-f81b96ea-bcd7-46ff-8626-fc7bf995c2e7.png" width="700">


#### WiFi

WiFi는 Thread보다는 더 많은 에너지를 사용하는데, 더 높은 대역폭을 가지고 보안 카메라나 비디오 도어락등에 활용됩니다. 




### Security

128bit AES-CEC을 이용하여 AES-128-CCM로 Encription을 수행합니다.

## Reference

[CSA](https://csa-iot.org/all-solutions/matter/)

[Matter - GIT](https://github.com/project-chip/connectedhomeip)

[Matter: A Unified Approach to IoT Device Development - SILICON LABS](https://www.silabs.com/wireless/matter?tab=start#wi-fi)

[What is THREAD?](https://www.threadgroup.org/BUILT-FOR-IOT/Smart-Home)

[Using the Matter standard - aws](https://docs.aws.amazon.com/privateca/latest/userguide/matter.html)
