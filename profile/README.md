# 프로젝트 소개
<div align=center>

<image width=25%, height=25%, src="https://user-images.githubusercontent.com/103196409/215019817-217224b4-b638-4fbb-98be-57e4988e9523.png">

***ROLL IT!*** 은 친한 친구 또는 친해지고 싶은 사람 등 다양한 사람들에게 익명의 힘을 빌려 메세지를 남길 수  있는 롤링페이퍼 서비스입니다.
</div>

***
## 1. 시스템 아키텍처

<image src="https://user-images.githubusercontent.com/103196409/214876886-5b5bbd0b-0dab-44ea-90a3-b36b70750ab5.png">

***
## 2. 기술 스택

<div align =center>

분야| 사용 기술|
:--------:|:------------------------------:|
**Fronted** | <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/ReactQuery-FF4154?style=for-the-badge&logo=reactquery&logoColor=black"> <img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">
**Backend** | <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=OpenCV&logoColor=white">
**DevOps** | <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black"> <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> 
**Monitoring** |   <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src = "https://img.shields.io/badge/-cadvisor-informational"> <img src ="https://img.shields.io/badge/-node--exporter-brightgreen">
</div>

***
## 3. ERD

<!--<image src="https://user-images.githubusercontent.com/103196409/214505660-fb892945-ffd9-4a9f-8626-0e2f24182674.png">-->
![RollIT-ERD](https://user-images.githubusercontent.com/103196409/215128071-858f1c9f-6df5-4fe0-9d45-d7a1718776ad.png)
- https://www.erdcloud.com/d/SKxFB7zrtQZXfGh6t

***
## 4. API

<details>
<summary>swagger</summary>
<div markdown="1">

![image](https://user-images.githubusercontent.com/103196409/214562842-b2e9870c-7ecc-46b4-90dc-b2ecbf5b3d18.png)
![image](https://user-images.githubusercontent.com/103196409/214562857-220bd0ef-682c-4d77-a9af-55085cdb19d0.png)
![image](https://user-images.githubusercontent.com/103196409/214562870-32b8d2a0-b128-4706-a2a7-aed2d04ca8cf.png)
</div>
</details>

***
## 5. 세부 구성

<div align=center>

**Main** | **Register** | **Login**
:---:|:-------:|:---:|
 image | image <!--img src="https://user-images.githubusercontent.com/103196409/214795136-1b9469a5-b9c9-4d2c-9b26-8552aba0a77c.gif" width="100%"--> | image

**Create RollingPaper** | **Add Memo**|**Add Images** 
:---:|:---:|:---:
image | image | image

**Add Sticker** | **My Page** | **Send Url**
:---:|:---:|:---:
image | image| image
</div>




***
## 6. DEMO

***
## 7. 사용 방법

>### Clone Repository
```
git clone https://github.com/2022-Winter-Bootcamp-Team-K/docker.git
```
>### Set environment file
Path : docker/frontend/.env<br>
프로젝트 연결을 위한 URL 환경변수
```
REACT_APP_BACKEND_URL=
```

Path : docker/backend/backend/.env<br>
Django secret key, S3 bucket, Email 공유 환경변수
```
SECRET_KEY=''
DEBUG=True
DATABASE_URL=mysql://root:root@mysqldb:3306/test

AWS_ACCESS_KEY_ID=''
AWS_SECRET_ACCESS_KEY=''
AWS_REGION=''
BUCKET_NAME=''
EMAIL_ADDR=''
EMAIL_PASSWORD=''
```
>### Run
```
docker compose -f docker-compose.prod.yaml up —build
```

***
   
## 8. 개발자

**이름** | 정윤호 | 김민석 | 김상원 | 라예진 | 이준희
:---:|:---:|:---:|:---:|:---:|:---:
역할 | Team Leader, FrontEnd, DevOps | FrontEnd | BackEnd | Backend | FrontEnd
GitHub | [@yunhobb](https://github.com/yunhobb) | [@minseok1015](https://github.com/minseok1015) | [@Doncham](https://github.com/Doncham) | [@Haaein](https://github.com/Haaein) | [@junvhui](https://github.com/junvhui)

