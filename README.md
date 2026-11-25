<div align="center">

# 이름 | 포트폴리오

<!-- 두 표를 한 테이블로 합쳐 가로폭을 동일하게 맞춤 (GitHub는 표 width 지정을 무시함) -->
<table>
<tr><th colspan="3"><h2>배포 중인 프로젝트</h2></th></tr>
<tr><th>프로젝트</th><th>소개</th><th>바로가기</th></tr>
<tr><td align="center"><b>fridgeO</b></td><td align="center">냉장고 재료 관리와 레시피 추천 서비스 (4인 팀)</td><td align="center"><a href="https://fridgeo.pages.dev">fridgeo.pages.dev</a></td></tr>
<tr><td align="center"><b>Re:Rail</b></td><td align="center">코레일 홈페이지 리디자인 (4인 팀)</td><td align="center"><a href="https://leesansa.github.io/re_rail/">leesansa.github.io/re_rail</a></td></tr>
<tr><td align="center"><b>game_servise</b></td><td align="center">게임 소개 사이트 퍼블리싱 (개인)</td><td align="center"><a href="https://leesansa.github.io/game_servise/">leesansa.github.io/game_servise</a></td></tr>
<tr><th colspan="3"><h2>기술 스택</h2></th></tr>
<tr><th>구분</th><th colspan="2">사용한 기술</th></tr>
<tr><td align="center"><b>언어</b></td><td colspan="2" align="center"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"> <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white" alt="CSS"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"></td></tr>
<tr><td align="center"><b>프론트엔드</b></td><td colspan="2" align="center"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"> <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="TanStack Query"></td></tr>
<tr><td align="center"><b>백엔드</b></td><td colspan="2" align="center"><img src="https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white" alt="Hono"></td></tr>
<tr><td align="center"><b>DB</b></td><td colspan="2" align="center"><img src="https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black" alt="Neon"></td></tr>
<tr><td align="center"><b>배포</b></td><td colspan="2" align="center"><img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare"> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"> <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages"></td></tr>
<tr><td align="center"><b>AI 도구</b></td><td colspan="2" align="center"><img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"> <img src="https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge" alt="ChatGPT"> <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude"></td></tr>
</table>

## 소개

> 한 줄 소개 — 예: 사용자 경험을 숫자로 증명하는 프론트엔드 개발자입니다.

<!-- 프로필 이미지: assets/profile.png 에 넣고 아래 주석 해제 -->
<!-- <img src="assets/profile.png" width="120" alt="프로필 사진"> -->

minhyung7009@naver.com<br>
&nbsp;·&nbsp; <br>
&nbsp;·&nbsp; <br>
[github.com/leesansa](https://github.com/leesansa)<br>

## 프로젝트 상세

### fridgeO

**냉장고에 뭐가 남았는지 확인하고, 그 재료로 오늘 뭐 해 먹을지 고르는 서비스**

| 기간 | 인원 | 내 역할 | 기술 |
| :---: | :---: | :---: | :---: |
| 2026.11.04 ~ 11.20 (17일) | 4인 팀 | 메인 화면, 서버, DB, 배포 | React, TanStack Query, Hono, Neon, Cloudflare |

**내가 한 일**<br>
메인 화면, 알림, 하단 메뉴<br>
로그인 · 회원가입 · 휴대폰 문자 인증<br>
Neon DB 구축, 서버를 Hono(Cloudflare Workers)로 전환<br>
GitHub Actions로 lint · 테스트 후 자동 배포

**트러블슈팅**<br>
화면마다 데이터를 따로 불러와 저장 후에도 예전 값이 보이던 문제 → React Query로 데이터 불러오기를 한곳에 모아 해결<br>
프론트엔드 39건, 서버 23건의 문제 해결 과정을 문서로 정리

[서비스](https://fridgeo.pages.dev) &nbsp;·&nbsp; [GitHub](https://github.com/leesansa/fridgeO)

---

### Re:Rail

**코레일 홈페이지의 불편하고 낡은 부분을 고쳐 다시 디자인한 리뉴얼 프로젝트**

| 기간 | 인원 | 내 역할 | 기술 |
| :---: | :---: | :---: | :---: |
| 2026.09 ~ 10 | 4인 팀 | Git · 코드 관리, 예약/예매 페이지 | HTML, CSS, JavaScript |

**내가 한 일**<br>
팀 Git 저장소와 코드 관리<br>
예약 · 예매 페이지, 예매 시간표<br>
역 선택 지도

**트러블슈팅**<br>
지도에서 역을 정확히 클릭하고 화면 크기가 바뀌어도 맞아야 하는 문제 → 비트 마스크와 좌표 백분율 변환으로 해결<br>
도착일이 출발일보다 빠르게 선택되던 버그 → 출발일 이전 날짜는 고를 수 없도록 제한<br>
예약 팝업의 인원 체크가 연동되지 않던 버그 → 흩어진 JS 파일을 정리해 다시 연결

[사이트](https://leesansa.github.io/re_rail/) &nbsp;·&nbsp; [GitHub](https://github.com/leesansa/re_rail)

---

### game_servise

**게임 공식 사이트 구조를 참고해 여러 페이지를 직접 퍼블리싱한 개인 프로젝트**

| 기간 | 인원 | 내 역할 | 기술 |
| :---: | :---: | :---: | :---: |
| 2026.09 ~ 10 | 개인 | 기획 · 퍼블리싱 전체 | HTML, CSS, JavaScript |

**만든 화면**<br>
소식(메인) · 콘텐츠 · 직업 · 지역 · 공성 · 미디어 · 로그인<br>
페이지 공통 헤더 내비게이션<br>
로그인 입력 공백 검사와 버튼 활성화 UI

[사이트](https://leesansa.github.io/game_servise/) &nbsp;·&nbsp; [GitHub](https://github.com/leesansa/game_servise)

## 📜 경력 · 활동

YYYY.MM – YYYY.MM · 소속 / 활동명 · 한 줄 요약

</div>
