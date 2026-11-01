# 친구 관리 서비스

Fetch API와 MockAPI를 활용한 CRUD 웹 서비스입니다.

---

## Deployment

| 항목 | URL |
|------|-----|
| GitHub | https://github.com/krorv/2026OSS_week9  |
| Vercel | https://2026ossweek9-neon.vercel.app/ |
| MockAPI Endpoint | https://6adea6de4e88f1bba4a53a3b.mockapi.io/Friends |

---

## Service

- **주제**: 친구 관리
- **Fields**: `id`, `name`, `relation`, `phone`, `email`, `birthday`
- **CRUD 기능**
  - GET: 페이지 로드 시 전체 친구 목록 조회 및 화면 출력
  - POST: 폼 입력 후 서버에 친구 추가
  - PATCH: 기존 데이터 불러와 수정 후 서버에 반영
  - DELETE: 확인(confirm) 후 서버에서 삭제

---

## Key Learning

1. **fetch() / async / await**: 비동기 방식으로 서버에 HTTP 요청을 보내고, await로 응답을 기다린 뒤 처리하는 방법을 익혔다.
2. **response.ok / response.json()**: 요청 성공 여부를 `response.ok`로 확인하고, `response.json()`으로 JSON 데이터를 JavaScript 객체로 변환하는 과정을 이해했다.
3. **REST API 구조**: GET / POST / PATCH / DELETE 각 메서드의 역할과 MockAPI를 통해 실제 서버처럼 데이터를 주고받는 흐름을 배웠다.

---

## AI / Search Usage

| 항목 | 내용 |
|------|------|
| 사용 도구 | 제미나이, 클로드 |
| 사용 목적 | 코드 구조 검토, 버그 확인, README 작성 보조 |
| 참고·반영한 기능 | 중복 loadFriends() 호출 제거 |
| 직접 수정한 내용 | fetch CRUD 로직 전체, validateForm, searchFriends, renderFriends, CSS 스타일 |
| 배운 점 | AI를 활용해 코드 리뷰 시 놓치기 쉬운 중복 호출 등의 버그를 발견할 수 있다 |
| 본인 추정 AI 코드 기여율 | 약 40% |

---

