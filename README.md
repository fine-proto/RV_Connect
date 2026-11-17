# RV Connect · Web Demo

RV Connect 앱(Android)을 실제 블랙박스 없이 웹에서 시연하는 프로토타입입니다.
파인뷰 CLOUD & Wi-Fi 앱에서 클라우드 기능을 제거하고 RoadView 스킨(포인트 컬러 #000F9E)을 적용한 버전입니다.

- 웹 보기: https://fine-proto.github.io/RV_Connect/ (GitHub Pages 활성화 시)
- 기본 언어: 영어 (한국어로 바로 열기: `?lang=ko`)
- 시연 모델: **Stealth** (NON-LCD · REC/PWR 페어링) / **Alpha** (NON-LCD · REC/MIC 페어링)
- 하단 탭: 홈 / 보관함 / 더보기 (클라우드 탭 없음)
- 왼쪽 DEMO 패널(모바일은 오른쪽 아래 DEMO 버튼)에서 블랙박스 버튼 누르기·연결 취소, 주행/주차 전환, Wi-Fi 끄기, 연결 끊김, 새 펌웨어 알림을 실행할 수 있습니다.

## 파일
- `index.html` — 단일 파일 데모 (이미지 내장)
- `video/front.mp4`, `video/rear.mp4` — 전·후방 샘플 영상 (index.html과 같은 위치에 있어야 재생됨). 영상 상단 OSD의 모델명은 화면에서 마스킹 후 `RoadView {모델명}`으로 표시합니다.
