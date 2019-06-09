# Unofficial Resume

이력서에서 다 하지 못한 이야기를 하는 Un Official Resume입니다.

# 자기 소개

저의 이름은 용찬호이고, 94년생 만 24세입니다. 클라우드를 좋아합니다. 항상 더 나은 클라우드 아키텍처와 자동화를 꿈꿉니다.

<div contenteditable="plaintext-only"><p align="center"><img width="400" src="https://github.com/alicek106/unofficial-resume/blob/master/jpg/7.jpg?raw=true"></p></div>



## 좋아하는 어구

[Kubernetes the Hard Way를 작성한 사람](<https://github.com/kelseyhightower>)은 이렇게 말했습니다.

**너가 열심히 노력해서 성공했으면, 다른 사람도 똑같이 그렇게 되도록 도와라**

혼자서 잘 되는 것은 아무 의미가 없습니다. 그렇기 때문에 지식의 전파와 재창조의 가치를 중요하게 생각하고 있습니다.



## 취미

커피 핸드드립을 매우 좋아합니다. 나중에 돈 많이 벌면 블루마운틴, 하와이 코나를 매일 내려 먹고 싶습니다.

<p align="center"><img width="400" src="https://github.com/alicek106/unofficial-resume/blob/master/jpg/4.jpeg?raw=true"></p>

피아노 치는 것을 너무너무 좋아합니다. 최근에 쳤던 피아노 곡은 [Animenz의 Tokimeki Poporon](https://www.youtube.com/watch?v=eIPsF6xOI_Q&t=135s) 입니다 (완주) 

그림 그리는 것이 즐겁습니다. 가끔씩 트위치에서 그림 방송도 합니다.

소설 쓰는 것을 좋아합니다만, 막상 쓰려고 하면 생각하는 것에 시간을 너무 뺏기기 때문에 자주 소설을 쓰는 편은 아닙니다.



## 특허 및 표준 목록

1. [2017.07] 국제 표준 (ITU-T Geneve) Study Group 13, Working Party 2, Question 17 CCCM (Cloud Computing Container Micro-service) Contribution-0154: [Use case of micro-service discovery and gateway for coordination and provision]

2. [2017. 12] 특허 출원 (10-2017-0167191) 컨테이너 이주 방법, 상기 방법을 수행하기 위한 컴퓨팅 장치 및 컴퓨팅 시스템

3. [2018. 04] 국제 표준 (ITU-T Geneve) Accepted with Modification Study Group 13, Working Party 2, Question 17 CCDC (Cloud Computing Distributed Cloud) Contribution-0110: [Use case of Intelligent Transportation System on distributed cloud]

4. [2018. 04] 국제 표준 (ITU-T Geneve) Accepted with Modification Study Group 13, Working Party 2, Question 17 CCDC (Cloud Computing Distributed Cloud) Contribution-0110: [Use case of content delivery service on distributed cloud]
5. [2018. 12] 특허 출원 (P-181214R) 컨테이너 가상화 환경에서의 성능 간섭 최소화를 통한 최적의 처리 시간 보장 방법



## 수행한 프로젝트 목록 (학부 ~ 대학원)
[제 블로그](https://blog.naver.com/alice_k106)에서 프로젝트 수행 기간에 작성된 포스트를 보시면 어떤 개발을 어떻게 진행했는지 대략적으로 확인하실 수 있습니다.

- 프로젝트 명 : **실시간 모바일 클라우드 연구센터 개발 산출물 통합을 위한 쿠버네티스 기반의 클라우드 플랫폼 개발**

  - 공식 과제 명 : 대학 ICT 연구센터 실시간 모바일 클라우드 (IITP)
  - 수행 기간 :  2018. 06 ~ 2019. 01
  - 사용 기술 스택 : **Kubernetes, Flask, Python 등**
  - 세부 사항 : 여러 대학의 연구실에서 개발된 애플리케이션을 통합해 컨테이너 서비스로서 제공하는 것을 목표로 하는 프로젝트입니다. 플라스크 MVC, 쿠버네티스에서 제공되는 SDK를 이용해 프론트엔드 웹 대시보드와 쿠버네티스 제어를 위한 API 서버를 개발하였습니다. 각 대학의 연구실에서 산출된 소스코드를 도커 이미지화해 동적으로 클라우드 플랫폼에 추가하기 위해 이미지를 import할 수 있는 인터페이스를 설계하고, 등록된 애플리케이션을 사용자가 직접 생성해 컨테이너와 서비스를 직접 제어할 수 있도록 구현하였습니다. 

  ------

- 프로젝트 명 : **서비스 이동 지원을 위한 분산형 클라우드 핵심 원천 기술 연구**

  - 공식 과제 명 : 대학 ICT 기초 연구실 (IITP)
  - 수행 기간 : 2018. 03 ~ 2018. 12
  - 사용 기술 스택 : **Python, Docker Swarm Mode, Spring Framework, CAdvisor, InfluxDB, Flask, 라즈베리파이 등** 
  - 세부 사항 : 에지 컴퓨팅을 제공하기 위한 컨테이너 기반의 분산 클라우드 환경 구축과 에지 노드의 모니터링 시스템 개발을 담당하였습니다. 엣지 노드 클러스터에서 서비스 요청을 자체적으로 처리할 수 있도록 MQTT 기반의 파이썬 에이전트를 개발하였습니다. 에이전트는 iptc 패키지를 이용해 NIC의 패킷을 조사 (Inspection) 한 뒤 iptables의 DNAT를 이용해 적절한 에지 노드로 라우팅하는 일종의 SDN으로서 구현하였습니다. 서비스 배포 및 관리를 위해 도커 스웜 모드를 기반으로 개발하였습니다. 각 클라우드 레이어 및 에지 노드의 자원 사용량을 실시간으로 수집하기 위해 InfluxDB, CAdvisor, Grafana, Prometheus 등을 도커 스웜 모드에서 마이크로서비스 형태로 배포해 모니터링 시스템을 구축하였습니다. 저장된 자원 사용량 데이터 값을 도커 대시보드 등과 같은 외부 모듈에서 사용할 수 있도록 플라스크 기반의 REST API 서버를 Exporter로서 개발해 사용하였습니다.

  ------

- 프로젝트 명 : **Qemu, Libvirt 기반의 가상 머신 제어를 위한 REST API 서버 개발 - 개발 및 유지 보수**

  - 공식 과제 명 : 중소기업청 기술혁신개발사업
  - 수행 기간 : 2017. 12 ~ 2018. 05
  - 사용 기술 스택 : **QEMU, KVM, Libvirt, PHP, Apache Web Server**
  - 세부 사항 : Qemu의 가상 머신을 기반으로 여러 사용자에게 가상 머신의 화면을 공유해 협업 시스템을 제공하기 위한 VDI 클라우드 플랫폼 구현을 목표로 하는 프로젝트입니다. 저는 가상 머신을 제어하기 위한 Libvirt API 서버를 개발하고 유지보수하는 역할을 담당하였습니다. REST API를 통해 클라우드 플랫폼에 등록된 인프라 서버에 가상 머신을 생성 및 삭제하고 관련 정보를 제어하는 기능을 개발하였습니다. 기존에 사용되던 Qemu 명령어를 Libvirt에 호환되는 xml로 변환하고 이를 API 서버에서 템플릿으로서 사용하도록 구현하였습니다. Apache 웹 서버에서 PHP를 사용해 Libvirt를 사용하였으며, 인프라 서버에서는 Qemu와 Libvirtd를 통해 가상 머신을 제어할 수 있는 환경을 구성하였습니다.qcow2의 Copy-on-Write 기능을 활용해 수초 내로 가상 머신을 생성하고 시작하는 기능을 추가함으로써 실시간으로 (수 초 내) 가상 머신을 생성할 수 있도록 하였습니다.

  ------

- 프로젝트 명 : **IoT 환경에 컨테이너 수준의 가상화 도입을 위한 실시간 컨테이너 연구 및 개발**

  - 공식 과제 명 : IoT 향 소프트웨어 요소기술 분석 (삼성)
  - 수행 기간 : 2017. 04 ~ 2017. 12
  - 대외비입니다.

  ------

- 프로젝트 명 : **HPC 환경에서 클라우드 서비스 적용을 위한 기술 연구**

  - 공식 과제 명 : HPC 환경에서 클라우드 서비스 적용을 위한 기술 연구 (한국과학기술정보연구원)
  - 수행 기간 : 2017. 03 ~ 2017. 12
  - 대외비입니다.

  ------

- 프로젝트 명 : **도커 컨테이너 기반의 실시간 모바일 클라우드 연구 및 개발 (학부 졸업 작품)**

  - 공식 과제 명 : 대학 ICT 연구센터 실시간 모바일 클라우드
  - 수행 기간 : 2016. 06 ~ 2017. 01
  - 사용 기술 스택 : **Zookeeper, Apache Tomcat, Calico, Flocker, MongoDB, AWS, Docker Registry, Spring, Jquery & bootstrap 등**
  - 세부 사항 : 오케스트레이션 툴의 도움 없이 컨테이너 기반 클라우드 플랫폼을 처음부터 끝까지 설계해 개발하는 것이 목적이었습니다. Worker, Master 에이전트를 직접 개발해 서버에 실행시켰으며, Metrics 수집, 컨테이너 및 호스트의 Discovery와 Fail 감지를 수행하도록 구현했습니다. 컨테이너, 호스트의 자원 사용량을 에이전트로 수집해 MongoDB에 저장하고, 웹페이지에서 시각화했습니다. Flocker를 통해 Persistent Storage Pool을 구성하고 이를 컨테이너에 마운트하는 방식으로 제공했습니다. 각 컨테이너를 프로젝트 단위로 추상화한 다음, 네트워크 간의 접근 제한 및 SSH 접근 제한 설정을 수행하는 일명 키스톤 서버를 구축했습니다. 이러한 요청을 처리하는 API 서버와 GUI를 제공하는 웹 서버를 별도로 구성해 서비스를 제공하는 워크플로우를 구성했습니다.

  ------

- 프로젝트 명 : **경희대학교 실시간 모바일 클라우드 연구센터 서버실 및 클라우드 관리자**

  - 수행 기간 : 2016. 06 ~ 2018. 12
  - 사용 기술 스택 : **Ansible, MQTT, Xen**
  - 세부 사항 : 경희대학교의 클라우드 및 보안 연구실에서 자체적으로 운영하고 있는 약 40대의 서버 관리자를 2년간 담당하였으며, 서버를 클러스터링함으로써 내부 클라우드를 구축해 연구실 인원에게 제공하였습니다. Xen 기반의 가상 머신 클라우드를 구축하였으며, NAS 의 iSCSI 스토리지를 가상 머신에 연결해 동적으로 인스턴스를 생성하도록 설정하였습니다. 석사 기간 중 쿠버네테스 및 자체 개발 클라우드 플랫폼을 도입해 간단한 CLI 개발 환경을 제공하는 컨테이너 인스턴스를 사용자 스스로가 웹 대시보드에서 직접 생성할 수 있도록 개발하였습니다. 앤서블과 MQTT를 통해 많은 서버들을 효율적으로 다룰 수 있도록 시스템을 구축했습니다.

  ------

- 프로젝트 명 : **대규모 기상 데이터 수집 및 제공 서비스를 위한 분산 MQTT 브로커 모델 설계 및 개발**

  - 공식 과제 명 : NIA 넷챌린지 캠프
  - 수행 기간 : 2016. 03 ~ 2016. 12
  - 사용 기술 스택 : **MQTT, Java, InfluxDB**
  - 세부 사항 : 기상 데이터 수집을 위한 스테이션으로부터 MQTT 통신을 통해 대규모의 기상 데이터를 수집해 공공데이터로서 활용하는 것을 목표로 하는 프로젝트입니다. 저는 부하 분산 및 고가용성을 위한 MQTT 브로커 모델의 설계를 담당하였으며, 설계 내용을 JAVA 기반의 오픈소스 MQTT 브로커인 ‘Moqutte’에 반영해 컨테이너 애플리케이션으로 새롭게 개발하였습니다. 부하 분산 및 장애 복구 기능을 위해 Master 브로커와 Slave 브로커 모델을 제안하고 이를 구현해 기상 데이터를 수집하였습니다. 또한 브로커를 도커 컨테이너로 구성함으로써 부하 발생 시에도 클라우드 서버에서 빠르게 확장해 대응할 수 있도록 개발하였으며, 각 브로커의 자원 사용량 모니터링을 위해 InfluxDB 기반의 텔레메트리 시스템 및 Auto-scaling 기능을 구현하였습니다.

  ------

- 프로젝트 명 : **Thin-Gateway 모니터링 기능 및 빅데이터 통합 분석을 활용하는 복합센서모듈 및 클라우드 서비스 플랫폼 개발**

  - 공식 과제 명 : 중소기업청 기술혁신개발사업
  - 수행 기간 : 2016. 06 ~ 2016. 12
  - 사용 기술 스택 : **라즈베리파이, NodeJS, BLE, MQTT**
  - 세부 사항 : 협업사에서 개발한 BLE 복합 센서 모듈으로부터 수집되는 데이터를 클라우드에 저장한 뒤 이를 사용자 대시보드와 안드로이드 애플리케이션에서 확인할 수 있도록 제공하는 것이 목표인 프로젝트입니다. 저는 복합 센서 모듈과 게이트웨이를 연동해 데이터를 수집하는 부분을 담당해 개발하였습니다. 복합 센서 모듈을 게이트웨이와 연결해 각 센서의 데이터를 MQTT 프로토콜을 통해 클라우드로 전송하도록 구현하였습니다. 게이트웨이는 라즈베리파이 3을, 에이전트는 NodeJS를 통해 개발했습니다.

  ------

- 프로젝트 명 : **요양원 환자를 위한 실증 서비스 구축**
  - 공식 과제 명 : 글로벌플랫폼 기반 헬스케어 서비스 실증 사업
  - 수행 기간 : 2015. 10 ~ 2016. 01
  - 사용 기술 스택 : **Android, Java, NodeJS, BLE, Beacon, MQTT, 라즈베리파이**
  - 세부 사항 : 요양원 내의 치매 환자의 움직임을 BLE 밴드와 게이트웨이를 통해 모니터링하고, 수집된 데이터를 클라우드에 지속적으로 저장해 요양보호사의 앱에 제공함으로써 치매 환자 사고를 미연에 방지하는 것을 목표로 하는 프로젝트입니다. 저는 게이트웨이의 설계 및 개발, 협업 개발사와의 데이터베이스 연동, 서비스 제공을 위한 안드로이드 애플리케이션 개발을 맡아 수행했습니다. 치매 노인의 배변 알람, 위험 알람, 배회 알람 및 BLE 비콘 센서를 이용한 치매 환자 인식 기능을 안드로이드 애플리케이션에서 사용할 수 있도록 만들었습니다. 

------

- 프로젝트 명 : **가상공간기반 실세계 사용자 선택형 스트리밍 서비스 플랫폼**
  - 공식 과제 명 : 중소기업청 기술혁신개발사업
  - 수행 기간 : 2015. 01 ~ 2016. 10
  - 사용 기술 스택 : **Hadoop, HBase, Tomcat, Java**
  - 세부 사항 : 처음으로 맡은 개발 프로젝트입니다. 하둡과 HBase를 도커 컨테이너로 구성해, Worker 개수를 입력하기만 하면 1분 안으로 빅데이터 처리 플랫폼을 구축해 개발자에게 제공하는 PaaS를 구축했습니다. 하둡과 HBase를 도커 이미지로 만든 뒤 도커 SDK를 통해 자동으로 컨테이너 클러스터를 제공한 뒤, SSH로 Master 컨테이너에 붙어 하둡 명령어를 사용할 수 있도록 만들었습니다. REST API와 대시보드 GUI로 컨테이너를 생성, 삭제할 수 있도록 개발했습니다.

------

#### 

## 논문 출판 내역
1. Nguyen, D. T., et al. "An index scheme for similarity search on cloud computing using mapreduce over docker container." Proceedings of the 10th International Conference on Ubiquitous Information Management and Communication. ACM, 2016.
2. 박나연, et al. "유동적 노드 그룹핑을 위한 MQTT 노드 관리 플랫폼 설계." 한국정보과학회 학술발표논문집 (2016): 2065-2067.
3. 용찬호, 이승형, and 허의남. "Docker 컨테이너 기반의 영상처리 서비스 패키지 모델." 한국정보과학회 학술발표논문집 (2016): 1650-1652.
4. 용찬호, 손동영, and 허의남. "블록 입출력 히스토리 학습을 통한 컨테이너 레이어 파일 시스템 분류 기법." 한국통신학회 학술대회논문집 (2017): 914-915.
5. 용찬호, 박준학, and 허의남. "컨테이너 기반의 HPC 클라우드 환경 구축을 위한 컨테이너 성능 및 특징 연구." 한국정보과학회 학술발표논문집 (2017): 94-96.
6. 용찬호, et al. "서비스 맞춤형 컨테이너를 위한 블록 입출력 히스토리 학습 기반 컨테이너 레이어 파일 시스템 선정 기법." 정보처리학회논문지. 컴퓨터 및 통신시스템 6.10 (2017): 415-420.
7. 용찬호, 우성윤, and 허의남. "애플리케이션 프로세서 기기를 위한 컨테이너 환경에서 실시간성 지원 방법 및 성능 분석 연구." 한국정보과학회 학술발표논문집 (2018): 1303-1305.
8. Yong, Chanho, Ga-Won Lee, and Eui-Nam Huh. "Proposal of Container-Based HPC Structures and Performance Analysis." Journal of Information Processing Systems 14.6 (2018).
