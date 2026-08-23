# HANDOFF

세션 사이를 잇는 인계 노트입니다.
**작업을 시작하면 여기를 먼저 읽고, 마칠 때 여기를 갱신하고 커밋합니다.**
장소가 바뀌어도, 도구가 바뀌어도(채팅 ↔ Claude Code), 모바일에서 이어받아도 이 파일 하나면 됩니다.

최종 갱신: 2026-08-23 · 갱신자: Claude Code

---

## 지금 상태

저장소를 막 만들었습니다. 공개 페이지는 `index.html` 하나뿐이고, `docs/` 문서 체계는 아직 시작 전입니다.
CLAUDE.md가 그려둔 구조(공개 페이지 3종, `docs/` 폴더 골격)는 아직 실제로 만들어지지 않았습니다 — 이 문서(CLAUDE.md)와 계획 문서 정도만 있는 상태입니다.

**있는 것**

- `index.html` — 공개 페이지 (개요·편성). GitHub Pages로 배포 완료, 정상 접속 확인됨
- `README.md` — 프로젝트 전체 안내 (단, `<계정명>` `<저장소명>` 플레이스홀더 미교체)
- `DOCUMENT-GUIDE.md` — 문서 규칙 전문. **저장소 루트**에 있음 (CLAUDE.md는 `docs/DOCUMENT-GUIDE.md`를 전제하므로 위치가 다름)
- `CLAUDE.md`, `HANDOFF.md` — 이번에 작성됨. **아직 git에 커밋되지 않은 상태(untracked)**였음 — 이번 세션에서 커밋

**없는 것**

- `roles.html`, `docs.html`, `style.css` — CLAUDE.md 구조에 있지만 실제로는 아직 없음 (공개 페이지는 index.html뿐)
- `docs/` 폴더 자체가 없음 (00-decisions ~ 06-team 골격 미생성)
- 팀원 확정, 역할 배정

**바뀐 것 (이번 세션)**

- GitHub Pages 설정 완료 → `https://hyun02063185-ax-beginner.github.io/Cody-Stat/` 에서 index.html 정상 노출 확인

---

## 다음에 할 일

우선순위 순입니다. 하나 끝낼 때마다 이 목록을 갱신하세요.

- [x] GitHub Pages 설정 (Settings → Pages → main / root) — 배포 확인 완료
- [ ] `README.md`의 `<계정명>` `<저장소명>` 두 곳을 실제 값(`hyun02063185-AX-beginner` / `Cody-Stat`)으로 교체
- [ ] `docs/` 폴더 생성하고 `DOCUMENT-GUIDE.md`를 루트에서 `docs/DOCUMENT-GUIDE.md`로 이동 (CLAUDE.md 구조와 맞추기)
- [ ] `roles.html`, `docs.html`, `style.css` 작성 — 공개 페이지 3종 구조를 실제로 만들기
- [ ] 세 페이지 만든 뒤 Pages 배포 후 서로 링크가 잘 도는지 확인
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
