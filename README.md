# Webpack Template Basic

Webpack 5를 기반으로 구성된 기본적인 프론트엔드 개발 템플릿입니다. Babel, SCSS, PostCSS 등이 미리 설정되어 있어 빠르게 프로젝트를 시작할 수 있습니다.

## 주요 기능

- **Webpack 5**: 최신 모듈 번들러 설정
- **Babel**: ES6+ 문법을 호환 가능한 JavaScript로 변환 (`@babel/preset-env`, `@babel/plugin-transform-runtime`)
- **SCSS/SASS**: CSS 전처리기 지원 (`sass`, `sass-loader`)
- **PostCSS**: CSS 호환성 자동화 (`autoprefixer`)
- **HTML**: HTML 파일 자동 생성 및 관리 (`html-webpack-plugin`)
- **Static Assets**: 정적 파일 복사 (`copy-webpack-plugin`)

## 시작하기

### 설치

프로젝트 의존성을 설치합니다.

```bash
npm install
```

### 개발 서버 실행

개발 모드로 로컬 서버를 실행합니다. (Hot Module Replacement 지원)

```bash
npm run dev
```

### 빌드

프로덕션 배포를 위해 파일을 번들링합니다.

```bash
npm run build
```
