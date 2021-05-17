<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
# Globlin guide 
- Globlin 가이드 문서

---

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
    <a href="#pages">페이지 구조</a>
    </li>
    <li><a href="#login">로그인</a></li>
    <li>
      <a href="#influencer">인플루언서</a>
       <ol>
    <li><a href="#influencer">목록</a></li>
    <li><a href="#influencer">등록</a></li>
    <li><a href="#influencer">후보목록</a></li>
    <li><a href="#influencer">블랙목록</a></li>
    </ol>
    </li>
    <li><a href="#campaign">캠페인</a>
     <ol>
    <li><a href="#campaign">목록</a></li>
    <li><a href="#campaign">등록</a></li>
    </ol>
    </li>
    <li><a href="#report">리포트</a></li>
    <li><a href="#setting">세팅</a>
     <ol>
    <li><a href="#campaign">크롤링</a></li>
    <li><a href="#campaign">필드</a></li>
    </ol>
    </li>
    <li><a href="#scenarios">사용 시나리오</a></li>
    <li><a href="#contact">contact</a></li>
  </ol>
</details>

---

<div id="pages"/>

## 페이지 구조

<div>
<img style="display: block" alt="인플루언서" src="https://user-images.githubusercontent.com/59603575/118248717-9aa2cf80-b4df-11eb-9a18-d15b8ea5a6b4.png">
<img style="display: block" alt="캠페인" src="https://user-images.githubusercontent.com/59603575/118253828-55819c00-b4e5-11eb-86b5-cdde9d0802f5.png">
<img style="display: block" alt="리포트" src="https://user-images.githubusercontent.com/59603575/118253832-56b2c900-b4e5-11eb-8362-ef77e306dabf.png">
<img style="display: block" alt="세팅" src="https://user-images.githubusercontent.com/59603575/118253835-587c8c80-b4e5-11eb-9d1d-462fbc5ed572.png">
</div>

<!--로그인 설명-->

<div id="login"/>

## 로그인

<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="인플루언서" src="https://user-images.githubusercontent.com/59603575/118250320-4dbff880-b4e1-11eb-9c11-9cb74fac03c2.gif">
</details>

<!-- 인플루언서 -->

<div id="influencer"/>

## 인플루언서
### 목록
- 조회
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="인플루언서" src="https://user-images.githubusercontent.com/59603575/118420992-19278900-b6fb-11eb-875f-0b1dd0c4c138.gif">
</details>
- 선택 인플루언서 데이터 다운 (Excel)
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="다운로드" src="https://user-images.githubusercontent.com/59603575/118421149-7b808980-b6fb-11eb-8a4d-d7b8e528a565.gif">
</details>
- 삭제
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="삭제" src="https://user-images.githubusercontent.com/59603575/118422609-825ccb80-b6fe-11eb-9a60-a8136fca513e.gif">
</details>
- 정렬방식 변경 (등록순, 구독자순, 조회수순, ER순)
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="정렬방식" src="https://user-images.githubusercontent.com/59603575/118422623-8983d980-b6fe-11eb-8497-b8d7c43c584a.gif">
</details>
- 세부정보
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="정렬방식 변경" src="https://user-images.githubusercontent.com/59603575/118422628-8d176080-b6fe-11eb-8837-1b4cc914c823.gif">
</details>
- 수정
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="수정" src="https://user-images.githubusercontent.com/59603575/118422635-90125100-b6fe-11eb-878d-ff209f1d7659.gif">
</details>
- 페이징

### 등록
- 개별등록
- 파일등록

### 후보목록
- 조회
- 다운
- 블랙리스트로 이동
- 정렬방식 변경 (최신순, 구독자순)
- 페이징

### 블랙목록
- 조회
- 인플루언서로 복원
- 정렬방식 변경 (최신순, 구독자순)
- 페이징

<!-- 캠페인 -->

<div id="campaign"/>

## 캠페인
### 목록
- 캠페인 수정
- 인플루언서 추가
- 제안 리스트 (기능 없음)
- 리포트로 이동
- 캠페인 추가

### 등록
- 개별등록

<!-- 리포트 -->

<div id="report"/>

## 리포트
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="리포트" src="https://user-images.githubusercontent.com/59603575/118423806-ce107480-b700-11eb-9d87-23e233ab9504.gif">
</details>

- 차트
- RAW DATA 내려받기
- 테이블

<!-- 세팅 -->

<div id="setting"/>

## 세팅
### 크롤링
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="크롤링" src="https://user-images.githubusercontent.com/59603575/118423809-cf41a180-b700-11eb-8750-90f93b6d51a8.gif">
</details>

- 크롤러 등록
- 크롤러 지우기


### 필드
<details open="close">
  <summary>동작</summary>
<img style="display: block" alt="필드" src="https://user-images.githubusercontent.com/59603575/118423810-d10b6500-b700-11eb-9e57-0fcdff2f2278.gif">
</details>

- 필드 등록 
- 필드 삭제


<!-- 시나리오 -->

<div id="scenarios"/>

## 사용 시나리오

<!-- contact -->

<div id="contact"/>

## contact


## Use tech

<span id="use-tech">
  <img src="https://img.shields.io/badge/Javascript-orange?style=flat-square&logo=JavaScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/css-blue?style=flat-square&logo=CSS3&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML-red?style=flat-square&logo=HTML5&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-blue?style=flat-square&logo=React&logoColor=white"/>
    <img src="https://img.shields.io/badge/Redux-blue?style=flat-square&logo=Redux&logoColor=white"/>
    <img src="https://img.shields.io/badge/Redux-saga-blue?style=flat-square&logo=Redux-saga&logoColor=white"/>
</span>