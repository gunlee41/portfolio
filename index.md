---
layout: default
title: 이건희 포트폴리오
---

<!-- 1. 스타일 정의 : 지저분한 헤더/푸터를 숨기고 배경색을 통일합니다 -->
<style>
  /* 상단 검은색 헤더와 깃허브 버튼 숨기기 */
  header, .site-header, #forkme_banner { display: none !important; }
  
  /* 하단 푸터 숨기기 */
  footer, .site-footer { display: none !important; }
  
  /* 배경색을 옅은 회색으로 통일하여 눈이 편안하게 만듦 */
  body { 
    background-color: #f7f7f7 !important; 
    color: #333 !important;
  }
  
  /* 내용이 너무 위로 붙지 않게 여백 추가 */
  .main-content { margin-top: 50px; }

  /* 이미지 배치를 위한 스타일 (표 대신 사용) */
  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    align-items: flex-start;
  }
  .image-item {
    width: 48%; /* 이미지 두 개를 나란히 놓기 위함 */
  }
  .image-item img {
    width: 100%;
    border-radius: 5px; /* 모서리 둥글게 */
    box-shadow: 0 2px 5px rgba(0,0,0,0.1); /* 살짝 그림자 */
  }
</style>

<!-- 2. 본문 시작 : 헤더를 지웠으므로 제목을 다시 써줍니다 -->
# [문제를 해결하는 제너럴리스트, 이건희입니다]

> "감성의 언어로 소통하고, 기술의 도구로 문제를 해결합니다."  
> 📧 Email: liongun3@naver.com  
> 🔗 Github: [github.com/gunlee41](https://github.com/gunlee41)

---

## 1. 소개 (Introduction)

하나의 직무에 갇히기보다, **문제를 해결하는 데 필요한 도구를 가리지 않고 사용하는 보편적인 인재**입니다.  
글쓰기(기획), 디자인(시각화), 그리고 데이터와 코딩(구현)을 넘나들며, 조직에 비어 있는 부분을 채우고 **'일이 되게 만드는 역할'**을 수행합니다.

<!-- 인권센터 사진 -->
<div align="center">
  <img src="assets/images/human.jpg" width="60%" style="border-radius:5px;">
  <br>
  <em>▲ 대전 인권센터 기자단 활동 및 공익 활동 증빙</em>
</div>

---

## 2. 주요 프로젝트 (Projects)

### 📌 Project 1. AI 협업 게임 'Weather is What'
**"기획한 것을 끝까지 구현해내는 실행력"**

전문 코딩 지식이 없어도, **LLM(AI)을 파트너로 활용**하여 아이디어를 실제 작동하는 웹 서비스로 구현했습니다.
단순한 날씨 정보가 아닌, 날씨 요소를 모아 점수를 내는 **셋 컬렉션(Set Collection)** 장르의 게임입니다.

*   **역할:** 게임 기획(룰 디자인), AI 프롬프트 엔지니어링, 배포
*   **기술:** HTML/CSS, JS, ChatGPT Prompting

<!-- 게임 화면 -->
<div align="center">
  <img src="assets/images/game.png" width="90%" style="border-radius:5px; border:1px solid #ddd;">
</div>

### 👉 [🎮 여기를 눌러 게임을 직접 플레이해보세요](https://gunlee41.github.io/weatheriswhat/)

<br>
<br> <!-- 간격을 띄워서 덜 답답하게 함 -->

### 📌 Project 2. 시집 <낚시> 출판 및 작가 활동
**"무(無)에서 유(有)를 만드는 기획력"**

단순 집필을 넘어 기획, 편집 디자인, 유통 계약까지 1인 출판의 전 과정을 수행하며 **완결성 있는 결과물**을 만들었습니다.

*   **성과:** 등단 작가(신인상), 시집 독립출판, 매거진 기고
*   **증빙:**
    *   [📄 잡지 기고문(PDF) 보기](assets/images/magazine.pdf)
    *   [📄 인터뷰 전문 이미지 보기](assets/images/interview.jpg)

<!-- 여기서부터 HTML 방식으로 이미지를 배치합니다 (표 깨짐 방지) -->
<div class="image-container">
  <div class="image-item">
    <img src="assets/images/poetry_book.png">
    <p align="center"><em>▲ 직접 제작한 시집</em></p>
  </div>
  <div class="image-item">
    <img src="assets/images/poet.jpg">
    <p align="center"><em>▲ 등단 상장</em></p>
  </div>
</div>

<br>
<br>

### 📌 Project 3. 콘텐츠 채널 성장전략
**"데이터와 감성을 연결하는 마케팅"**

감성적인 콘텐츠 기획과 협찬/제휴를 통해 채널을 성장시켰습니다.

*   **성과:** 인스타그램 팔로워 1.3k, 브랜드 협찬 및 제휴 달성
*   **역할:** 채널 운영, 카드뉴스 제작, 데이터 분석

<!-- 인스타그램 이미지 배치 -->
<div class="image-container">
  <div class="image-item">
    <img src="assets/images/insta.png">
    <p align="center"><em>▲ 운영 채널 피드</em></p>
  </div>
  <div class="image-item">
    <img src="assets/images/support.png">
    <p align="center"><em>▲ 브랜드 협찬 성과</em></p>
  </div>
</div>

---

<br>

### 🎁 Bonus Project. 현재 보고 계신 이 포트폴리오
**"과정 자체가 증명하는 습득력"**

이 사이트는 별도의 웹 빌더(Wix, I'mweb)나 유료 호스팅 없이, **Github Pages와 마크다운(Markdown)**을 익혀 직접 제작했습니다.
코드가 낯설어 화면 레이아웃이 깨지는 시행착오가 있었으나, **AI와의 협업과 리서치**를 통해 즉시 해결하고 배포까지 완료했습니다.

*   **제작 기간:** 1일 (Fast Prototyping)
*   **비용:** 0원 (오픈소스 활용 및 자체 제작)
*   **사용 기술:** Github, HTML/CSS Mix, AI Prompting
*   **의의:** 필요한 도구가 있다면, 망설이지 않고 배워서 **내 것으로 만듭니다.**

---

## 3. 업무 스킬 & 자격 (Skills & Docs)

실무에 즉시 투입 가능한 문서 작성 및 데이터 분석 능력입니다.

### 🛠️ Tools & Certification
*   **Google Analytics (GA4):** 데이터 기반의 의사결정 가능
    *   [📄 고급 Google 애널리틱스 수료증 보기](assets/images/GA.pdf)
*   **Notion (노션):** 협업 툴 구축 및 업무 매뉴얼화 능숙
    *   [📄 직접 제작한 '일 잘하는 법' 노션 가이드 보기](assets/images/notion.pdf)
*   **Design:** 포토샵, 일러스트레이터, 인디자인 (상업용 활용 가능)

---

### 감사합니다.
<br>
<br>
