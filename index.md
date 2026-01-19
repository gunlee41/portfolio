---
layout: default
---

<style>
  /* [1] 가독성 및 전체 폰트 크기 상향 (건희님 설정 유지) */
  .markdown-body {
    max-width: 880px !important;
    margin: 0 auto !important;
    padding: 100px 40px !important;
    font-size: 19px !important;
    line-height: 1.9;
    text-align: left !important;
    color: #2d3436;
  }
  header, footer, .site-header, .site-footer { display: none !important; }

  /* [2] 제목 스타일 */
  h1 { font-size: 2.6em !important; font-weight: 800; margin-bottom: 40px !important; word-break: keep-all; }
  h2 { margin-top: 100px !important; border-bottom: 2px solid #eee; padding-bottom: 10px; font-size: 1.9em !important; }
  h3 { margin-top: 40px !important; color: #0984e3; font-size: 1.4em !important; }

  /* [3] 이미지 가로 배치 레이아웃 */
  .project-flex-row {
    display: flex;
    gap: 30px;
    margin: 30px 0;
  }
  .project-flex-item {
    flex: 1;
    text-align: center;
  }
  .project-flex-item img {
    width: 100%;
    height: 380px;
    object-fit: cover;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: 0.3s;
    cursor: zoom-in; /* 커서 모양 돋보기로 변경 */
  }
  .project-flex-item img:hover { transform: translateY(-10px); }
  .img-caption { margin-top: 15px; font-weight: bold; color: #636e72; }

  /* [4] 링크 및 강조 */
  .cert-link { color: #0984e3 !important; font-weight: bold; text-decoration: underline !important; margin-left: 10px; }
  .btn-action {
    display: inline-block;
    padding: 15px 35px;
    background: #0984e3;
    color: white !important;
    border-radius: 50px;
    text-decoration: none !important;
    font-weight: bold;
    margin: 20px 0;
  }

  /* [5] 이미지 팝업(Lightbox) 스타일 추가 */
  #imageModal {
    display: none; 
    position: fixed; 
    z-index: 1000; 
    left: 0; 
    top: 0; 
    width: 100%; 
    height: 100%; 
    background-color: rgba(0,0,0,0.9); 
    align-items: center; 
    justify-content: center;
  }
  #modalImg {
    max-width: 90%; 
    max-height: 90%; 
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(255,255,255,0.2);
  }
  
  @media (max-width: 768px) {
    .project-flex-row { flex-direction: column; }
    .project-flex-item img { height: auto; }
  }
</style>

# [문제를 해결하는 제너럴리스트, 이건희입니다]

> "감성의 언어로 소통하고, 기술의 도구로 문제를 해결합니다."  
> 📧 liongun3@naver.com | gunlee41@kakao.com  

---

## 1. 소개 (Introduction)
하나의 직무에 갇히기보다 도구를 가리지 않고 사용하는 인재입니다. 시각적인 기획부터 기술적인 구현까지 문제 해결을 위한 최적의 길을 찾습니다.

**특히, 타인의 삶에 깊이 공감하는 인문학적 소양을 바탕으로 '대전 인권센터 기자단' 활동을 수행하며 공익적 가치를 진정성 있게 전달한 경험이 있습니다.** 기술과 감성을 연결하여 신뢰를 주는 커뮤니케이션을 지향합니다.

<!-- 이미지 클릭 시 팝업 함수 호출 -->
<img src="assets/images/human.jpg" alt="소개 이미지" onclick="openModal(this.src)" style="width:100%; border-radius:15px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); cursor: zoom-in;">
<p align="center" style="font-size: 0.9em; color: #b2bec3; margin-top: 15px;">▲ 이미지를 클릭하면 크게 볼 수 있습니다.</p>

---

## 2. 주요 프로젝트 (Projects)

### 📌 Project 1. AI 협업 게임 ‘Weather is What’
전문 코딩 지식이 없어도 LLM을 활용해 실제 서비스를 구현해내는 실행력을 갖췄습니다.

<img src="assets/images/game.png" alt="게임 구동 화면" onclick="openModal(this.src)" style="width:100%; border-radius:15px; cursor: zoom-in;">

<div align="center">
  <a href="https://gunlee41.github.io/weatheriswhat/" class="btn-action" target="_blank">🎮 게임 플레이해보기</a>
</div>

<br>

### 📌 Project 2. 시집 <낚시> 출판
<div class="project-flex-row">
  <div class="project-flex-item">
    <img src="assets/images/poetry_book.png" onclick="openModal(this.src)">
    <div class="img-caption">시집 <낚시> 발간</div>
  </div>
  <div class="project-flex-item">
    <img src="assets/images/poet.jpg" onclick="openModal(this.src)">
    <div class="img-caption">등단 및 신인상 수상</div>
  </div>
</div>

<br>

### 📌 Project 3. 콘텐츠 채널 성장전략
<div class="project-flex-row">
  <div class="project-flex-item">
    <img src="assets/images/insta.png" onclick="openModal(this.src)">
    <div class="img-caption">인스타그램 운영</div>
  </div>
  <div class="project-flex-item">
    <img src="assets/images/support.png" onclick="openModal(this.src)">
    <div class="img-caption">브랜드 협찬 사례</div>
  </div>
</div>

---

## 3. 업무 스킬 & 자격 (Skills & Docs)
* **Google Analytics (GA4):** 데이터 기반 의사결정 가능 <a href="assets/images/GA.pdf" target="_blank" class="cert-link">[📄 수료증 확인]</a>
* **Notion:** 협업 툴 구축 및 매뉴얼화 능숙 <a href="assets/images/notion.pdf" target="_blank" class="cert-link">[📄 수료증 확인]</a>
* **Design:** 포토샵, 일러스트레이터, 인디자인 활용 가능

---

<!-- 감사합니다 문구 크게 수정 -->
<h2 align="center" style="margin-top: 100px; color: #2d3436; border: none;">감사합니다.</h2>

<!-- 이미지 팝업용 HTML 및 스크립트 (건드리지 않으셔도 됩니다) -->
<div id="imageModal" onclick="closeModal()">
  <img id="modalImg">
</div>

<script>
  function openModal(src) {
    document.getElementById('modalImg').src = src;
    document.getElementById('imageModal').style.display = "flex";
  }
  function closeModal() {
    document.getElementById('imageModal').style.display = "none";
  }
</script>
