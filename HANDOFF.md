# HANDOFF

세션 사이를 잇는 인계 노트입니다.
**작업을 시작하면 여기를 먼저 읽고, 마칠 때 여기를 갱신하고 커밋합니다.**
장소가 바뀌어도, 도구가 바뀌어도(채팅 ↔ Claude Code), 모바일에서 이어받아도 이 파일 하나면 됩니다.

최종 갱신: 2026-08-23 · 갱신자: Claude Code

---

## 지금 상태

공개 페이지 3종이 갖춰졌습니다. `docs/` 문서 체계는 아직 시작 전입니다.

**있는 것**

- `index.html` `roles.html` `docs.html` — 공개 페이지 3종. 네비게이션 상호 연결 확인됨
- `style.css` — 세 페이지 공용 스타일. 인라인 스타일이 여기로 분리됨
- `README.md` — 프로젝트 전체 안내 (단, `<계정명>` `<저장소명>` 플레이스홀더 3곳 미교체)
- `CLAUDE.md`, `HANDOFF.md` — 작업 규칙과 인계 노트
- GitHub Pages 배포 — `https://hyun02063185-ax-beginner.github.io/Cody-Stat/` 정상 접속 확인

**없는 것 / 어긋난 것**

- `docs/` 폴더 자체가 없음 (00-decisions ~ 06-team 골격 미생성)
- `DOCUMENT-GUIDE.md`가 **저장소 루트**에 있음. CLAUDE.md와 `docs.html` 본문은 `docs/DOCUMENT-GUIDE.md`를 가리키므로 링크가 어긋난 상태
- 팀원 확정, 역할 배정

**바뀐 것 (이번 세션)**

- GitHub Pages 설정 및 배포 확인
- `roles.html` `docs.html` `style.css` 추가, `index.html`을 공용 스타일 기준으로 정리
- `files.zip`(작업물 전달용 압축본)은 저장소에 넣지 않고 `.gitignore`에 추가

---

## 다음에 할 일

우선순위 순입니다. 하나 끝낼 때마다 이 목록을 갱신하세요.

- [x] GitHub Pages 설정 (Settings → Pages → main / root) — 배포 확인 완료
- [x] `roles.html`, `docs.html`, `style.css` 작성 — 공개 페이지 3종 구조 완성
- [ ] Pages 재배포 후 세 페이지 링크가 실제 URL에서 서로 잘 도는지 확인
- [ ] `README.md`의 `<계정명>` `<저장소명>` 3곳을 실제 값(`hyun02063185-AX-beginner` / `Cody-Stat`)으로 교체
- [ ] `docs/` 폴더 생성하고 `DOCUMENT-GUIDE.md`를 루트에서 `docs/DOCUMENT-GUIDE.md`로 이동 — `docs.html`이 이미 그 경로를 안내하고 있음
- [ ] `docs/00-decisions/decision-log.md` 생성 (빈 표 + 헤더)
- [ ] `docs/01-handover/checklist.md` 생성 — 9월 3일에 들고 갈 인수인계 체크리스트
- [ ] `docs/01-handover/qna.md` 생성 — 원작자에게 물어볼 질문 목록
- [ ] `docs/06-team/roster.md` 생성 — 역할 배정표 (발대식 후 채움)
- [ ] 노션 문서와 공개 페이지 내용 동기화 여부 결정

---

## 열려 있는 질문

아직 답이 안 난 것들입니다. 결정되면 `decision-log.md`로 옮기고 여기서 지웁니다.

- 팀원 의견 취합 결과 (Q1~Q6, 마감 8/31) — 반영 후 편성안 v0.2로 갱신 필요
- 노션과 GitHub 중 어느 쪽을 팀원 대상 정본으로 할지
- 유료 전환 시 비용 부담 주체
- QA·개인정보 담당을 누가 겸임할지

---

## 최근 작업 기록

새 항목을 **위에** 추가합니다. 오래된 것은 10줄이 넘으면 지웁니다.

| 날짜 | 도구 | 한 일 |
| --- | --- | --- |
| 2026-08-23 | Claude Code | 공개 페이지 3종(roles·docs·style.css) 추가, index.html 정리, HANDOFF 재갱신 |
| 2026-08-23 | Claude Code | 실제 저장소 상태 점검 후 HANDOFF 갱신 — 공개 페이지는 index.html 하나뿐, docs/ 폴더 미생성임을 반영 |
| 2026-08-23 | Claude Code | GitHub Pages 배포 및 접속 확인, CLAUDE.md·HANDOFF.md 커밋 |
| 2026-08-23 | claude.ai | 저장소 골격 생성 — index.html, README, 문서 가이드, CLAUDE.md, HANDOFF.md |

---

## 이 파일 쓰는 법

- **「지금 상태」** — 스냅샷. 새로 온 사람이 이것만 읽어도 현황을 알 수 있게
- **「다음에 할 일」** — 체크박스. 끝내면 지우지 말고 `[x]`로 바꿨다가, 다음 갱신 때 삭제
- **「열려 있는 질문」** — 결정 대기 중인 것. 답이 나오면 `decision-log.md`로 이동
- **「최근 작업 기록」** — 무엇을 했는지 한 줄. 왜 했는지는 `decision-log.md`에

길게 쓰지 마세요. 이 파일이 길어지면 아무도 안 읽습니다. **한 화면을 넘기지 않게** 유지합니다.
