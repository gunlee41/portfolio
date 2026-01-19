---
layout: default
---

<style>
  /* 1. 레이아웃 및 전체 톤앤매너 */
  :root {
    --primary-color: #2d3436;
    --accent-color: #0984e3;
    --bg-color: #ffffff;
    --text-color: #2d3436;
  }

  .markdown-body {
    max-width: 850px !important;
    margin: 0 auto !important;
    padding: 60px 40px !important;
    font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif !important;
    color: var(--text-color) !important;
    line-height: 1.8 !important;
    text-align: left !important;
    background-color: var(--bg-color);
  }

  /* 2. 헤더/푸터 강제 제거 */
  header, footer, .site-header, .site-footer, .breadcrumb {
    display: none !important;
  }

  /* 3. 제목 및 강조 스타일 */
  h1 { border-bottom: 2px solid var(--primary-color); padding-bottom: 15px; font-weight: 800; }
  h2 { margin-top: 50px !important; border-left: 5px solid var(--accent-color); padding-left: 15px; }
  h3 { color: var(--accent-color); margin-top: 30px !important; }
  blockquote { background: #f1f2f6 !important; border-left: 5px solid var(--accent-color) !important; color: #57606f !important; }

  /* 4. 이미지 및 카드 스타일링 */
  img { 
    display: block;
    margin: 20px auto;
    max-width: 100%;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    transition: transform 0.3s ease;
  }
  img:hover { transform: translateY(-5px); }

  /* 5. 표(Table) 최적화 - 이미지 배치용 */
  table {
    display: table !important;
    width: 100% !important;
    border-collapse: separate !important;
    border-spacing: 15px 0 !important;
    border: none !important;
    margin: 20px 0 !important;
  }
  table tr, table td { border: none !important; background: transparent !important; vertical-align: top; }
  table td { width: 50%; }
  
  /* 표 내부 이미지 높이 맞춤 */
  table img {
    width: 100% !important;
    height: 250px !important;
    object-fit: cover; /* 사진 비율 유지하며 꽉 채움 */
    margin: 0 !important;
  }

  /* 6. 링크 버튼 스타일 */
  .play-button {
    display: inline-block;
    padding: 12px 25px;
    background-color: var(--accent-color);
    color: white !important;
    text-decoration: none !important;
    border-radius: 30px;
    font-weight: bold;
    margin: 20px 0;
    box-shadow: 0 4px 15px rgba(9, 132, 227, 0.3);
  }
  
  /* 모바일 최적화 */
  @media (max-width: 768px) {
    .markdown-body { padding: 30px 20px !important; }
    table td { display: block; width: 100%; margin-bottom: 20px; }
  }
</style>

# 문제를 해결하는 제너럴리스트, 이건희입니다

> **"감성의 언어로 소통하고, 기술의 도구로 문제를 해결합니다."** > 📧 Email: liongun3@naver.com / gunlee41@kakao.com  

---

## 1. 소개 (Introduction)

하나의 직무에 갇히기보다, **문제를 해결하는 데 필요한 도구를 가리지 않고 사용하는 보편적인 인재**입니다.  
글쓰기(기획), 디자인(시각화), 그리고 데이터와 코딩(구현)을 넘나들며, 조직에 비어 있는 부분을 채우고 **'일이 되게 만드는 역할'**을 수행합니다.

<img src="assets/images/human.jpg" alt="인권센터 활동 확인" style="width:100%; max-height:400px; object-fit:cover;">
<p align="center" style="color: #888; font-size: 0.9em;">▲ 대전 인권센터 기자단 활동 및 공익 활동 증빙</p>

---

## 2. 주요 프로젝트 (Projects)

### 📌 Project 1. AI 협업 게임 'Weather is What'
**"기획한 것을 끝까지 구현해내는 실행력"**

전문 코딩 지식이 없어도, **LLM(AI)을 파트너로 활용**하여 아이디어를 실제 작동하는 웹 서비스로 구현했습니다. 단순한 날씨 정보가 아닌, 날씨 요소를 모아 점수를 내는 **셋 컬렉션(Set Collection)** 장르의 게임입니다.

* **역할:** 게임 기획(룰 디자인), AI 프롬프트 엔지니어링, 배포
* **기술:** HTML/CSS, JS, ChatGPT Prompting

<img src="assets/images/game.png" alt="게임 구동 화면" style="width: 80%;">

<p align="center">
  <a href="https://gunlee41.github.io/weatheriswhat/" class="play-button">🎮 여기를 눌러 게임을 직접 플레이해보세요</a>
</p>

<br>

### 📌 Project 2. 시집 <낚시> 출판 및 작가 활동
**"무(無)에서 유(有)를 만드는 기획력"**

단순 집필을 넘어 기획, 편집 디자인, 유통 계약까지 1인 출판의 전 과정을 수행하며 **완결성 있는 결과물**을 만들었습니다.

* **성과:** 등단 작가(신인상), 시집 독립출판, 매거진 기고
* **증빙:** [📄 잡지 기고문(PDF)](assets/images/magazine.pdf) / [📄 인터뷰 전문](assets/images/interview.pdf)

| 시집 <낚시> 발간 | 등단 및 신인상 수상 |
| :---: | :---: |
| ![시집 표지](assets/images/poetry_book.png) | ![등단 상장](assets/images/poet.jpg) |

<br>

### 📌 Project 3. 콘텐츠 채널 성장전략
**"데이터와 감성을 연결하는 마케팅"**

감성적인 콘텐츠 기획과 협찬/제휴를 통해 채널을 성장시켰습니다. 팔로워 1.3k 달성 및 다양한 브랜드 제휴를 성공시켰습니다.

| 인스타그램 운영 | 브랜드 협찬 사례 |
| :---: | :---: |
| ![인스타 계정](assets/images/insta.png) | ![협찬 내역](assets/images/support.png) |

---

## 3. 업무 스킬 & 자격 (Skills & Docs)

실무에 즉시 투입 가능한 문서 작성 및 데이터 분석 능력입니다.

### 🛠️ Tools & Certification
* **Google Analytics (GA4):** 데이터 기반의 의사결정 가능 ([📄 수료증 확인](assets/images/GA.pdf))
* **Notion (노션):** 협업 툴 구축 및 업무 매뉴얼화 능숙 ([📄 가이드 보기](assets/images/notion.pdf))
* **Design:** 포토샵, 일러스트레이터, 인디자인 (상업용 활용 가능)

---

<p align="center" style="margin-top: 100px; color: #bdc3c7;">© 2024 LEE GUN HEE. All rights reserved.</p>
