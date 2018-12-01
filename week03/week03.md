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

#### 4. NodeJS Process Manager 구축

> npm install -g pm2
> : NPM을 통해 pm2(nodejs process manager)를 -g 옵션으로 글로벌 모드(전체 적용)로 설치합니다.
> 
> npm install
> : npm install 명령어를 입력했을 때 뒤에 패키지명이 없다면 프로젝트 내에 package.json 파일 안의 내용을
>   확인하여 관련 모듈들을 해당 프로젝트 내에 설치합니다(-g 옵션과의 차이).
> 
> pm2 start bin/www --name WAS
>  : pm2를 통해 node.js로 작성된 API 프로젝트를 실행합니다.
> 
> pm2 list
> : pm2로 관리되는 프로세스들을 확인합니다.
> 
> pm2 show WAS
> : 방금 pm2로 실행한 WAS로 명시한 프로세스의 상세 정보를 확인합니다.
> 


