# 📅 2026년 1월 4일 To-Do

---

### FE (프론트엔드)
- [ ] 로컬 스토리지 암호화 적용
  - `crypto-js` 등 라이브러리 활용
  - `useCrypto.ts` 컴포저블 생성
- [ ] 전역 인증 상태 관리 개선 (임시)
  - `useAuth.ts` 컴포저블에서 앱/플랫폼 ID 분리
  - 앱 ID 기준으로 데이터 조회하도록 로직 변경
- [ ] (GEMINI 제안) 스크래핑/조회 시 로딩 및 에러 상태 UI 개선
  - 로딩 스피너 및 에러 메시지 컴포넌트 추가

---

### BE (백엔드)
- [ ] `ApplyHistory` 스키마에 `appUserId` 필드 추가
- [ ] 스크래핑 시 `appUserId`를 함께 저장하도록 로직 수정
- [ ] `GET /scraper/history/:appUserId` API 구현
- [ ] 잡코리아 팝업 자동 제거 로직 강화
  - `page.evaluate()`를 사용한 DOM 직접 제어
- [v] 스크래핑 데이터 중복 저장 방지
  - ~~`deleteMany` 후 `insertMany` 방식으로 구현 완료~~

---