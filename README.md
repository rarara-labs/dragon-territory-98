# DRAGON TERRITORY '98 — Mobile Lock v5

모바일 플레이 안정화 버전입니다.

## v5 수정
- 게임 페이지를 모바일 viewport에 고정
- maximum-scale / minimum-scale / user-scalable=no 재적용
- 방향키, DRAW, 게임 캔버스에서 더블탭 확대 차단
- pinch/gesture zoom 차단
- orientation 변경 시 viewport 재고정
- 페이지 스크롤/overscroll 억제
- 방향키 민감도 완화
  - 한 번 탭: 한 칸 이동
  - 약 145ms 이상 눌러야 연속 이동 시작
  - 연속 이동 간격을 이전보다 느리게 조정
- 빠른 연타가 브라우저 제스처로 인식되는 현상 추가 방지

## GitHub Pages
기존 저장소의 index.html을 v5 index.html로 교체 후 Commit 하면 됩니다.
