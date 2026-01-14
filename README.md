# Parcel Template Basic

Parcel Bundler를 기반으로 한 기본적인 웹 개발 템플릿입니다. 별도의 복잡한 설정 없이 Sass, PostCSS, Babel 등 최신 프론트엔드 개발 환경을 바로 사용할 수 있도록 구성되어 있습니다.

## ✨ 주요 기능 (Features)

- **Bundler**: [Parcel Bundler](https://github.com/parcel-bundler/parcel) (v1)을 사용하여 설정 없는(Zero configuration) 빌드 환경 제공
- **Styles**:
  - [Sass](https://sass-lang.com/) (`dart-sass`) 지원
  - PostCSS 및 Autoprefixer를 통한 크로스 브라우징 호환성 확보
- **JavaScript**: Babel을 사용하여 최신 ES6+ 문법 지원 (`@babel/preset-env`)
- **Static Files**: `static` 폴더 내의 정적 파일들을 빌드 결과물로 자동 복사 (`parcel-plugin-static-files-copy`)

## 🛠 사전 요구사항 (Prerequisites)

이 프로젝트를 실행하려면 Node.js가 설치되어 있어야 합니다.

## 🚀 시작하기 (Getting Started)

### 1. 설치 (Installation)

프로젝트의 의존성 패키지를 설치합니다.

```bash
npm install
```

### 2. 개발 서버 실행 (Development)

로컬 개발 서버를 실행합니다. 파일 변경 시 자동으로 브라우저가 새로고침됩니다 (HMR).

```bash
npm run dev
```

- 실행 후 `http://localhost:1234`에서 확인할 수 있습니다.

### 3. 빌드 (Build)

배포를 위한 프로덕션 빌드를 생성합니다. 결과물은 `dist` 폴더에 생성됩니다.

```bash
npm run build
```

## 📂 프로젝트 구조 (Project Structure)

- **index.html**: 진입점(Entry point) 파일
- **static/**: 이미지, 폰트 등 정적 파일을 보관하는 폴더 (빌드 시 자동으로 복사됨)
- **package.json**: 프로젝트 설정 및 의존성 관리
