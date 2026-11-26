# 마지막 교실 · 좀비 아포칼립스 생존 웹게임

신구대학교 게임콘텐츠과 기말 작업 · 2023137046 이준해

- 웹페이지: https://junhae0.github.io/ZombieGame/
- 게임 바로가기: https://junhae0.github.io/ZombieGame/game.html
- 시스템 기획서: https://junhae0.github.io/ZombieGame/system-design.pdf

## 파일 구성

| 파일 | 내용 |
| --- | --- |
| `index.html` | 디오라마와 게임을 묶은 첫 화면 |
| `game.html` | 마지막 교실 웹게임 (HTML 한 파일) |
| `diorama.html` | Treasure Reef 디오라마 |
| `system-design.pdf` | 시스템 기획서 v1.3 |

## 조작

WASD 이동 · Shift 달리기 · C 웅크리기 · E 구조·대화·무전·하루 마치기 · Q 횃불 · R 알람시계 · F 통조림 · Esc 일시정지와 소리 조절 · M 소리 끄기

## 피드백 반영 (11월 18일 피드백 → v1.3)

1. **2일차 이어하기**: 밤 정산이 끝날 때마다 날짜·자원·동료·감염·부품을 자동 저장. 타이틀에 "이어하기 (N일차 아침)" 버튼 추가.
2. **쉘터 E 안내**: 하루를 마칠 수 없을 때 E를 누르면 이유와 남은 시간 표시. 머리 위와 상단 시계에 남은 초 표시. 1일차 아침에 "첫날 꼭 알아야 할 규칙 세 가지" 추가.
3. **밤 결과의 이유**: 밤 정산의 모든 줄에 원인 태그([감염], [밤 습격] 등)와 계산 과정 표시. 인원·식량·바리케이드·사기를 "시작 → 결과 (변화)"로 비교.
4. **1366×768 화면**: 타이틀과 아침 화면을 2단으로 바꿔 제목과 시작 버튼이 스크롤 없이 보이게 수정.

## GitHub Pages

저장소 Settings → Pages에서 Source를 Deploy from a branch, Branch를 main / (root)로 설정. 주소: https://junhae0.github.io/ZombieGame/
