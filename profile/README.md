## 💡 Introducetion
예약 구매 사이트

## 📌요구사항
* Jwt와 Security를 이용한 유저관리
* Docker를 기반으로 MSA 구축
* 예약 구매를 위한 API 생성
  * 상품 목록 API
  * 상품 상세 API
  * 주문 현황 API
  * 재고 관리 API
  * 결제 API

## ⚒ Develop Select Stack
* Spring boot version 3.2.2
* Gradle
* Spring boot Security jwt
* Spring boot JPA
* Spring Cloud Gateway
* Spring Cloud Eureka
* Spring Cloud OpenFeign
* Docker
* Redis
* Postgresql

## IDE
* IntelliJ
* Docker desktop

## ERD 설계

<img src="https://github.com/PreorderSystemPersonal/.github/assets/39753337/b794b335-e4fc-471c-9fa1-8a1c1bf21efd" width="800" height="400">


## API 명세서
👉[API 명세서](https://foamy-principle-0ef.notion.site/API-fc7e48d269cc4d01a9f39d1eb255a39b?pvs=4)


## 고민했던 부분
* 결제율 실패 경우의 수 고려
* 토큰 발급시 payload 구성 고려
