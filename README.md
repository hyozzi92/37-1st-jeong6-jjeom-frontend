![logo_w-1](https://user-images.githubusercontent.com/67556491/193203493-632c4b7a-b06b-4e8f-b306-dec380bb4b5b.png)


## 정육쩜 **프로젝트 Front-end/Back-end 소개**

- 초신선 육류를 주력으로 판매하는 쇼핑몰
- 프로젝트 기간동안 메인, 회원가입, 로그인, 리스트, 상세, 장바구니 결제 페이지를 구현했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### **개발 인원 및 기간**

- 개발기간 : 2022/9/19 ~ 2022/9/30
- 개발 인원 : 프론트엔드 3명, 백엔드 2명
- [백엔드 github 링크](https://github.com/wecode-bootcamp-korea/37-1st-jeong6-jjeom-backend)

### **프로젝트 선정이유**

- 이 사이트는, 깔끔한 UI로 구성되어있으며 기본 기능 구현에 충실한 사이트이기 때문이다.

### **데모 영상(이미지 클릭)**

[정육쩜 시연영상](https://youtu.be/NzY8gplL_xM) 

## **적용 기술 및 구현 기능**

### **적용 기술**

> Front-End : React.js, sass
> 

> Back-End : My SQL, Bcrypt, Node.js
> 

> Common :  RESTful API
> 

### **내가 구현한 기능**

### 회원가입/로그인
1. 로그인
  - 기본디자인에서 효과를 넣어봤다
  - 클라이언트 단에서 Validation을 1차적으로 넣었다.
  
  ![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/106464348/203305422-20a06fa1-17c4-42b8-b003-8a07bcfbb404.gif)
  
2. 회원가입
 - 여기도 마찬가지로 1차 Validation으로 서버와의 통신을 줄였다.
 
  
![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/106464348/203305854-7685b23e-6d82-4bdb-a236-6d8f952e9c1d.gif)

### 메인페이지
1. 캐러셀
  - 배너이미지를 500px로 늘어뜨려서 클릭 시 100px만큼 이동하는 형식으로 구현(setTime 함수도 사용했지만 지저분한 느낌이 들어서 제거)


<br>

![캐러셀](https://user-images.githubusercontent.com/106464348/203301108-8933b363-8edf-4ae6-ad8a-7e7c38c4e5c8.gif)


2. 추천상품리스트
   - 원하는 카테고리 선택시 관련 상품들이 보여지게 구현
   - 추천상품은 Math.random 함수를 사용해서 무작위로 표현
   
   <br>
![추천상품리스트](https://user-images.githubusercontent.com/106464348/203301831-174d7765-ef73-47a3-8ba8-cd603a2a092c.gif)
### 리스트

### 상세

### 장바구니

### 주문/결제

## **Reference**

- 이 프로젝트는 [정육각](https://www.jeongyookgak.com/index) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
