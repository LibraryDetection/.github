# 경희대학교 공과대학 열람실 예약시스템 개선

빈번히 일어나는 열람실 사석화와 미반납 문제를 해결하고자 시작하게 된 연구입니다.

YOLOv5 모델을 이용해 짐과 사람, 의자를 감지하고, django와 react를 기반으로 구현한 예약시스템에서 사석화와 미반납 행위가 실시간 카메라로 감지될 시 자동으로 퇴실처리되는 시스템입니다.

### 📚 STACKS

![node-16.14.2](https://img.shields.io/badge/Node-16.14.2-green)
![express-4.18.1](https://img.shields.io/badge/Express-4.18.1-green)
![html-latest](https://img.shields.io/badge/html-5.2-green)
![css-latest](https://img.shields.io/badge/css-3-green)

![nginx-1.14.0](https://img.shields.io/badge/nginx-1.14.0-blue)
![socket.io-6.14.13](https://img.shields.io/badge/socket.io-6.14.13-blue)
![AWS_EC2](https://img.shields.io/badge/AWS_EC2-blue)

![mysql-2.18.1](https://img.shields.io/badge/Mysql-2.18.1-yellowgreen)
![AWS_RDS](https://img.shields.io/badge/AWS_RDS-yellowgreen)

## About the Project

- 회원가입 및 로그인을 통해 사이트에 들어갈 수 있습니다.
- 메인 화면에서는 지역별 맛집정보를 파악할 수 있습니다.
- 실시간 채팅을 통해 타 유저들과 해당 음식점의 실시간 정보를 빠르게 공유할 수 있습니다.
- 다음의 주소를 통해 플랫폼 이용이 가능합니다.
- http://52.54.201.217:3000/login

### Overview

<div align="center">
    <img src="https://github.com/jeongmin1217/favorite_restaurant/blob/main/overview.png">
</div>

### Project Architecture

![architecture](https://github.com/LibraryDetection/.github/assets/79658037/e751cdd9-2e55-4651-8c4d-d7c2277488e1)

### Built With

- [node.js](https://nodejs.org/ko/)
- [express](https://expressjs.com/ko/)
- [AWS_EC2](https://aws.amazon.com/ko/)
- [AWS_RDS](https://aws.amazon.com/ko/)
- [socket.io](https://socket.io/)
- [nginx](https://www.nginx.com/)
- [mysql](https://www.mysql.com/)
