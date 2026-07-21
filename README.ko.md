🌐 [English](README.md) | 한국어

# 안녕하세요, 이호원입니다

온라인에서는 주로 **airtaxi**를 쓰고, 가끔 kck4156도 씁니다. 예전에는 hoyo321로 활동했습니다.

서울에서 개발자로 일하고 있습니다. 선문대학교 컴퓨터공학과에서 공학박사 학위를 받았습니다.

박사 논문 제목은 '멀티모달 대규모 언어 모델과 검색 증강 생성을 결합한 실내 화재 대응 조언 시스템 개발에 관한 연구'였습니다.

주로 .NET과 C#으로 개발하고 있고, 특히 윈도우 개발(WinUI)과 Uno Platform 기반 크로스플랫폼 앱을 만드는 걸 좋아합니다. 게임이나 서버 쪽 개발 경험도 있습니다.

---

## 주요 프로젝트

### 윈도우 앱 & 유틸리티

- **[PinStats](https://github.com/airtaxi/PinStats)** - 윈도우 10/11에서 실시간 PC 자원 사용량을 보여주는 앱입니다. Windows 11 작업 표시줄에 사용량 위젯을 직접 고정할 수 있는 게 가장 큰 차별점으로, 다른 시스템 모니터에서는 거의 찾아볼 수 없는 기능입니다.

- **[Deskband11Lib](https://github.com/airtaxi/Deskband11Lib)** - 윈도우 11 작업 표시줄에 위젯을 띄울 수 있는 라이브러리입니다. 비슷한 건 있지만 쓰기 좋게 라이브러리로 정리된 건 이게 거의 유일한 강력한 수단입니다.

- **[BarPlay](https://github.com/airtaxi/BarPlay)** - 윈도우 11 작업 표시줄에서 미디어 재생 정보와 컨트롤을 쓸 수 있는 가벼운 위젯입니다. 원래 Deskband11Lib의 PoC로 시작했는데, 주변 사람들 반응이 좋아서 실제 앱으로 만들었습니다.

- **[AT-Installer](https://github.com/airtaxi/AT-Installer)** - WinUI 3로 만든 가벼운 윈도우 설치 프레임워크입니다. 최근에 추가된 MSIX를 EXE로 패키징하는 기능이 차별점인데, PowerShell이나 개발자 모드 없이 MSIX를 더블클릭 설치 파일로 만들어 줍니다.

- **[DeskBorder](https://github.com/airtaxi/DeskBorder)** - 가상 데스크톱을 쓰는 사람들을 위한 윈도우 유틸리티입니다. 화면 가장자리에 마우스를 대면 데스크톱이 전환되고, 그 외에도 여러 기능이 있습니다. 아이디어가 좋다고 생각합니다.

- **[Cli-Account-Switcher](https://github.com/airtaxi/Cli-Account-Switcher)** - AI 서비스 제공자(Codex, Claude Code, Z.ai, Ollama Cloud, OpenCode Go)의 인증 계정을 관리하는 윈도우 앱입니다. 작업 표시줄에 항상 떠 있는 사용량 위젯이 꽤나 킥입니다.

- **[LidGuard](https://github.com/airtaxi/LidGuard)** - 노트북 덮개를 닫아도 로컬 AI 코딩 에이전트가 계속 깨어 있도록 해줍니다. 비슷한 다른 레포가 아예 없습니다.

- **[AT-Image-Converter](https://github.com/airtaxi/AT-Image-Converter)** - WinUI 3와 Magick.NET으로 만든 일괄 이미지 변환기입니다. 깔끔한 UI에 지원 포맷과 옵션이 풍부한 게 특징입니다.

- **[ClosedAwake](https://github.com/airtaxi/ClosedAwake)** - 노트북 덮개를 닫아도 깨어 있게 해주는 윈도우 트레이 앱입니다. 절전 방지 도구는 많지만 노트북 덮개 문제를 해결하는 건 거의 없습니다. 이 앱은 그게 가능하고, UI도 깔끔합니다.

- **[KoreanNumberParser](https://github.com/airtaxi/KoreanNumberParser)** - `10억4천3백만이십일` 같은 한국어 숫자 문자열을 int/long으로 파싱하고, 다시 한국어 숫자 문자열로 변환해 주는 .NET 라이브러리입니다. 한자어 수사와 아라비아 숫자가 섞인 표현까지 처리하는 게 차별점입니다.

- **[YellowInside](https://github.com/airtaxi/YellowInside)** - 카카오톡 메신저에서 디시콘, 아카콘, 인벤 스티커를 쓸 수 있게 해주는 윈도우 앱입니다.

- **[CrispShot](https://github.com/airtaxi/CrispShot)** - 윈도우 기본 `Alt + Print Screen`이 창 캡처할 때 생기는 작은 배경 테두리를 없애주는 가벼운 트레이 유틸리티입니다. 부드러운 그림자 효과도 넣을 수 있어서 macOS의 창 스크린샷 같은 느낌을 낼 수 있습니다.

- **[AutoClipboardSaver](https://github.com/airtaxi/AutoClipboardSaver)** - 이미지를 복사할 때마다 클립보드 이미지를 지정한 폴더에 자동으로 저장해 주는 시스템 트레이 앱입니다.

- **[ScreenBrightnessByBattery](https://github.com/airtaxi/ScreenBrightnessByBattery)** - 배터리 전원인지 AC 전원인지에 따라 화면 밝기를 자동으로 조절해 주는 가벼운 앱입니다. 외부 모니터가 연결되어 있을 때 절전을 막아주는 기능도 있습니다.

- **[NamuWikiViewer](https://github.com/airtaxi/NamuWikiViewer)** - WinUI 3와 .NET 10으로 만든 비공식 나무위키 뷰어 앱입니다. 광고 차단, 방문 기록, 깔끔한 열람 UI를 제공합니다.

---

### MCP 서버

터미널에서 AI 코딩 에이전트가 더 많은 일을 할 수 있도록 MCP(Model Context Protocol) 서버도 만들고 있습니다.

- **[FluentIconsMcp](https://github.com/airtaxi/FluentIconsMcp)** - 에이전트에서 윈도우 Fluent 아이콘을 검색할 수 있습니다. Fluent 아이콘 메타데이터를 stdio MCP 서버로 노출하는 .NET 글로벌 도구입니다. WinUI 앱을 개발할 때 FontIcon에 AI 에이전트가 적절한 아이콘을 사용하게 하는 데 유용합니다.

- **[XamlStylerMcp](https://github.com/airtaxi/XamlStylerMcp)** - 에이전트에서 XAML 포맷팅을 할 수 있습니다. XamlStyler를 감싸서 XAML 문자열, 파일, 디렉토리 단위 포맷팅을 지원합니다.

- **[GithubRepoStructureMcp](https://github.com/airtaxi/GithubRepoStructureMcp)** - 에이전트에서 GitHub 저장소 디렉토리 구조를 트리 형태로 가져올 수 있습니다. PAT를 쓰면 비공개 저장소도 됩니다. 에이전트가 레포지토리 탐색을 훨씬 빠르게 할 수 있게 도와줍니다.

- **[PhotoshopMcpServer](https://github.com/airtaxi/PhotoshopMcpServer)** - AI 어시스턴트가 윈도우 COM 자동화로 Adobe Photoshop을 제어할 수 있게 해주는 MCP 서버입니다.

---

## 통계

<img src="https://github-stats-extended.vercel.app/api?username=airtaxi&show_icons=true&theme=default" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=airtaxi&theme=default" alt="GitHub Streak" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=airtaxi&layout=compact&theme=default" alt="Top Languages" />

---

## 방명록

가볍게 인사 남겨주세요. 연락 기다리고 있습니다.

<a href="https://github.com/airtaxi/airtaxi/issues">
  <img src="https://img.shields.io/badge/메시지%20남기기-여기%20클릭-blue" alt="Guestbook" />
</a>

[프로필 저장소](https://github.com/airtaxi/airtaxi/issues)에 이슈를 열고 댓글을 남겨주세요. 무엇이든 환영합니다.