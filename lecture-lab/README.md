# Lecture Lab

강의자료를 입력하면 AI로 객관식 10문제 + 단답형 3문제를 만들고, 즉시 피드백/실전 시험/오답 재시험/개념별 정답률을 제공하는 React 웹앱입니다.

## 실행

```bash
npm install
npm run dev
```

## AI 연결

앱의 `AI 연결 설정`에서 OpenAI 호환 Chat Completions 엔드포인트, 모델 ID, 필요하면 API 키를 입력합니다.

운영 환경에서는 브라우저에 API 키를 넣기보다 서버 프록시를 두는 것을 권장합니다.

## 지원 파일

TXT, MD, CSV, 텍스트형 PDF, DOCX. 최대 20MB, 추출 텍스트 최대 60,000자입니다.
