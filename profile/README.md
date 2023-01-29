# Introduction
<div align=center>

<image width=25%, height=25%, src="https://user-images.githubusercontent.com/87285536/215344050-6453724d-777d-47b9-bae2-e7a312d341a7.png">

***ROLL IT!***
<br>큰 종이의 한편에 당신의 마음을 전달해보세요
</div>



***
## Demo
###  URL: [www.rollit5.link](www.rollit5.link)
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
여기서 일반 사용자 입장이랑 어드민 그리고 처음부터 과정을 다 넣어주면 좋을듯 

***
## System Arcitechture

<image src="https://user-images.githubusercontent.com/87285536/215322656-8b618261-7ea5-4d50-a9c6-b40eb503ebc6.png">

***
## Tech stack

<div align =center>

분야| 사용 기술|
:--------:|:------------------------------:|
**Fronted** | <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> ![styled-components](https://img.shields.io/static/v1?style=for-the-badge&message=styled-components&color=DB7093&logo=styled-components&logoColor=FFFFFF&label=) 
**Backend** | <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=OpenCV&logoColor=white">
**DevOps** | <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black"> <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> 
**Monitoring** |   <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src = "https://img.shields.io/badge/-cadvisor-informational"> <img src ="https://img.shields.io/badge/-node--exporter-brightgreen"> ![Elastic Stack](https://img.shields.io/static/v1?style=for-the-badge&message=Elastic+Stack&color=005571&logo=Elastic+Stack&logoColor=FFFFFF&label=)
**etc** | ![Slack](https://img.shields.io/static/v1?style=for-the-badge&message=Slack&color=4A154B&logo=Slack&logoColor=FFFFFF&label=) ![Notion](https://img.shields.io/static/v1?style=for-the-badge&message=Notion&color=000000&logo=Notion&logoColor=FFFFFF&label=) ![Figma](https://img.shields.io/static/v1?style=for-the-badge&message=Figma&color=F24E1E&logo=Figma&logoColor=FFFFFF&label=) ![Postman](https://img.shields.io/static/v1?style=for-the-badge&message=Postman&color=FF6C37&logo=Postman&logoColor=FFFFFF&label=) <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"> ![GitKraken](https://img.shields.io/static/v1?style=for-the-badge&message=GitKraken&color=179287&logo=GitKraken&logoColor=FFFFFF&label=) ![Visual Studio Code](https://img.shields.io/static/v1?style=for-the-badge&message=Visual+Studio+Code&color=007ACC&logo=Visual+Studio+Code&logoColor=FFFFFF&label=)
</div>

***
## ERD

<!--<image src="https://user-images.githubusercontent.com/103196409/214505660-fb892945-ffd9-4a9f-8626-0e2f24182674.png">-->
![RollIT-ERD](https://user-images.githubusercontent.com/87285536/215340380-42a76006-03a1-44bb-949a-c6debd94da13.png)
- https://www.erdcloud.com/d/ZQmQaTRBR39Hu2MJu

***
## API

<details>
<summary>swagger</summary>
<div markdown="1">

![image](https://user-images.githubusercontent.com/103196409/215338660-c5286994-a22f-4d84-9d6c-30cab659effe.png)
![image](https://user-images.githubusercontent.com/103196409/214562857-220bd0ef-682c-4d77-a9af-55085cdb19d0.png)
![image](https://user-images.githubusercontent.com/103196409/215338656-e777d43c-edfe-4cfd-9c63-9dea218b3736.png)
</div>
</details>

***
## Detailed Info
**NAME** | **Port** | **Description**
:---:|:---:|:---:
Nginx | 80 | 가벼움과 높은 성능을 목표로 하는 웹서버로 서버로서의 역활과 프록시로서의 역할을 수행합니다
React(on Nginx)| 80 | 사용자들이 메모, 사진, 스티커를 저장하고서버로부터 사용자들이 저장한 메모, 사진, 스티커를 가져와 보여주는 역할을 합니다
Django + Gunicorn | 8080 | Rollit의 서버, 모든 내용의 중심에 위치하며, Database와의 소통을 담당합니다.
Mysql | 3307 | Database
RabbitMQ | 5672 | 요청에 대한 많은 사용자에게 전달하거나, 요청에 대한 처리 시간이 길 때 사용합니다.
Celery | - | 비동기 작업을 위해 사용합니다. 분산 메시지 전달을 기반으로 동작하는 비동기 작업 큐 입니다.
Grafana | 3001 | Django, cAdvisor, Prometheus, NodeExporter를 통해 전달받은 시간별 메트릭 데이터를 시각화 하여 대시보드로 제공해 줍니다
cAdvisor | 8081 | 사용중인 도커 컨테이너의 리소스 사용량을 측정하여 시계열 메트릭을 데이터화합니다.
Prometheus | 9090 | Django의 메트릭 데이터와 cAdvisor, NodeExporter의 시계열 메트릭 데이터를 수집하여 시스템 모니터링을 합니다
Node Exporter | 9100 | 서버의 cpu, 메모리, 디스크, 네트워크 사용량등 호스트 과련 메트릭 데이터를 수집하여 api로 노출시킵니다.
Filebeat | - | Nginx의 로그파일을 Filebeat로 수집합니다.
Logstash | 5044, 9600, 50000|  Filebeat가 수집한 로그를 Logstash에 전달합니다.
Elasticsearch | 9200, 9300 | Logstash로부터 전달 받은 로그를 Elasticsearch에 저장합니다.
Kibana | 5061 | Elasticsearch에 저장된 로그를 Kibana를 통해 분석합니다.
***

   
## Team:  `It's 5K`
| Name    | <center>정윤호</center>|<center>김민석</center> |<center>김상원</center> | <center>라예진</center> | <center>이준희</center>
| ------- | --------------------------------------------- | ------------------------------------ | --------------------------------------------- | --------------------------------------- | --------------------------------------- |
| Profile | <img width="150px" src="https://avatars.githubusercontent.com/u/87285536?v=4" />|<img width="150px" src="https://avatars.githubusercontent.com/u/107205708?v=4" />| <img width="150px" src="https://avatars.githubusercontent.com/u/109122419?v=4" />| <img width="150px" src="https://avatars.githubusercontent.com/u/103196409?v=4" />| <img width="150px" src="https://avatars.githubusercontent.com/u/121507763?v=4" />|
| role    | <center>Team Leader, <br>Frontend & DevOps</center>   | <center>Frontend</center>    | <center>Backend</center>  | <center>Bakcend</center> | <center>Frontend</center> |
GitHub | <center>[@yunhobb](https://github.com/yunhobb)</center> | <center>[@minseok1015](https://github.com/minseok1015) </center>| <center>[@Doncham](https://github.com/Doncham) </center>| <center>[@Haaein](https://github.com/Haaein)</center> | <center>[@junvhui](https://github.com/junvhui)</center>

***

