# DevOps 구축 BOOTCAMP 3기
## 3주차

### Node.js 환경 구축

#### 1. EC2 생성

#### 2. EC2 접속 및 Node.js 환경 셋팅

> sudo ssh -i ~/Desktop/ec2_test.pem ec2-user@{접속할 WAS 인스턴스 DNS 주소} ↵ sudo su ↵  
> : curl 클라이언트를 통해 nodejs(v8.x LTS), NPM 설치 코드 받아오기
> 
> curl --silent --location https://rpm.nodesource.com/setup_8.x | sudo bash -  
> : yum 클라이언트로 nodejs 설치(npm도 같이 설치됨)
>
> yum install -y nodejs  
> : 설치된 nodejs 버전 확인
>
> node -v npm -v  
> : 설치된 NPM 버전 확인 

#### 3. Node 환경 api 소스 코드 셋팅

> ymu install -y git
> : git 클라이언트 설치
> 
> git clone -b v1 https://github.com/owen1025/Fastcampus-api-deploy.git
> : git을 통해 Fastcampus-api-deploy 프로젝트 코드를 받아옵니다. 현 프로젝트는 브랜치 별로 코드 버전이
>   관리되어 지금은 v1 브랜치의 코드를 받아오기 위해 -b 옵션을 사용합니다.
> ls -al
> : API 프로젝트 코드 다운로드가 잘 되었는 지 디렉토리 확인을 합니다.
> 
> cd Fastcampus-api-deploy/
> : Fastcampus-api-deploy 디렉토리로 이동합니다.
