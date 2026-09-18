# RETRO ARCADE
GitHub Pages용 PC·모바일 레트로 웹게임 모음.

- `/index.html` : 게임 선택 로비
- `/dragon/index.html` : DRAGON TERRITORY '98
- `/raccoon/index.html` : RACCOON TREASURE '90

Raccoon: PC 방향키/WASD + Space, 모바일 방향키 + JUMP.
사운드는 원작 음원을 사용하지 않고 Web Audio API로 만든 오리지널 8-bit풍 BGM/효과음입니다.

## 배포
ZIP을 풀어 저장소 루트에 전체 내용을 업로드하세요. 기존 GitHub Pages 주소를 그대로 사용하며, 루트 주소를 열면 게임 선택 화면이 나옵니다.

## v2 Raccoon update
- 귀여운 픽셀 너구리 캐릭터(마스크 얼굴, 귀, 볼터치, 줄무늬 꼬리)
- 게임 조작 영역의 더블탭 확대 방지 강화 (START/MENU 클릭은 차단하지 않음)
- 층간 높이 90px → 80px 수준으로 축소하고 점프력 강화
- 사다리 없는 구간에서도 인접 위층 점프 이동 가능하도록 스테이지 재배치

## v3 Raccoon fix
- DOWN 키/버튼으로 사다리 내려가기 판정 수정
- 발판 위에서 DOWN 입력 시 사다리로 진입 가능
- 사다리 중심 자동 보정으로 모바일 조작 안정화
- 모든 보물 수집 후 맨 위 EXIT가 초록색으로 열림
- EXIT 진입 시 STAGE CLEAR 화면 → 다음 스테이지로 전환
- 클리어 보너스 및 다음 STAGE HUD 갱신
