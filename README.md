---
title : 도커 공부하기 from <가장 빨리 만나는 Docker> 
tag : 
- docker
---

# docker-playground
> 

1. Docker
	1. 가상 머신과 Docker
		1. 가상 머신
		2. Docker
		3. 리눅스 컨테이너
	2. Docker 이미지와 컨테이너
2. Docker 설치하기
	1. 리눅스
		1. 자동 설치 스크립트
		2. 우분투
		3. RedHat Enterprise Linux, CentOS
		4. 최신 바이너리 사용하기
	2. Mac OS X
	3. Windows
3. Docker 사용해보기
	1. search 명령으로 이미지 검색하기
	2. pull 명령으로 이미지 받기
	3. images 명령으로 이미지 목록 출력하기
	4. run 명령으로 컨테이너 생성하기
	5. ps 명령으로 컨테이너 목록 확인하기
	6. start 명령으로 컨테이너 시작하기
	7. restart 명령으로 컨테이너 재시작하기
	8. attach 명령으로 컨테이너에 접속하기
	9. exec 명령으로 외부에서 컨테이너 안의 명령 실행하기
	10. stop 명령으로 컨테이너 정지하기
	11. rm 명령으로 컨테이너 삭제하기
	12. rmi 명령으로 이미지 삭제하기
4. Docker 이미지 생성하기
	1. Bash 익히기
	2. Dockerfile 작성하기
	3. build 명령으로 이미지 생성하기
5. Docker 살펴보기
	1. history 명령으로 이미지 히스토리 살펴보기
	2. cp 명령으로 파일 꺼내기
	3. commit 명령으로 컨테이너의 변경사항을 이미지로 생성하기
	4. diff 명령으로 컨테이너에서 변경된 파일 확인하기
	5. inspect 명령으로 세부 정보 확인하기
6. Docker 좀더 활용하기
	1. Docker 개인 저장소 구축하기
		1. 로컬에 이미지 데이터 저장
		2. push 명령으로 이미지 올리기
		3. Amazon S3에 이미지 데이터 저장
		4. 기본 인증 사용하기
	2. Docker 컨테이너 연결하기
	3. 다른 서버의 Docker 컨테이너에 연결하기
	4. Docker 데이터 볼륨 사용하기
	5. Docker 데이터 볼륨 컨테이너 사용하기
	6. Docker 베이스 이미지 생성하기
		1. 우분투 베이스 이미지 생성하기
		2. CentOS 베이스 이미지 생성하기
		3. 빈 베이스 이미지 생성하기
	7. Docker 안에서 Docker 실행하기
7. Dockerfile 자세히 알아보기
	1. .dockerignore
	2. FROM
	3. MAINTAINER
	4. RUN
	5. CMD
	6. ENTRYPOINT
	7. EXPOSE
	8. ENV
	9. ADD
	10. COPY
	11. VOLUME
	12. USER
	13. WORKDIR
	14. ONBUILD
8. Docker로 애플리케이션 배포하기
	1. 서버 한 대에 애플리케이션 배포하기
		1. 개발자 PC에서 Git 설치 및 저장소 생성하기
		2. 개발자 PC에서 Node.js로 웹 서버 작성하기
		3. 개발자 PC에서 Dockerfile 작성하기
		4. 개발자 PC에서 SSH키 생성하기
		5. 서버에 Git 설치 및 저장소 생성하기
		6. 서버에 Docker 설치하기
		7. 서버에 SSH 키 설정하기
		8. 서버에 Git Hook 설정하기
		9. 개발자 PC에서 소스 Push하기
	2. 서버 여러 대에 애플리케이션 배포하기
		1. 개발자 PC에서 Git 설치 및 저장소 생성하기
		2. 개발자 PC에서 Node.js로 웹 서버 작성하기
		3. 개발자 PC에서 Dockerfile 작성하기
		4. 개발자 PC에서 SSH키 생성하기
		5. 배포 서버에 Git 설치 및 저장소 생성하기
		6. 배포 서버에서 SSH 키 생성하기
		7. 배포 서버에 Docker 설치하기
		8. 배포 서버에 Docker 레지스트리 서버 설정하기
		9. 배포 서버에 SSH 키 설정하기
		10. 배포 서버에 Git Hook 설정하기
		11. 애플리케이션 서버에 Docker 설치하기
		12. 애플리케이션 서버에 SSH 키 설정하기
		13. 개발자 PC에서 소스 Push하기
9. Docker 모니터링하기
	1. 모니터링 서버 Dockerfile 작성하기
	2. 애플리케이션 서버 Dockerfile 작성
	3. 웹 브라우저에서 그래프 확인
10. Amazon Web Services에서 Docker 사용하기
	1. Amazon EC2에서 Docker 사용하기
	2. AWS Elastic Beanstalk에서 Docker 사용하기
		1. AWS 콘솔에서 Docker 애플리케이션 배포하기
		2. Docker Hub 공개 저장소 이미지 사용하기
		3. Docker Hub 개인 저장소 이미지 사용하기
		4. Git으로 Elastic Beanstalk Docker 애플리케이션 배포하기
11. Google Cloud Platform에서 Docker 사용하기
	1. Google Cloud SDK 설정하기
	2. Compute Engine에서 Docker 사용하기
	3. Container Engine에서 Docker 사용하기
12. Microsoft Azure에서 Docker 사용하기
13. Docker Hub 사용하기
	1. Docker Hub 가입하기
	2. push 명령으로 이미지 올리기
	3. Docker Hub 개인 저장소 생성하기
	4. Docker Hub Automated Build 활용하기
14. Docker Remote API 사용하기
	1. Docker Remote API Python 라이브러리 사용하기
		1. 컨테이너 생성 및 시작하기
		2. 이미지 생성하기
		3. 컨테이너 목록 출력하기
		4. 이미지 목록 출력하기
		5. 기타 예제 및 함수
	2. Docker Remote API Python 라이브러리로 HTTPS 통신하기
		1. 인증서 생성하기
		2. Python 라이브러리 사용하기
15. CoreOS 사용하기
	1. VirtualBox에 CoreOS 설치하기
		1. systemd로 서비스 실행하기
	2. Vagrant로 CoreOS 설치하기
	3. etcd 사용하기
		1. etcd 키, 디렉터리 생성하기
		2. etcd 키, 디렉터리 목록 출력하기
		3. etcd 키, 디렉터리 자동 삭제 설정하기
		4. etcd 키 감시하기
		5. etcd 기타 명령
	4. fleet 사용하기
		1. fleet 머신 목록 출력하기
		2. fleet으로 유닛 실행하기
		3. fleet 유닛 목록 출력하기
		4. fleet 유닛 상태 확인하기
		5. fleet 자동 복구 확인하기
		6. fleet 전용 옵션 사용하기
		7. fleet 유닛 파일 템플릿 활용하기
		8. fleet 사이드킥 모델 활용하기
		9. fleet 기타 명령
	5. 클라우드 서비스에서 CoreOS 사용하기
		1. Amazon EC2에서 CoreOS 사용하기
		2. Google Compute Engine에서 CoreOS 사용하기
16. Docker로 워드프레스 블로그 구축하기
	1. 워드프레스 Dockerfile 작성하기
	2. MySQL 데이터베이스 Dockerfile 작성하기
	3. 워드프레스와 데이터베이스 컨테이너 생성하기
17. Docker로 Ruby on Rails 애플리케이션 구축하기
	1. Ruby와 Rails 설치하기
	2. Rails Dockerfile 작성하기
	3. PostgreSQL 데이터베이스 Dockerfile 작성하기
	4. Rails와 데이터베이스 컨테이너 생성하기
18. Docker로 Django 애플리케이션 구축하기
	1. Django 설치하기
	2. Django Dockerfile 작성하기
	3. Oracle 데이터베이스 Dockerfile 작성하기
	4. Django와 데이터베이스 컨테이너 생성하기
19. Docker 활용 시나리오
	1. 로드 밸런서와 연계한 확장 전개
	2. 개발, 테스트, 운영을 통합
	3. 손쉬운 서비스 이전
	4. 테스트 용도
20. Docker 명령어 및 옵션 목록
	1. attach
	2. build
	3. commit
	4. cp
	5. create
	6. diff
	7. events
	8. exec
	9. export
	10. history
	11. images
	12. import
	13. info
	14. inspect
	15. kill
	16. load
	17. login
	18. logout
	19. logs
	20. port
	21. pause
	22. ps
	23. pull
	24. push
	25. restart
	26. rm
	27. rmi
	28. run
	29. save
	30. search
	31. start
	32. stop
	33. tag
	34. top
	35. unpause
	36. version
	37. wait
21. 부록
	1. Docker 컴파일하기
	2. 우분투 한국 미러 사용하기
	3. 참고 사이트
- 오탈자


예제 소스
- https://github.com/pyrasis/dockerbook
