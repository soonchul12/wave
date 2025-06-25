# 🌊 Wave Animation Project

Canvas API를 사용하여 구현한 인터랙티브 파도 애니메이션 프로젝트입니다.

## 📖 프로젝트 소개

이 프로젝트는 [YouTube 튜토리얼](https://www.youtube.com/watch?v=LLfhY4eVwDY)을 참고하여 제작된 웹 기반 파도 애니메이션입니다. HTML5 Canvas와 JavaScript를 활용하여 부드러운 파도 효과를 구현했습니다.

## ✨ 주요 기능

- **실시간 파도 애니메이션**: Canvas API를 사용한 부드러운 파도 움직임
- **인터랙티브 요소**: 마우스 움직임에 반응하는 파도 효과
- **반응형 디자인**: 다양한 화면 크기에 적응
- **성능 최적화**: 효율적인 렌더링 시스템

## 🛠️ 기술 스택

- **HTML5**: 웹 페이지 구조
- **CSS3**: 스타일링 및 레이아웃
- **JavaScript (ES6+)**: 애니메이션 로직 및 인터랙션
- **Canvas API**: 그래픽 렌더링

## 📁 파일 구조

```
wave-animation/
├── index.html          # 메인 HTML 파일
├── style.css           # 스타일시트
├── app.js              # 메인 애플리케이션 로직
├── wave.js             # 파도 애니메이션 클래스
├── wavegroup.js        # 파도 그룹 관리 클래스
├── point.js            # 포인트 클래스
└── README.md           # 프로젝트 문서
```

## 🚀 사용법

1. 프로젝트를 클론하거나 다운로드합니다
2. `index.html` 파일을 웹 브라우저에서 엽니다
3. 마우스를 움직여 파도 애니메이션을 확인합니다

## 🎯 주요 클래스 설명

### Wave 클래스
파도 애니메이션의 핵심 로직을 담당합니다. 사인파를 사용하여 자연스러운 파도 움직임을 구현합니다.

### WaveGroup 클래스
여러 개의 파도를 그룹으로 관리하여 복잡한 파도 효과를 만듭니다.

### Point 클래스
파도 위의 개별 포인트들을 관리합니다.

## 📚 참고 자료

- [YouTube 튜토리얼](https://www.youtube.com/watch?v=LLfhY4eVwDY) - 이 프로젝트의 기반이 된 영상
- [MDN Canvas API](https://developer.mozilla.org/ko/docs/Web/API/Canvas_API) - Canvas API 문서

## 🤝 기여하기

1. 이 저장소를 포크합니다
2. 새로운 기능 브랜치를 생성합니다 (`git checkout -b feature/AmazingFeature`)
3. 변경사항을 커밋합니다 (`git commit -m 'Add some AmazingFeature'`)
4. 브랜치에 푸시합니다 (`git push origin feature/AmazingFeature`)
5. Pull Request를 생성합니다

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 👨‍💻 개발자

- **이름**: [Kwon soonchul]

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요! 
