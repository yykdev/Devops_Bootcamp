# [[ 패스트캠퍼스 ] DEVOPS 구축 BOOTCAMP 3기](https://www.fastcampus.co.kr/dev_camp_devb/?gclid=Cj0KCQjw08XeBRC0ARIsAP_gaQA-oDn79_vTccFxR0gg3zyCTHwH4NdjtKytrcQT9vKhDtyoZBJx-cMaAgH6EALw_wcB)

> 최제필 강사님 / 진재규 강사님  
> Facebook : [https://www.facebook.com/groups/fc.devb3th/](https://www.facebook.com/groups/fc.devb3th/)  

----

## # 1 주차

> 1) 웹 서버 구성

```
서비스 운영에 기본이 되는 웹 서버를 로컬 환경, 클라우드 환경, 컨테이너 환경에 각각 구축하며  
각 환경의 장, 단점과 전체적인 서버 아키텍처에 대한 기본 지식을 습득합니다.

- 리눅스 기본 명령어 및 사용 방법
- 운영 모니터링 시 지표 확인에 도움될 정보
- VIM 사용 방법 : vim 기본 설명(검색/치환/구간 복사,잘라내기 등의 편집 기능)
- Virtual Box, Vagrant를 활용하여 VM 운영하기
- 로컬 환경에서 Nginx 설치
- Docker 설치, Docker hub를 통해 컨테이너 기반의 Nginx 설치
- AWS EC2 인스턴스 생성 후 해당 환경에서 Nginx 설치하여 외부에서 접속
```

> 2) 서버 아키텍처와 컨테이너 환경

```
모든 상황을 해결하는 하나의 서버 아키텍처는 없습니다. 따라서, 각 상황에 맞는 서버 아키텍처를 알아보며,  
현업에서는 어떤 방식으로 서버를 운영하는지 다양한 사례들을 살펴봅니다.

- 서버 아키텍처 비교
- 모노리틱 아키텍처
- 서버리스 아키텍처
- 마이크로 서비스 아키텍처
- Docker 이해
- Docker 개념 및 역사
- Linux 컨테이너 기술에 대한 개념
```

----

## # 2 주차

> 1)다중 서버 환경 구성

```
실제 운영 환경에는 하나의 서버로 운영할 수 없습니다. 왜냐하면, 하나의 서버에 장애가 생길수도 있고, 트래픽이 너무 많아질 수도 있기 때문입니다. 따라서, 서버에 문제가 생기거나 트래픽이 몰려도 장애없는 서버를 구성하는 방법을 배웁니다.

- git 구성요소 및 기능 설명
- AWS ELB을 활용하여 로드밸런싱 환경 구축
- AWS Auto Scaling Group을 이용한 다중 서버 구성
- Failover 아키텍처 구성
```

> 2) 네트워크 기본

```
서버를 운영하며 알아야 할 기초적인 네트워크 지식을 짚고 갑니다.

- 포트포워딩
- 네트워크 기본
- 가용성
```

----

## # 3 주차

> 1) 웹 서버 + WAS + DB서버 - 간이 운영 환경 구축

```
전체적인 서버 아키텍처 부터 서버 내부, 외부 등 운영 서버에 필요한 요소들을 배우고 구성하게 됩니다. 이 수업이 끝나면 내가 작성한 코드를 운영 환경에서 서비스 할 수 있게 됩니다.

- Nginx
- ssl 설정 및 Multi site
- WAS 프로젝트 간단 소개(Node.js) 및 EC2에서 환경 구축
- AWS RDS를 통한 DB 서버 구축(MySQL)
- 간이 인프라(웹 서버 + WAS + DB서버)를 구축해보고 통합 테스트
```

> 2) DevOps로 넘어가기

```
함께 운영 환경을 구축해보며 어떠한 요소가 더 필요한 지 고민하고 해당 운영 스택을 기반으로 
DevOps로 확장할 준비를 합니다.

- 해당 인프라 구축 경험을 다함께 공유하여 앞으로 어떤 기능이 있으면 좋을 지에 대한 토론하고 AWS 제품,  
  오픈소스 툴 등을 리서치해보기
- 모니터링(퍼포먼스, 로그, 메트릭 등
- CI/CD
- VM 환경에서의 한계와 컨테이너 환경
```

----

## # 4 주차

> 1) CI/CD, 모니터링 환경 구성

```
사람은 무조건 실수를 하기 때문에 단순 반복적인 업무는 최대한 기계에게 맡겨야 합니다.
코딩 이후 배포까지 필요한 수많은 작업들을 어떻게 자동화하는지 배웁니다.

- AWS 내 사용 빈도가 높을 서비스군들 소개
- AWS Beanstalk을 이용한 배포 및 서비스 관리
- AWS Cloudwatch를 구성하여 모니터링
- Jenkins를 활용한 CI/CD 파이프라인 구축
- ELK 스택을 구성하여 로그 모니터링
```

> 2) CI/CD, 모니터링 환경 구성

```
대량의 로그를 관리하는 방법과 로그에서 장애의 단서를 재빠르게 찾기 위해 사용되는
시스템들의 활용 방법을 배웁니다. 또한 자동화 된 서버 관리에 필요한 요소를 공유합니다.

- 모니터링의 이해와 여러 운영 데이터를 보며 가용성, 병목화 등 운영 경험 공유
- CI/CD의 이해와 배포 전략 및 정책에 대한 경험 공유
```

----

## # 5 - 6 주차

> 컨테이너 환경으로의 이전

```
1~4주차에 구축한 인프라 환경을 컨테이너 환경으로 이전, 구축하기

- Docker file 작성 / 빌드, 컨테이너 운영하기
   - Docker 명령어
   - Dockerfile 작성

- AWS ECS를 활용한 Container orchestration
   - AWS ECR에 n개의 Docker file push
   - EC2 n대를 구성한 후 ECR(docker file)을 기반으로 하여 ECS로 클러스터링
        - 작업 정의 구성
        - 컨테이너 별 포트 매핑
        - 컨테이너 Metric(시스템 자원) 배치

- AWS ALB(Aplication load balancer)를 활용한 컨테이너 로드밸런싱

- AWS Codepipeline을 활용한 CI/CD
   - Github webhook 설정
   - 컨테이너 별 자동 배치를 위한 Dockerfile 재작성
   - AWS Codebuild를 통한 자동 빌드(Docker) 설정
   - Codepipeline + Codebuild + ECS를 활용한 무중단(블루-그린) 배포
```

----

## # 7 주차

> 서버리스 아키텍처 구축

```
AWS에서 제공하는 다양한 컴퓨팅 리소스를 활용하여 서버리스 아키텍처를 구축해보면서
기존 아키텍처와의 장단점을 비교하여 효율적으로 활용할 수 있는 방안에 대해 고민합니다.

- AWS S3 + AWS CloudFront CDN 정적 파일 전송 아키텍처 구축
- AWS API Gateway + AWS Lambda + AWS Dynamo DB 웹 서비스 구동을 위한 서버리스 아키텍처 구축
- 다양한 AWS Computing service 알아보기
```

----

## # 8 주차

> 실제 업무 환경 도입

```
1~7주차까지 다양한 아키텍처를 구축, 운영 실습을 진행하였습니다.
이를 기반으로 실제 업무 환경에 진입하였다고 가정하고 설계부터 운영까지 한 사이클을 경험하고 회고합니다.

- 본인 코드 / 과제 코드를 기반으로 서버 아키텍처 설계 및 도안 작성
   - Draw.io
   - Cloudcraft

- Cloud / Bare metal(물리 서버) 환경에서 구축 진행
   - 강사 / 보조 강사와 실습생이 한 팀을 이뤄 맨투맨으로 진행
   - CI/CD Pipeline, Monitoring
   - 필요한 Open source tool 리서치 및 구축

- 구축한 서버를 대상으로 부하 테스트(Stress test) 진행 및 병목 찾기
   - Apache jMeter
   - NGrinder
```
