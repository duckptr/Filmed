# Filmed 🎬

TMDB API를 활용하여 제작한 영화 정보 웹앱입니다.  
React 기반으로 최신 인기 영화 데이터를 자동으로 불러오고,  
슬라이드 UI와 모달 상세보기 기능을 제공합니다.

👉 **배포 링크**: [filmed.vercel.app](https://filmed-3153r0429-chorongs-projects.vercel.app/)

---

## ✨ 주요 기능

- 🎞️ TMDB API 연동 (실시간 인기/신작 영화 데이터)
- 🎨 넷플릭스 스타일 UI 구성
- 🖱️ 영화 카드 클릭 시 모달로 상세 정보 확인
- 📱 반응형 레이아웃
- 🔁 카테고리별 슬라이드(좌우 이동)

---

## 🛠 기술 스택

- ⚛️ React (Create React App)
- 💅 Styled-Components
- 🌐 Axios
- 🔐 TMDB API
- 📦 Vercel 배포

---

## 🚀 실행 방법

bash
# 1. 저장소 클론
git clone https://github.com/duckptr/filmed.git
cd filmed

# 2. 패키지 설치
npm install

# 3. 환경 변수 설정 (.env 파일 생성)
echo "REACT_APP_TMDB_API_KEY=your_tmdb_api_key_here" > .env

# 4. 실행
npm start

---

📦 src
 ┣ 📂 api
 ┃ ┗ 📜 movie.js
 ┣ 📂 components
 ┃ ┣ 📜 Banner.js
 ┃ ┣ 📜 MovieModal.js
 ┃ ┗ 📜 Row.js
 ┣ 📜 App.js
 ┣ 📜 index.js
 ┗ 📜 index.css

---

## 👨‍💻 개발자

- 김명준 ([duckptr](https://github.com/duckptr))
