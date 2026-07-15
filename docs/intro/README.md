# STF 소개 페이지 (docs/intro)

`index.html` — DeviceFarmer STF의 인터랙티브 소개(단일 파일, 외부 의존성 없음).
디바이스 선반·원격 제어 콘솔·아키텍처 맵·퀵스타트를 담았다. 브라우저로 바로 열면 된다.

## 관련 프로젝트

이 STF 포크는 **BlueStacks 팜을 브라우저에서 보고/수동 제어**하는 용도다.
같은 팜에 대해 **배치 업로드를 자동화**하는 별도 툴이 있다:

- **yt-studio-uploader** (로컬 `~/dev/yt-uploader`) — BlueStacks 인스턴스에 영상을 push하고
  YouTube Studio 앱으로 병렬 업로드하는 uiautomator2 하네스.

둘은 별도 저장소이며 ADB(`127.0.0.1:<port>`)로 같은 기기에 붙는다.
STF = 관제/수동, uploader = 자동 배치. 함께 쓰는 하나의 워크플로우다.
