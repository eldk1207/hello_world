# CLAUDE.md

## 프로젝트 개요

**hello_world**는 Node.js 기반의 연습용 웹 서버 프로젝트입니다.

- 런타임: Node.js v22
- 패키지 매니저: npm
- 프레임워크: 없음 (Node.js 내장 `http` 모듈 사용)

## 저장소 구조

```
hello_world/
├── CLAUDE.md          # AI 어시스턴트 가이드 (이 파일)
├── README.md          # 프로젝트 설명
├── package.json       # Node.js 프로젝트 설정 및 의존성
└── index.js           # 메인 엔트리 포인트 (HTTP 서버)
```

## 주요 명령어

```bash
# 서버 실행 (http://localhost:3000)
npm start

# 테스트 (아직 미설정)
npm test
```

## 개발 가이드라인

### 일반 규칙

- 프로젝트가 변경될 때 README.md를 최신 상태로 유지할 것
- 명확하고 설명적인 커밋 메시지를 사용할 것
- 새로운 작업은 기능 브랜치를 생성하여 진행할 것

### 의존성 관리

- 패키지 설치: `npm install <패키지명>`
- 개발 전용 패키지 설치: `npm install -D <패키지명>`
- `package.json` 변경 후에는 반드시 `npm install` 실행할 것
