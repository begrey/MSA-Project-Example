# MSA-Project-Example [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/begrey)  
  
> MSA 구조 기반 Cloud Native Application 토이프로젝트 입니다.   
    

## 프로젝트 구성

### apigateway-service
    [Spring Cloud Gateway]
    Spring Security Filter 처리
    마이크로서비스 부하 분산 및 서비스 라우팅

### config-service
    [Spring Cloud Config]
    마이크로서비스 소스 관리 및 프로파일 관리

### discovery-service
    [Eureka]
    마이크로서비스 등록 및 검색

### order-service
    [MicroService]
    주문에 대한 서비스

### user-service
    [MicroService]
    유저에 대한 서비스

### catalog-service
    [MicroService]
    상품(카테고리)에 대한 서비스


## 구성도


![ex_screenshot](./구성도.PNG)


## 목표 설계


![ex_screenshot](./목표.PNG)

## WBS

![ex_screenshot](./wbs.PNG)

