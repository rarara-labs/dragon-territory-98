# RETRO ARCADE — v5 Bubble Shooter

기존 게임을 유지하면서 `bubble/` 게임만 버블 슈터 퍼즐로 교체했습니다.

## 게임
- `index.html` : 게임 선택 로비
- `dragon/index.html` : DRAGON TERRITORY '98
- `raccoon/index.html` : RACCOON TREASURE '90
- `bubble/index.html` : BUBBLE BLOOM (같은 색 3개 이상 맞추는 퍼즐)

## Bubble Bloom 조작
- 모바일: 게임 화면을 누르고 끌어 조준한 뒤 손가락을 떼면 발사
- PC: 마우스로 조준하고 클릭, 좌우 방향키로 미세 조준 후 Enter 발사
- `구슬 바꾸기`: 현재 구슬과 다음 구슬을 교체 (PC Space)
- 같은 색 3개 이상 연결 시 제거, 천장과 연결이 끊어진 구슬도 제거
- 모두 제거하면 다음 스테이지로 진행
- 발사 횟수를 다 쓰거나 구슬이 아래까지 내려오면 다시 도전
- 첫 스테이지는 3색부터 시작하며 점차 색상/행이 증가

## 사운드 및 저작권
원작 음악·그래픽·캐릭터를 복제하지 않고 HTML5 Canvas와 Web Audio API로 자체 제작했습니다.

## 배포
ZIP을 풀어 GitHub Pages 저장소 최상위에 전체 파일/폴더를 업로드합니다. 기존 GitHub Pages 주소 유지.

## 버전 기록
- v5: 기존 버블 플랫폼 액션을 초등 저학년도 즐길 수 있는 파스텔 버블 슈터 퍼즐로 전면 교체
