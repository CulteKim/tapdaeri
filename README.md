# 보령탑대리운전 랜딩페이지 🚗

최신 트렌드를 반영한 현대적인 대리운전 서비스 랜딩페이지입니다.

## ✨ 주요 특징

### 🎨 디자인 트렌드
- **글래스모피즘(Glassmorphism)**: 반투명 배경과 블러 효과
- **그라데이션**: 현대적인 색상 그라데이션
- **미니멀리즘**: 깔끔하고 직관적인 레이아웃
- **다크/라이트 모드**: 사용자 선호도에 따른 테마

### 📱 반응형 디자인
- 모바일, 태블릿, 데스크톱 최적화
- 터치 친화적인 인터페이스
- 접근성 고려 (WCAG 2.1 준수)

### ⚡ 성능 최적화
- 빠른 로딩 속도
- 이미지 지연 로딩
- 스크롤 이벤트 최적화
- PWA 지원

### 🎭 인터랙티브 요소
- 스크롤 애니메이션
- 호버 효과
- 타이핑 애니메이션
- 카운터 애니메이션
- 리플 효과

## 🚀 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - CSS Grid & Flexbox
  - CSS Variables (Custom Properties)
  - CSS Animations & Transitions
  - Backdrop Filter
- **JavaScript (ES6+)**:
  - Intersection Observer API
  - Event Listeners
  - DOM Manipulation
  - Service Workers

## 📁 파일 구조

```
WebPage/
├── index.html          # 메인 HTML 파일
├── styles.css          # CSS 스타일시트
├── script.js           # JavaScript 기능
└── README.md           # 프로젝트 설명서
```

## 🎯 섹션 구성

### 1. 네비게이션 (Navigation)
- 고정 헤더
- 반응형 햄버거 메뉴
- 스크롤 시 배경 변화

### 2. 히어로 섹션 (Hero Section)
- 그라데이션 배경
- 타이핑 애니메이션
- CTA 버튼
- 스크롤 인디케이터

### 3. 서비스 섹션 (Services)
- 4개의 주요 서비스 카드
- 호버 애니메이션
- 아이콘과 설명

### 4. 소개 섹션 (About)
- 회사 특징
- 통계 카운터
- 그리드 레이아웃

### 5. 연락처 섹션 (Contact)
- 연락처 정보
- CTA 섹션
- 플로팅 액션 버튼

### 6. 푸터 (Footer)
- 회사 정보
- 서비스 링크
- 연락처 정보

## 🎨 색상 팔레트

```css
--primary-color: #6366f1    /* 메인 색상 */
--primary-dark: #4f46e5     /* 어두운 메인 */
--secondary-color: #f59e0b  /* 보조 색상 */
--accent-color: #10b981     /* 강조 색상 */
--text-primary: #1f2937     /* 주요 텍스트 */
--text-secondary: #6b7280   /* 보조 텍스트 */
```

## 📱 반응형 브레이크포인트

- **모바일**: 480px 이하
- **태블릿**: 768px 이하
- **데스크톱**: 768px 이상

## 🚀 설치 및 실행

1. **파일 다운로드**
   ```bash
   git clone [repository-url]
   cd WebPage
   ```

2. **로컬 서버 실행**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   
   # PHP
   php -S localhost:8000
   ```

3. **브라우저에서 확인**
   ```
   http://localhost:8000
   ```

## 🔧 커스터마이징

### 색상 변경
`styles.css` 파일의 `:root` 섹션에서 CSS 변수를 수정하세요:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* ... */
}
```

### 내용 수정
`index.html` 파일에서 텍스트와 이미지를 수정하세요.

### 애니메이션 조정
`script.js` 파일에서 애니메이션 속도와 효과를 조정할 수 있습니다.

## 📊 성능 최적화

- **이미지 최적화**: WebP 포맷 사용 권장
- **폰트 최적화**: Google Fonts preconnect 사용
- **CSS 최적화**: Critical CSS 인라인화
- **JavaScript 최적화**: 이벤트 리스너 스로틀링

## 🔍 SEO 최적화

- 시맨틱 HTML 구조
- 메타 태그 최적화
- Open Graph 태그
- Twitter Cards
- 구조화된 데이터 (Schema.org)

## 📱 PWA 기능

- Service Worker 등록
- 오프라인 지원
- 앱 설치 가능
- 푸시 알림 (구현 예정)

## 🛠️ 브라우저 지원

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📈 분석 도구

Google Analytics 이벤트 추적이 포함되어 있습니다:
- 버튼 클릭 추적
- 전화번호 클릭 추적
- 페이지 스크롤 추적

## 🤝 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 📞 연락처

- **전화번호**: 010-1234-5678
- **운영시간**: 24시간 연중무휴
- **서비스 지역**: 보령 및 전국

---

**보령탑대리운전** - 안전하고 신뢰할 수 있는 대리운전 서비스 🚗✨ 