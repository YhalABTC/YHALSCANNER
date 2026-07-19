# yhal 트레이딩 스캐너 — GitHub Pages 배포

## 파일 구성
- `index.html` — 런처 (세 앱 입구)
- `rsi_candle_scanner_mobile.html` — 모바일 스캐너
- `rsi_candle_scanner.html` — PC 스캐너
- `xaut_dashboard.html` — GOLD DESK
- `manifest-*.json` — PWA 설정 (홈 화면 앱)
- `icon-*.png` — 앱 아이콘 (동그라미 Y)

## 배포 방법 (5분)

### 1. GitHub 리포 생성
1. github.com 로그인 → 우측 상단 **+** → **New repository**
2. 이름: 예 `scanner` (또는 아무거나)
3. **Public** 선택 → **Create repository**

### 2. 파일 업로드
1. 새 리포 화면에서 **uploading an existing file** 클릭
2. 이 폴더의 **모든 파일**을 드래그앤드롭
3. **Commit changes**

### 3. Pages 켜기
1. 리포 → **Settings** → 왼쪽 **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)** → **Save**
4. 1~2분 후 상단에 주소 나옴: `https://<아이디>.github.io/scanner/`

### 4. 뿌리기
- 링크 하나만 보내면 됨: `https://<아이디>.github.io/scanner/`
- 각자 폰에서 열고 원하는 앱 선택 → 브라우저 메뉴 → **홈 화면에 추가**

## 홈 화면 추가 방법
- **아이폰(사파리)**: 공유 버튼 ⬆️ → "홈 화면에 추가"
- **안드로이드(크롬)**: 메뉴 ⋮ → "홈 화면에 추가" 또는 "앱 설치"

## 주의
- 바이낸스 API는 한국에서 VPN 필요 (각자 폰에서)
- 즐겨찾기·프리셋은 각자 기기에만 저장됨 (기기 간 공유 안 됨)
- 업데이트 시: 같은 파일 다시 업로드 → 각자 강력 새로고침
