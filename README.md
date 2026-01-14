# ESLint Error Learning Project

이 프로젝트는 Webpack 5와 Vue.js 3 환경에서 발생하는 다양한 ESLint 에러를 학습하고 해결하는 방법을 익히기 위한 프로젝트입니다.

## 주요 기능 (Features)

- **Vue.js 3**: `vue-loader` 및 `@vue/compiler-sfc`를 통한 Vue 3 컴포넌트 지원.
- **Webpack 5**: 개발(Development) 및 배포(Production) 모드 설정.
- **스타일링 (Styling)**:
  - SCSS/SASS 지원 (`sass`, `sass-loader`)
  - PostCSS 및 Autoprefixer 적용
  - CSS 로더 구성 (`vue-style-loader`, `style-loader`, `css-loader`)
- **트랜스파일링 (Transpiling)**: Babel (`@babel/preset-env`)을 사용하여 최신 JavaScript 문법 호환성 확보.
- **린팅 (Linting)**: ESLint 및 Vue 관련 린트 플러그인 설정.
- **에셋 관리**: 이미지 파일(`file-loader`) 및 정적 파일(`copy-webpack-plugin`) 처리.

## 사전 요구사항 (Prerequisites)

- Node.js
- npm

## 설치 (Installation)

프로젝트 의존성 패키지를 설치합니다.

```bash
npm install
```

## 스크립트 (Scripts)

### 개발 서버 실행 (Development)

HMR(Hot Module Replacement)이 활성화된 개발 서버를 실행합니다.

```bash
npm run dev
```

- 호스트: `localhost`
- 포트: `8080`

### 배포용 빌드 (Production Build)

프로덕션 환경을 위해 프로젝트를 빌드합니다. 빌드 결과물은 `dist` 디렉토리에 생성되며, 이전 빌드 내용은 자동으로 삭제됩니다(`clean: true`).

```bash
npm run build
```

## 프로젝트 설정 (Configuration)

- **Entry Point**: `./src/main.js`
- **Output**: `dist/`
- **Alias (경로 별칭)**:
  - `~`: `src/`
  - `assets`: `src/assets/`
