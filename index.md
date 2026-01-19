---
layout: default
---

<style>
  /* 1. 전체 레이아웃 및 여백 최적화 */
  .markdown-body {
    max-width: 900px !important;
    margin: 0 auto !important;
    padding: 100px 40px !important; /* 섹션 간 상하 여백 대폭 확대 */
    font-size: 18px !important;     /* 전체 글씨 크기 상향 */
    line-height: 1.8;
    word-break: keep-all;
    text-align: left !important;
    color: #2d3436;
  }

  /* 헤더, 푸터 등 불필요한 테마 요소 제거 */
  header, footer, .site-header, .site-footer, .breadcrumb { display: none !important; }

  /* 2. 제목 스타일 및 줄바꿈 방지 */
  h1 { 
    font-size: 2.6em !important; 
    font-weight: 800 !important;
    margin-bottom: 50px !important;
    line-height: 1.3 !important;
    word-break: keep-all; /* 단어 단위 줄바꿈으로 깔끔하게 */
  }
  h2 { 
    margin-top: 100px !important; /* 섹션 시작 전 여백 확보 */
    margin-bottom: 30px !important;
    border-bottom: 2px solid #f1f2f6; 
    padding-bottom: 15px;
    font-size: 1.8em !important;
  }
  h3 { margin-top: 40px !important; color: #0984e3; }

  /* 3. 이미지 가로 배치 (깨지는 표 기능 대체) */
  .image-container {
    display: flex;
    gap: 25px;
    margin: 30px 0;
  }
  .image-item {
    flex: 1;
    text-align: center;
  }
  .image-item img {
    width: 100%;
    height: 380px; /* 이미지 높이 통일 */
    object-fit: cover;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    transition: transform 0.3s ease;
    cursor: zoom-in;
  }
  .image-item img:hover { transform: translateY(-8px); }
  .image-label { margin-top: 15px; font-weight: 600; color: #636e72; font-size: 0.95em; }

  /* 4. 링크 및 버튼 스타일 */
  .cert-link { 
    color: #0984e3 !important; 
    text-decoration: underline !important; 
    font-weight: bold; 
    margin-left: 8px;
  }
  .btn {
    display: inline-block;
    padding: 14px 30px;
    background: #0984e3;
    color: #fff !important;
    border-radius: 50px;
    text-decoration: none !important;
    font-weight: bold;
    margin: 25px 0;
    transition: 0.3s;
  }
  .btn:hover { background: #074a81; }

  /* 모바일 대응: 이미지를 세로로 쌓음 */
  @media (max-width: 768px) {
    .image-container { flex-direction: column; }
    .image-item img { height: auto; }
    h1 { font-size: 2em !important; }
  }
</style>

# [문제를 해결하는 제너럴리스트, 이건희입니다]

> "감성의 언어로 소통하고, 기술의 도구로 문제를 해결합니다."  
> 📧 liongun3@naver.com | gunlee41@kakao.com  

---

## 1. 소개 (Introduction)
하나의 직무에 갇히기보다 도구를 가리지 않고 사용하는 인재입니다.

<a href="assets/images/human.jpg" target="_blank">
  <img src="assets/images/human.jpg" alt="인권센터 활동" style="width:100%; border-radius:15px; box-shadow: 0 10px 30px rgba(0,0,0,0.08);">
</a>
<p align="center" style="font-size: 0.9em; color: #b2bec3; margin-top: 15px;">▲ 이미지를 클릭하면 새 창에서 원본을 크게 볼 수 있습니다.</p>

---

## 2. 주요 프로젝트 (Projects)

### 📌 Project 1. AI 협업 게임 'Weather is What'
전문 코딩 지식이 없어도 LLM을 활용해 실제 서비스를 구현해내는 실행력을 갖췄습니다.

<a href="assets/images/game.png" target="_blank">
  <img src="assets/images/game.png" alt="게임 구동 화면" style="width:100%; border-radius:15px;">
</a>

<div align="center">
  <a href="https://gunlee41.github.io/weatheriswhat/" class="btn" target="_blank">🎮 게임 플레이해보기</a>
</div>

<br>

### 📌 Project 2. 시집 <낚시> 출판
<div class="image-container">
  <div class="image-item">
    <a href="assets/images/poetry_book.png" target="_blank"><img src="assets/images/poetry_book.png"></a>
    <div class="image-label">시집 <낚시> 발간</div>
  </div>
  <div class="image-item">
    <a href="assets/images/poet.jpg" target="_blank"><img src="assets/images/poet.jpg"></a>
    <div class="image-label">등단 및 신인상 수상</div>
  </div>
</div>

<br>

### 📌 Project 3. 콘텐츠 채널 성장전략
<div class="image-container">
  <div class="image-item">
    <a href="assets/images/insta.png" target="_blank"><img src="assets/images/insta.png"></a>
    <div class="image-label">인스타그램 운영</div>
  </div>
  <div class="image-item">
    <a href="assets/images/support.png" target="_blank"><img src="assets/images/support.png"></a>
    <div class="image-label">브랜드 협찬 사례</div>
  </div>
</div>

---

## 3. 업무 스킬 & 자격 (Skills & Docs)
* **Google Analytics (GA4):** 데이터 기반 의사결정 가능 <a href="assets/images/GA.pdf" target="_blank" class="cert-link">[📄 수료증 확인]</a>
* **Notion:** 협업 툴 구축 및 매뉴얼화 능숙 <a href="assets/images/notion.pdf" target="_blank" class="cert-link">[📄 수료증 확인]</a>
* **Design:** 포토샵, 일러스트레이터, 인디자인 활용 가능

---

<p align="center" style="margin-top: 100px; color: #dfe6e9;">감사합니다.</p>
