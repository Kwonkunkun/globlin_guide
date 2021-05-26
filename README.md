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
<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=Globlin Simple guide&fontSize=60&animation=fadeIn" />

- Globlin 간단 소개 문서
- 더 자세한 내용 설명을 원하신다면 [globlin notion document](https://www.notion.so/57a60ad434754963b956fb54c5c29db2)를 참조해주세요!

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
    <li><a href="#influencer-list">목록</a></li>
    <li><a href="#influencer-regist">등록</a></li>
    <li><a href="#influencer-candidate">후보목록</a></li>
    <li><a href="#influencer-black">블랙목록</a></li>
    </ol>
    </li>
    <li><a href="#campaign">캠페인</a>
     <ol>
    <li><a href="#campaign-list">목록</a></li>
    <li><a href="#campaign-regist">등록</a></li>
    </ol>
    </li>
    <li><a href="#report">리포트</a></li>
    <li><a href="#setting">세팅</a>
     <ol>
    <li><a href="#setting-crawling">크롤링</a></li>
    <li><a href="#setting-field">필드</a></li>
    </ol>
    </li>
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

<details>
  <summary>동작</summary>
<img style="display: block" alt="인플루언서" src="https://user-images.githubusercontent.com/59603575/118250320-4dbff880-b4e1-11eb-9c11-9cb74fac03c2.gif">
</details>

-광고주나 내부에서 아이디 발급 필요 시 개발팀에 문의 

<!-- 인플루언서 -->

<div id="influencer"/>

## 인플루언서
- 캠페인에 등록할 인플루언서 목록을 관리합니다. 
- 크롤링된 인플루언서 목록을 관리합니다. 

<div id="influencer-list"/>

### 목록

<details>
  <summary>동작</summary>
<img style="display: block" alt="인플루언서" src="https://user-images.githubusercontent.com/59603575/118426086-817b6800-b705-11eb-9b4f-8f8b5f7f8335.gif">
</details>

- 조회
- 선택 인플루언서 다운 (Excel)
- 선택 인플루언서 삭제
- 정렬순서 변경 (등록순, 구독자순, 조회자순, er순)
- 인플루언서 세부정보 
- 인플루언서 수정
- 페이징 


<div id="influencer-regist"/>

### 등록
<details>
  <summary>동작</summary>
<img style="display: block" alt="등록" src="https://user-images.githubusercontent.com/59603575/118422635-90125100-b6fe-11eb-878d-ff209f1d7659.gif">
</details>

- 개별 등록
- 파일로 대량등록 (Excel)
 
<div id="influencer-candidate"/>

### 후보목록
<details>
  <summary>동작</summary>
<img style="display: block" alt="등록" src="https://user-images.githubusercontent.com/59603575/118425100-690a4e00-b703-11eb-9744-b39ee6c1cefb.gif">
</details>

- 조회
- 다운
- 블랙리스트로 이동
- 정렬방식 변경 (최신순, 구독자순)
- 페이징

<div id="influencer-black"/>

### 블랙목록
<details>
  <summary>동작</summary>
<img style="display: block" alt="등록" src="https://user-images.githubusercontent.com/59603575/118425104-6a3b7b00-b703-11eb-8e89-965a9fc01c09.gif">
</details>

- 조회
- 인플루언서로 복원
- 정렬방식 변경 (최신순, 구독자순)
- 페이징

<!-- 캠페인 -->

<div id="campaign"/>

## 캠페인

- 캠페인을 등록하고, 캠페인을 관리(인플루언서 등록, 비디오 등록)합니다.
- 광고주 ID로도 접근할 수 있는 메뉴이며, 광고주로 접근시 광고주가 소유한 캠페인에 대한 정보만 확인할 수 있습니다. 

<div id="campaign-list"/>

### 목록
<details>
  <summary>동작</summary>
<img style="display: block" alt="캠페인 목록" src="https://user-images.githubusercontent.com/59603575/118425584-707e2700-b704-11eb-994c-ed8118a9c2cf.gif">
</details>

- 캠페인 수정
- 인플루언서 추가
- 제안 리스트 (기능 없음)
- 리포트로 이동
- 캠페인 추가

<div id="campaign-regist"/>

### 등록
<details>
  <summary>동작</summary>
<img style="display: block" alt="등록" src="https://user-images.githubusercontent.com/59603575/118425582-6f4cfa00-b704-11eb-8022-d1fca433b20b.gif">
</details>

- 개별등록

<!-- 리포트 -->

<div id="report"/>

## 리포트

- 등록된 캠페인의 일간 리포트를 확인합니다.
- 일간 리포트의 RAW DATA를 다운로드 할 수 있습니다.
- 광고주 ID로도 접근할 수 있는 메뉴이며, 광고주로 접근시 광고주가 소유한 캠페인에 대한 정보만 확인할 수 있습니다. 

<details>
  <summary>동작</summary>
<img style="display: block" alt="리포트" src="https://user-images.githubusercontent.com/59603575/118423806-ce107480-b700-11eb-9d87-23e233ab9504.gif">
</details>

- 차트
- RAW DATA 내려받기
- 테이블

<!-- 세팅 -->

<div id="setting"/>

## 세팅
- 특정 키워드를 기반으로, 특정 권역의 인플루언서 리스트를 크롤링할 수 있습니다. 
- [캠페인 > 등록] / [인플루언서 > 등록] 등에서 사용할 각종 필드들의 값들을 생성하고 삭제합니다.

<div id="setting-crawling"/>

### 크롤링

<details>
  <summary>동작</summary>
<img style="display: block" alt="크롤링" src="https://user-images.githubusercontent.com/59603575/118423809-cf41a180-b700-11eb-8750-90f93b6d51a8.gif">
</details>

- 크롤러 등록
- 크롤러 지우기

<div id="setting-field"/>

### 필드
<details>
  <summary>동작</summary>
<img style="display: block" alt="필드" src="https://user-images.githubusercontent.com/59603575/118423810-d10b6500-b700-11eb-9e57-0fcdff2f2278.gif">
</details>

- 필드 등록 
- 필드 삭제


<!-- contact -->

<div id="contact"/>

## contact

- 개발팀에 문의 (kunwoo242@neicon.net)

## Use tech

<span id="use-tech">
  <img src="https://img.shields.io/badge/Javascript-orange?style=flat-square&logo=JavaScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/css-blue?style=flat-square&logo=CSS3&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML-red?style=flat-square&logo=HTML5&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-blue?style=flat-square&logo=React&logoColor=white"/>
    <img src="https://img.shields.io/badge/Redux-blue?style=flat-square&logo=Redux&logoColor=white"/>
    <img src="https://img.shields.io/badge/Redux-Saga-blue?style=flat-square&logo=Redux-Saga&logoColor=white"/>
    
</span>

---

<img src="https://capsule-render.vercel.app/api?type=soft&color=auto&height=100&section=footer&text=End&fontSize=50&animation=scaleIn" />
