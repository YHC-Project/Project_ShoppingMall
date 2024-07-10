<h1  align='center'>👕라이브 커머스 프로젝트</h1>

## 목차
- [개요]
- [기술 스택]
- [프로젝트 설계]
- [핵심 기능]
- [주요기능 실행화면]
- [개선사항]
  


## 🚩 개요
- 프로젝트 목표 : 다양한 `API`를 활용한 `스프링` , `마이바티스` 라이브 커머스 프로젝트
- 개발기간 : 24/05/02 ~ 24/05/24



## 🔧 기술 스택
- API : `카카오페이 API`
- Language : `Java(11)` `JavaScript(3.22)`
- Library & Framework : `Spring(5.3.23)` `Junit(4.12)` `Servlet(4.0.1)` `Spring Security` `websocket(5.2.7)` `JSP(2.5)`
- Database : `MySQL(8.0.35)`
- Target : `Web Browser`
- Tool : `SpringSource Tool Suite (STS) 3.9.18.RELEASE`
- Infra : `Linux(Ubuntu)` `EC2`
- Etc : `Git`

## 👾 프로젝트 설계, 구현 📂 PPT 📂 (ERD, USECASE)

<details><summary>프로젝트 설계, 구현, PPT 눌러서 확인</summary>   
<div align="center">   

| **![1](./image/image.png)|** | **![2](./image/image-1.png)** |
| :------: |  :------: |
|![3](./image/image-2.png)| |![4](./image/image-3.png)| |![5](./image/image-4.png)| |![6](./image/image-5.png)| |![7](./image/image-6.png)| |![8](./image/image-7.png)| |![9](./image/image-8.png)| |![10](./image/image-9.png)| |![11](./image/image-10.png)| |![12](./image/image-11.png)| |![13](./image/image-12.png)| |![14](./image/image-13.png)| |![15](./image/image-14.png)| |![16](./image/image-15.png)| |![17](./image/imvage-16.png)| |![18](./image/image-17.png)||![19](./image/image-18.png)| |![20](./image/image-19.png)| |![21](./image/image-20.png)| |![22](./image/image-21.png)|

</div>            
</details>

## 💻 핵심 기능



#### 상품
- 의류 쇼핑몰 사이트를 이용해 상품정보 DB 저장
- 상품 정렬(낮은 가격, 높은 가격, 등록순)
- 상품 검색(상품이름, 카테고리, 색상, 색상+상품이름)
- 관심상품
- 상품 정보 제공

#### 유저
- 소셜 로그인 및 간편 회원가입
- 이메일 중복 처리
- 비밀번호 암호화 처리
- 다음 우편주소 API
- 마이페이지(장바구니, 관심상품, 사용 가능한 쿠폰, 주문내역, 배송지 관리, 내 게시글) 
- 유저 정보 수정
- 비밀번호 찾기

#### 장바구니
- 상품 장바구니에 담기 및 제거
- 실시간 수량 수정후 결제
- 같은 상품, 같은 사이즈 장바구니 담을 시 수량 증가 

#### 주문
- 장바구니 상품 주문
- 주문 정보 확인
- IamportAPI 이용한 결제

## 🎇 주요기능 실행화면

<details>
<summary>주요기능 실행화면 눌러서 확인</summary>



</details>

## 🚩 문제점
- 테스트때 NULL값이 넘어가서 오류가 뜰때
- 생각지도 못한 DB join으로 다시 설정해야될때
- 시큐리티 토큰


## 🌄 개선사항
- 관리자 CRUD 추가
- 장바구니 구매 후 삭제
 
