---
title: Docker 설치 ( CentOS 7 )
category: Docker
order: 1
---
1. Docker 설치
---

```bash
1. yum 패키지 업데이트

	 yum -y update

2. Docker, Docker Registry 설치

	 yum -y install docker docker-registry
```

2. Docker 서비스 실행

---

```bash
1. Docker 서비스 시작
	 systemctl start docker

2. Docker 서비스 중지
	 systemctl stop docker

3. Docker Status 확인
	 systemctl status docker
```