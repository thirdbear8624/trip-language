짱세투어 생존여행언어 - 앱 설치 가이드

[방법 A] GitHub Pages로 올려서 폰에 앱처럼 설치 (추천, 무료)
1. GitHub에서 새 저장소(Repository)를 만든다. 예: jjangse-tour
2. 이 폴더의 파일 전부(index.html, manifest.json, sw.js, 아이콘 3개)를 저장소 맨 위(루트)에 올린다.
3. 저장소 Settings > Pages > Branch를 main(/root)로 선택하고 Save.
4. 1~2분 뒤 https://아이디.github.io/jjangse-tour/ 주소가 생긴다.
5. 폰으로 그 주소를 열고
   - 아이폰: Safari 공유 버튼 > 홈 화면에 추가
   - 안드로이드: Chrome 메뉴 > 앱 설치 (또는 홈 화면에 추가)
6. 한 번 열어두면 인터넷 없이도 열린다. 해외 데이터 없이 쓰기 좋다.

[주의]
- 앱 이름은 홈 화면에서 "짱세투어"로 보인다.
- 내용을 고치면 sw.js 맨 위의 "jjangse-v1"을 v2로 바꿔서 올려야 폰에 새 버전이 반영된다.
- 음성(스피커 버튼)은 폰에 해당 언어 음성이 설치되어 있어야 나온다.
- 스토어(앱스토어/플레이스토어) 정식 앱이 필요하면 이 파일을 Capacitor로 감싸면 된다. 그때 다시 요청하면 된다.
