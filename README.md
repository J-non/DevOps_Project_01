# 1차 프로젝트

## 목차
- [개요](#개요)  
- [주요기능](#주요기능)   
    - [MainPage](#mainpage)   
    - [로그인 및 회원가입](#로그인-및-회원가입)
    - [마이페이지 및 관리자 페이지](#마이페이지-및-관리자-페이지)
    - [게시판](#게시판)
- [이슈사항](#이슈사항)   
---
## 개요

### 기간 : 2024.05.14 ~ 2024.05.28

### 개발자 : J-non(이종석) 본인 외 1명

### 기술스택
<img src='https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white'> <img src='https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white'> <img src='https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white'> <img src='https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white'>   

### 목표
> 프론트 영역에서 모던한 느낌의 화면 구성 및 로컬스토리지를 사용한 게시판, 로그인 기능 구현


---

## 주요기능

### MainPage
![1차 메인](https://github.com/user-attachments/assets/a0c9e987-b8c4-40fc-9e8d-e4db6a478711)
   - 게시판 및 로그인 페이지 이동
   - 모달을 사용한 호텔 찾기 및 예약 화면
   - 이미지 슬라이드 및 스와이프 기능
   <br>
   
### 로그인 및 회원가입
![1차 로그인](https://github.com/user-attachments/assets/0847edfe-da9c-46dd-b123-d93d26261658)
   - 사용자 정보로 가입 및 로그인
   - 가입한 사용자 중복 확인
   - CSS를 사용한 회원가입, 로그인창 animation 구현
   <br>
   
### 마이페이지 및 관리자 페이지
![1차 마이페이지](https://github.com/user-attachments/assets/e24d2ec3-8950-4793-bb32-23edb4084572)
   - 현재 인증한 사용자의 정보 확인 및 수정
   - 관리자 인증시 사용자 가입허가 
   <br>
   
### 게시판
  ![페이지네이션 게시판](https://github.com/user-attachments/assets/7ea8df03-2c7e-41f8-aed8-a84684472891)
   - 작성된 게시글 조회
   - 게시글 작성, 수정, 삭제
   - 페이지네이션 기능

---
## 본인 역할
- Main페이지
    - Main페이지 화면 구성
    - 이미지 슬라이드 및 스와이프 기능 구현
    - 헤더영역 호텔찾기, 예약탭 모달창 구현
- 로그인 및 회원가입 페이지
    - 로컬스토리지를 사용한 회원가입 및 로그인 기능 구현
    - 게시판 목록 페이지네이션 및 검색기능 구현
    - CSS를 사용한 회원가입, 로그인창 animation 구현
- 게시판 목록 페이지
    - 게시판 목록 화면 
    - 작성된 게시글 조회 기능 구현

---

## 이슈사항

1. 게시글 및 대댓글 삭제시 이전 글의 댓글, 대댓글로 이동    
  => 삭제시 각 게시글, 댓글, 대댓글의 index 수정   
2. 닉네임 변경시 게시글 수정, 삭제 권한 없음   
  => 삭제시 각 게시글, 댓글, 대댓글의 index 수정
