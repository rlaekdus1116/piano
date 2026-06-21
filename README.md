# 🎀 코드 트레이너 (CP88)

야마하 CP88(또는 아무 USB MIDI 키보드)을 브라우저에 연결해서 피아노 코드와 반주를 배우는 웹앱입니다. 핑크 애니풍 디자인, 태블릿 터치 지원.

## 기능
- 🎧 **실시간 인식** — 친 음을 읽어 무슨 코드인지 바로 표시 (왼손/오른손 가이드 포함)
- 🌸 **코드 따라치기** — "이 코드를 눌러보세요" 예시 건반 + 손가락 번호를 보고 그대로 연습, 맞으면 딩동댕
- 📖 **코드 사전** — 25종 코드 × 12키, 건반 위치·손가락·소리 듣기
- 🎵 **반주 연습** — 4가지 패턴(블록/발라드/아르페지오/알베르티) + 코드 악보 + 메트로놈 박자 채점
  - 🎤 Ed Sheeran 곡 5개 내장: Thinking Out Loud, Photograph, Supermarket Flowers, Perfect, Castle on the Hill
- ✋ **양손 반주 가이드** — 왼손/오른손 역할, 손가락 번호 그림, 패턴별 단계 설명

## 쓰는 법
1. CP88을 USB 케이블로 컴퓨터/태블릿에 연결
2. 크롬·엣지(데스크톱) 또는 사파리(아이패드)로 페이지 열기
3. 상단 **CP88 연결** 버튼 → 권한 허용
4. 화면 건반은 손가락으로 터치해도 소리가 납니다

## GitHub Pages로 배포하기 (무료, 5분)
1. GitHub에 로그인 → 우측 상단 **+** → **New repository**
2. 이름 예: `piano-chord-trainer`, **Public** 선택 → **Create repository**
3. **uploading an existing file** 클릭 → 이 폴더의 `index.html`을 끌어다 올리고 **Commit changes**
4. 저장소 상단 **Settings** → 왼쪽 **Pages**
5. **Source**에서 **Deploy from a branch** → Branch: **main** / 폴더 **/(root)** → **Save**
6. 1~2분 뒤 `https://<내아이디>.github.io/piano-chord-trainer/` 주소가 생기면 끝!

> 파일 이름이 반드시 **`index.html`**여야 자동으로 열립니다.

## 브라우저 호환 (Web MIDI)
- ✅ 크롬, 엣지 (데스크톱)
- ✅ 사파리 (iPadOS 14.5+에서 Web MIDI 지원)
- ⚠️ 일부 브라우저는 MIDI 미지원 — 이 경우 화면 건반 터치로만 사용 가능

소리는 보안 정책상 첫 사용자 동작(버튼 클릭·건반 터치) 이후에 활성화됩니다.
