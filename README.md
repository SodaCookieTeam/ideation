# 🎲 무작위성 주입기 (Randomness Injector)

> 일상에 통제된 카오스를 추가하는 웹 애플리케이션

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📖 소개

**무작위성 주입기**는 예측 가능한 일상에서 벗어나 새로운 경험과 자극을 제공하는 웹 서비스입니다. 

매일 반복되는 루틴에 지치셨나요? 🔄  
항상 같은 식당, 같은 길, 같은 일상에서 벗어나고 싶으신가요? 🌟  

이제 **주사위 한 번**으로 삶에 즐거운 변화를 더해보세요!

## ✨ 주요 기능

### 🎯 랜덤 미션 시스템
- 일상, 관계, 음식, 스킬, 모험 등 다양한 카테고리의 미션
- 난이도별 분류 (쉬움 ⭐ / 중급 ⭐⭐ / 도전 ⭐⭐⭐)
- 언제든지 새로운 미션 받기

### 📊 통계 & 성취 추적
- 완료한 미션 수 추적
- 연속 달성 기록
- 카오스 레벨 시스템
- 미션 히스토리 확인

### 🎨 게이미피케이션
- 레벨 시스템 (일상인 → 예측불가)
- 뱃지 수집
- 완료 시 축하 애니메이션

### 💾 로컬 저장
- 브라우저 로컬스토리지에 데이터 저장
- 계정 없이 바로 사용 가능
- 개인정보 걱정 없음

## 🚀 시작하기

### 온라인으로 바로 사용
웹 브라우저에서 바로 접속: [Demo Link] (추후 추가 예정)

### 로컬 실행
```bash
# 저장소 클론
git clone https://github.com/YOUR_USERNAME/soda_cookie.git

# 디렉토리 이동
cd soda_cookie

# index.html 파일을 브라우저에서 열기
# 방법 1: 파일 탐색기에서 index.html 더블클릭
# 방법 2: Live Server 사용 (VSCode 확장)
```

## 📱 사용 방법

1. **미션 받기**: "🎲 새로운 미션 받기" 버튼 클릭
2. **카테고리 선택**: 원하는 카테고리 필터링 가능
3. **미션 실행**: 미션을 읽고 실제로 실행해보세요!
4. **완료 표시**: "✅ 미션 완료" 버튼으로 성취 기록
5. **통계 확인**: 내가 얼마나 예측 불가능한 삶을 사는지 확인

## 🎮 미션 예시

- 🚶 "출근길에 평소와 다른 경로로 가기"
- ☕ "가본 적 없는 카페에서 메뉴판 보지 않고 주문하기"
- 💬 "1년 이상 연락 안 한 친구에게 안부 물어보기"
- 🎵 "평소 안 듣던 장르의 음악 30분 듣기"
- 📚 "서점/도서관에서 눈 감고 랜덤으로 책 고르기"
- 🍜 "이름만 보고 처음 보는 음식 주문하기"
- 🎨 "30분 동안 낙서하기 (주제: 랜덤 단어)"

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox/Grid, 애니메이션, 반응형 디자인
- **Vanilla JavaScript**: 프레임워크 없는 순수 JS
- **LocalStorage API**: 데이터 영속성
- **Geolocation API**: 위치 기반 기능 (선택)

## 📂 프로젝트 구조

```
soda_cookie/
├── index.html          # 메인 HTML 파일
├── style.css           # 스타일시트
├── script.js           # JavaScript 로직
├── README.md           # 프로젝트 설명
├── .gitignore          # Git 제외 파일
└── IDEATION/           # 아이디어 문서
    └── 무작위성_주입기.md
```

## 🌟 특징

### 왜 무작위성 주입기인가?

| 일반 To-Do 앱 | 무작위성 주입기 |
|---------------|----------------|
| 할 일 관리 | 새로운 경험 제공 |
| 사용자가 결정 | 랜덤이 결정 |
| 생산성 중심 | 재미와 모험 중심 |
| 지루할 수 있음 | 항상 신선함 |

### 핵심 가치
- 🔄 **탈루틴화**: 반복되는 일상 탈출
- 🎲 **세렌디피티**: 우연한 발견의 즐거움
- ✅ **실행 가능성**: 현실적으로 할 수 있는 미션
- 🎉 **재미와 성장**: 즐기면서 배우기

## 🎯 로드맵

### v1.0 (현재)
- [x] 기본 미션 시스템
- [x] 카테고리 필터링
- [x] 로컬 히스토리 저장
- [x] 통계 추적
- [ ] JavaScript 로직 구현 (진행 중)

### v1.1 (예정)
- [ ] 위치 기반 식당 룰렛
- [ ] PWA 지원 (오프라인 사용)
- [ ] 다크 모드

### v2.0 (계획)
- [ ] 사용자 계정 시스템
- [ ] 친구 초대 및 미션 공유
- [ ] AI 맞춤형 미션 생성
- [ ] 커뮤니티 미션 업로드

## 🤝 기여하기

프로젝트에 기여하고 싶으신가요? 환영합니다! 🎉

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 기여 아이디어
- 새로운 미션 아이디어 제안
- 버그 리포트
- 기능 개선 제안
- 번역 (다국어 지원)

## 📝 라이센스

이 프로젝트는 MIT 라이센스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 💭 피드백 & 문의

- 버그 리포트: [Issues](https://github.com/YOUR_USERNAME/soda_cookie/issues)
- 기능 제안: [Discussions](https://github.com/YOUR_USERNAME/soda_cookie/discussions)
- 이메일: your.email@example.com

## 🎨 스크린샷

(추후 추가 예정)

## 🙏 감사의 말

이 프로젝트는 일상의 루틴에 지친 모든 분들에게 영감을 받아 만들어졌습니다.

---

**"예측 불가능한 삶이야말로 가장 재미있는 삶이다."** 🎲

Made with ❤️ by [Your Name]

---

⭐ 이 프로젝트가 마음에 드셨다면 Star를 눌러주세요!
