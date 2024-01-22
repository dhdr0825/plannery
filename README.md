# 나만의 플래너 자동생성 서비스
자동 생성 기능(탬플릿 생성, 일자 생성, 하이퍼링크 생성)을 통해 디지털 플래너를 쉽게 만드는 웹 플랫폼
<br/> 
<br/> 

## 연구/개발 목적
* 디지털 플래너 제작 시간을 줄여 초보자도 쉽고 간단하게 만들 수 있음
* 프로그램 설치 없이 웹 브라우저에서 간편하게 디자인할 수 있음
<br/> 

## 연구/개발 필요성
* 태블릿 PC의 가구 점유율 36%, 전년(2022년)대비 6.9% 성장
* 디지털 문구 시장의 성장
* 기존 디자인 소프트웨어의 한계 : 별도의 학습이 필요, 비싼 가격과 구독 모델
<br/>

## 추진전략 및 방법
### 목표
* 디지털 플래너를 쉽게 만드는 웹 플랫폼 개발
### 문제점
* 디지털 플래너 제작 시간이 오래 걸림
  * 날짜/공휴일 등 입력할 요소가 많음
  * 방대한 디지털 플래너 페이지 관리를 위해 하이퍼링크를 일일이 만들어야 함
### 해결방법
* 플래너 자동 생성 / 수정 기능 제공
* 하이퍼링크 자동 생성 기능 제공
<br/>

## 개발환경
### 개발도구
* Visual Studio Code

### 개발언어
* 프론트엔드 : HTML, CSS
* 백엔드 : JavaScript, Python

### API
* Google Cloud Vision API – OCR
<br/>

## 수행결과
### 1) 플래너 자동 생성
* 사용자가 선택한 서식에 따라 플래너 페이지 생성
* 날짜/공휴일 자동 입력
<br/>

![image](https://github.com/dhdr0825/plannery/assets/65939582/06d2e81b-e54f-468c-9353-a93976fbbac3)
![image](https://github.com/dhdr0825/plannery/assets/65939582/53d285ec-812b-45c6-9f24-93c3c24104e7)


### 2) 플래너 서식 수정

* 캔버스의 여백, 선색, 채우기 색, 텍스트 색, 폰트 등을 수정 가능
<br/>

![image](https://github.com/dhdr0825/plannery/assets/65939582/3a3d8325-b0b2-4109-b341-c33e9428103e)

### 3) 하이퍼링크 자동 생성
* 플래너 이미지에서 OCR로 텍스트 좌표 추출
* 텍스트 좌표의 결측치 자동 처리 : 사용자가 월/일 영역 지정 → 해당 영역의 좌표값 추출 → 결측치 자동 처리
<br/>

![image](https://github.com/dhdr0825/plannery/assets/65939582/fcd95384-066b-432a-809e-9b22ea7cfa46)
![제목을-입력해주세요_-001 (4)](https://github.com/dhdr0825/plannery/assets/65939582/613e5938-4c1f-492e-b9bf-7ab20dc6aec7)

















