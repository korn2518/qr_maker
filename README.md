# 이미지 합성 QR 메이커 (설치형 웹앱)

웹 주소·지도 주소·텍스트·Wi‑Fi를 내 PNG 이미지와 합성한 디자인 QR 코드로 만드는 앱입니다.
한 번 열면 인터넷 없이도 작동하고, 휴대폰·PC에 앱처럼 설치할 수 있습니다.

## GitHub Pages로 배포하기 (5분)
1. GitHub에서 **New repository** → 이름 예: `qr-maker` → **Public** → Create.
2. **Add file → Upload files**에서 이 폴더 안의 파일을 **폴더 구조 그대로** 모두 끌어다 놓고 Commit.
   (`index.html`, `manifest.webmanifest`, `sw.js`, `favicon.png`, `icons/` 폴더)
3. **Settings → Pages → Branch: main / (root) → Save**.
4. 1~2분 뒤 `https://<내아이디>.github.io/qr-maker/` 주소로 접속.

## 앱으로 설치하기
- **PC 크롬·엣지**: 주소창 오른쪽 설치 아이콘 또는 화면 위 「📲 앱 설치」 버튼
- **안드로이드 크롬**: 「📲 앱 설치」 버튼 또는 메뉴(⋮) → 앱 설치
- **아이폰·아이패드 Safari**: 공유 버튼 → 「홈 화면에 추가」

## 업데이트할 때
`index.html`을 새 파일로 바꿔 올리면 됩니다. 이미 설치한 기기에서 바로 반영되지 않으면
`sw.js` 맨 위의 `qr-maker-v1`을 `qr-maker-v2`처럼 숫자를 올려 함께 올려 주세요.

## 참고
- 반드시 https 주소(GitHub Pages 등)에서 열어야 설치·오프라인 기능이 켜집니다. 파일을 더블클릭해 열면 일반 웹페이지로만 작동합니다.
- 휴대폰에서 「PNG로 저장」을 누르면 공유 창이 열립니다 → 「이미지 저장」을 고르면 사진첩에 저장됩니다.
