---
layout: default
---

<style>
  /* [1] 기본 레이아웃 및 텍스트 스타일 */
  .markdown-body {
    max-width: 800px !important;
    margin: 0 auto !important;
    text-align: left !important;
    padding: 50px 30px !important;
    line-height: 1.8;
  }
  header, footer, .site-header, .site-footer { display: none !important; }

  /* [2] 이미지 기본 스타일 및 애니메이션 */
  img { 
    border-radius: 12px; 
    box-shadow: 0 5px 20px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
    cursor: zoom-in;
    display: block;
    margin: 15px auto;
  }
  img:hover { transform: translateY(-5px); }

  /* [3] 표 내부 이미지 정렬 */
  table { width: 100% !important; border: none !important; table-layout: fixed; }
  table td { border: none !important; padding: 10px !important; }
  .img-box img {
    width: 100% !important;
    height: 250px !important;
    object-fit: cover;
  }

  /* [4] 이미지 확대 모달(Lightbox) 스타일 */
  #modal {
    display: none;
    position: fixed;
    z-index: 9999;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background-color: rgba(0,0,0,0.85);
    cursor: zoom-out;
    align-items: center;
    justify-content: center;
  }
  #modal img {
    max-width: 90%;
    max-height: 90%;
    box-shadow: 0 0 30px rgba(0,0,0,0.5);
    transform: none !important; /* 모달 내에선 애니메이션 해제 */
    cursor: default;
  }
</style>

<div id="modal" onclick="this.style.display='none'">
  <img id="modal-img" src="" alt="확대 이미지">
</div>

# [문제를 해결하는 제너럴리스트, 이건희입니다]

> "감성의 언어로 소통하고, 기술의 도구로 문제를 해결합니다."  <br>
> 📧 liongun3@naver.com | gunlee41@kakao.com  

---

## 1. 소개 (Introduction)
하나의 직무에 갇히기보다 도구를 가리지 않고 사용하는 인재입니다.

<img src="assets/images/human.jpg" alt="인권센터 활동" onclick="openModal(this.src)">
<p align="center" style="font-size: 0.85em; color: #888;">▲ 이미지를 클릭하면 화면 내에서 크게 볼 수 있습니다.</p>

---

## 2. 주요 프로젝트 (Projects)

### 📌 Project 2. 시집 <낚시> 출판
| 시집 <낚시> 발간 | 등단 및 신인상 수상 |
| :---: | :---: |
| <div class="img-box"><img src="assets/images/poetry_book.png" onclick="openModal(this.src)"></div> | <div class="img-box"><img src="assets/images/poet.jpg" onclick="openModal(this.src)"></div> |

<br>

### 📌 Project 3. 콘텐츠 채널 성장전략
| 인스타그램 운영 | 브랜드 협찬 사례 |
| :---: | :---: |
| <div class="img-box"><img src="assets/images/insta.png" onclick="openModal(this.src)"></div> | <div class="img-box"><img src="assets/images/support.png" onclick="openModal(this.src)"></div> |

---

## 3. 업무 스킬 & 자격 (Skills & Docs)
* **Google Analytics (GA4):** 데이터 기반 의사결정 가능
* **Notion:** 협업 툴 구축 및 매뉴얼화 능숙
* **Design:** 포토샵, 일러스트레이터, 인디자인 활용 가능

---

<script>
  function openModal(src) {
    const modal = document.getElementById('modal');
    const modalImg = document.getElementById('modal-img');
    modal.style.display = 'flex';
    modalImg.src = src;
  }
</script>

### 감사합니다.
