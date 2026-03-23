[🇰🇷 한국어 (Korean)](#korean) | [🇺🇸 English](#english)

<a name="korean"></a>
# 🛡️ 디아블로 2: 레저렉션 공역 & 우버디아 트래커 (D2R Tracker)

디아블로 2: 레저렉션 플레이 중 **다음 공역(Terror Zone)** 정보와 **우버디아(Diablo Clone)** 의 각 서버별 진행 상황을 게임 화면 위에 실시간으로 표시해 주는 투명 오버레이 프로그램입니다.

---

## ☕ 후원하기 (Support)
이 프로그램이 마음에 드셨다면, 개발자가 더 좋은 기능을 만들 수 있도록 커피 한 잔의 여유를 선물해 주세요! 

* [👉 카카오페이로 커피 한 잔 후원하기 (모바일 환경에서 링크 클릭)](https://qr.kakaopay.com/FTeinPf5n9c405794)
> PC 환경이신 경우, 아래의 QR 코드를 스마트폰 기본 카메라나 카카오톡 스캔 기능으로 찍어주세요!

<img src="kakaopay.JPG" width="250" alt="카카오페이 후원 QR 코드">

---

## 📸 스크린샷 (Screenshots)

### 1. 다음 공역 및 진행률 표시
![다음 공역과 진행률 표시 화면](right-top.png)
> 화면 우측 상단에 다음 시간대의 공역 정보와 갱신까지 남은 시간을 표시합니다. (설정에 따라 현재 공역, 진행률 바, 반투명 배경 패널을 켜고 끌 수 있습니다.)

### 2. 우버디아(Diablo Clone) 진행도 표시
![우버디아 진행율 서버별 표시](right-bottom.png)
> 화면 우측 하단에 아시아, 유럽, 아메리카 서버의 현재 우버디아 진행도를 6단계 블록(`■■■□□□`)으로 직관적으로 표시합니다.

---

## ✨ 주요 기능

* **실시간 공역 알림:** 매시 정각 및 30분마다 업데이트되는 공역 정보를 표시합니다. (ACT 정보 포함)
* **🌐 다국어 지원 (한국어/영어):** 한국어와 영어를 모두 완벽하게 지원하며, 환경설정 창에서 언제든지 자유롭게 언어를 변경할 수 있습니다.
* **🔔 즐겨찾기 맞춤 알림 (New!):** 원하는 공역을 즐겨찾기로 등록하면 해당 공역 발견 시, 그리고 시작 5분 전에 **부드러운 텍스트 깜빡임**과 **소리(띵동)** 로 알림을 줍니다. (동일한 지역 명칭은 하나로 깔끔하게 통합 표시되며, 즐겨찾기 목록은 `favorite_tz.json` 파일로 저장되어 유저 간 공유가 가능합니다.)
* **🎨 사용자 맞춤형 슬림 UI (New!):** 가독성을 높이는 **반투명 다크 패널**, 현재 공역 표시, 진행바 표시, 공역 티어 표시 등을 입맛에 맞게 독립적으로 켜고 끌 수 있습니다. 게임 화면 가림을 최소화하도록 상하 여백을 초슬림하게 최적화했습니다.
* **우버디아 프로그레스 바:** 아시아, 유럽, 아메리카 서버의 진행도를 우측 하단에 실시간으로 표시합니다.
* **⚡ 스마트 폴링 (최적화):** 공역이 바뀌는 정각/30분 근처(5분 전후)에는 1분마다, 그 외의 조용한 시간대에는 5분마다 데이터를 동기화하여 API 서버 부하를 줄이면서도 정확도를 완벽하게 유지합니다.
* **완벽한 게임 통합:** 클릭 관통(Click-through) 투명 창 모드로 작동하여 게임 플레이(클릭, 이동)에 전혀 지장을 주지 않습니다.
* **버전 실시간 확인:** 트레이 메뉴(작업 표시줄 아이콘 우클릭)에서 현재 내 버전과 GitHub에 올라온 최신 버전을 실시간으로 비교할 수 있습니다.

---

## 🚀 시작하기

### 1. 프로그램 다운로드 (초보자 가이드)
GitHub 사용이 익숙하지 않으신 분들은 아래의 순서대로 진행해 주세요.
1. 화면 우측의 **Releases** 섹션에서 최신 버전을 클릭합니다.
2. **Assets** 항목 아래에 있는 **`.zip` 압축 파일**을 클릭하여 다운로드합니다.
3. 로컬 환경(내 PC)에서 다운로드한 파일의 압축을 해제합니다.

### 2. 개인 API Key(Token) 발급받기
본 프로그램은 빠르고 안정적인 실시간 정보 제공을 위해 개인용 API Key가 필요합니다.
1. [d2tz.info 회원가입/로그인](https://www.d2tz.info/user-profile) 페이지로 접속합니다.
2. 가입 및 로그인 후, **User Profile** 페이지에서 본인의 **API Key(Token)** 문자를 복사합니다.

### 3. 실행 및 설정 방법
1.  압축을 푼 폴더 안에 `d2_tz.exe` 파일과 **`area.json`** 파일이 함께 있는지 확인합니다. (`area.json`은 공역 이름의 다국어 번역 데이터를 불러오는 데 꼭 필요합니다.)
2.  **디아블로 2: 레저렉션**을 실행합니다. (창 모드 또는 전체 화면 창 모드 권장)
3.  `d2_tz.exe` 파일을 실행합니다.
4.  화면에 "토큰 설정 필요"라는 문구가 뜨면, 윈도우 우측 하단 시스템 트레이(시계 옆)에 있는 빨간색 아이콘을 **우클릭**합니다.
5.  **`🔑 API 토큰 설정 (d2tz.info)`** 을 클릭하고, 복사해둔 API Key를 붙여넣기 한 뒤 확인을 누릅니다.
6.  다시 아이콘을 우클릭하여 **`⚙️ 환경설정`** 에 들어가면 래더/하드코어 모드 설정, 반투명 배경, 티어, 언어(한/영 변경), 즐겨찾기 관리 등 다양한 개인 맞춤 옵션을 설정할 수 있습니다. (설정값은 `d2_overlay_config.json`에 자동 저장됩니다.)

### 4. 단축키 및 메뉴 설정
* **프로그램 완전 종료:** `Ctrl` + `Shift` + `Q`
* **즐겨찾기 테러존 관리:** 환경설정 창 내의 `🔔 즐겨찾기 테러존 관리` 버튼을 눌러 알림을 받을 공역을 체크하거나 [전체 해제]할 수 있습니다.

---

## 🛡️ 보안 및 백신 오탐지 안내 (Security)

본 프로그램은 파이썬(Python) 기반으로 제작되었으며, 키보드 단축키 감지(`keyboard`) 및 윈도우 알림음(`winsound`)을 사용합니다. 이 과정에서 일부 백신 프로그램(Windows Defender 등)이 악성코드로 **오탐지**(False Positive)하여 실행을 차단할 수 있습니다.

* **해결 방법:** 실행이 되지 않거나 파일이 사라질 경우, 프로그램이 위치한 폴더를 **백신 검사 제외 대상**으로 등록한 후 다시 압축을 풀어 실행해 주시기 바랍니다.
* 본 프로그램은 어떠한 개인 정보도 수집하지 않으며 100% 안전한 오픈 소스 기반 스크립트입니다.

---

## ⚠️ 면책 조항 (Disclaimer)

* 본 프로그램은 Blizzard Entertainment와 무관하며, 게임 데이터를 직접 수정하거나 메모리를 조작하지 않는 **순수 웹 데이터 오버레이 도구**입니다.
* 프로그램 사용으로 인해 발생하는 모든 책임은 사용자 본인에게 있으며, 제작자는 어떠한 결과에 대해서도 책임을 지지 않습니다.
* 데이터 제공처(d2tz.info)의 서버 상황에 따라 정보 표시가 일시적으로 지연될 수 있습니다.

---

## 📢 채널 및 문의

* **이메일:** mdloopy02@gmail.com

---

<br><br><br>

---

<a name="english"></a>
# 🛡️ Diablo 2: Resurrected Terror Zone & Diablo Clone Tracker (D2R Tracker)

[⬆️ Back to Top / 한국어](#korean)

This is a transparent overlay program that displays the upcoming **Terror Zone** information and real-time **Diablo Clone** progression across servers directly on your game screen while playing Diablo 2: Resurrected.

---

## ☕ Support (Donation)
If you found this program helpful, please consider buying the developer a coffee! 

* [👉 Buy me a coffee via KakaoPay (Click link on mobile)](https://qr.kakaopay.com/FTeinPf5n9c405794)
> If you are on a PC, please scan the QR code below using your smartphone's camera!

<img src="kakaopay.JPG" width="250" alt="KakaoPay QR Code">

---

## 📸 Screenshots

### 1. Next Terror Zone & Progress Bar
![Terror Zone Screen](right-top.png)
> Displays the next Terror Zone and the remaining time until the next update. (You can independently toggle the Current TZ, Progress Bar, and Translucent Dark Background on/off in the settings.)

### 2. Diablo Clone Progression
![Diablo Clone Screen](right-bottom.png)
> Displays the current Diablo Clone progression for Asia, Europe, and Americas servers in a 6-stage block format (`■■■□□□`) at the bottom right.

---

## ✨ Key Features

* **Real-time TZ Alerts:** Displays the next Terror Zone updated hourly/half-hourly. (Includes ACT info).
* **🌐 Bilingual Support (English/Korean):** Supports both English and Korean seamlessly. You can easily toggle between the two languages in the settings menu at any time.
* **🔔 Custom Favorite Alerts (New!):** Add specific zones to your favorites (🔔). The app will notify you with a **soft text blink** and a **sound (Windows Ding)** when the zone is discovered, and 5 minutes before it starts. (Duplicate zone names are cleanly grouped, and favorites are saved in a shareable `favorite_tz.json` file).
* **🎨 Customizable Slim UI (New!):** Toggle the **Translucent Dark Panel**, Current TZ, Progress Bar, and Exp/Loot Tiers to match your taste. Optimized minimal padding ensures the game screen is never blocked.
* **DClone Progress Bar:** Visually tracks the Diablo Clone progression across 3 regions in real-time.
* **⚡ Smart Polling (Optimized):** Syncs data every 1 minute during active shifts (around the hour/half-hour) and slows down to every 5 minutes during quiet times to save API server loads while maintaining perfect accuracy.
* **Perfect Game Integration:** Operates in a click-through transparent window mode. Mouse clicks pass right through the overlay, causing zero interference with your gameplay.
* **Live Version Check:** Check your current version vs. the latest GitHub release directly from the system tray menu.

---

## 🚀 Getting Started

### 1. Download the Program (Beginner's Guide)
If you are not familiar with GitHub, please follow these steps:
1. Click on the latest version in the **Releases** section on the right side of the screen.
2. Under **Assets**, click the **`.zip` file** to download it.
3. Extract the downloaded zip file on your PC.

### 2. Get a Personal API Key (Token)
This program requires a personal API Key to provide fast and stable real-time data.
1. Go to the [d2tz.info Sign Up/Login](https://www.d2tz.info/user-profile) page.
2. After signing up and logging in, copy your **API Key (Token)** from the **User Profile** page.

### 3. How to Run and Configure
1. Ensure that the extracted folder contains both the `d2_tz.exe` and the **`area.json`** files. (`area.json` is essential for translating Terror Zone names.)
2. Run **Diablo 2: Resurrected**. (Windowed or Windowed Fullscreen mode is recommended)
3. Run `d2_tz.exe`.
4. When the "Token Required" message appears, **right-click** the red icon in your Windows system tray (bottom right taskbar).
5. Click **`🔑 Set API Token (d2tz.info)`**, paste the copied API Key, and click OK.
6. Right-click the icon again and go to **`⚙️ Settings`** to customize your modes (Ladder/NL, HC/SC), translucent background, favorite zones, alerts, language (Eng/Kor), and more. (Settings are auto-saved to `d2_overlay_config.json`).

### 4. Hotkeys & Menu Settings
* **Exit Program:** `Ctrl` + `Shift` + `Q`
* **Manage Favorite Zones:** Click the `🔔 Manage Favorite Zones` button in the Settings to check/uncheck zones you want to be alerted for, or use the [Clear All] button.

---

## 🛡️ Security & False Positives

This program is built using Python and uses the `keyboard` library to detect hotkeys and standard Windows audio for alerts. Because of this, some antivirus programs (like Windows Defender) may flag it as a **False Positive** and block or delete the file.

* **Solution:** If the program is blocked, please add the folder containing the executable to your antivirus **exclusion list** and try running it again.
* This is a 100% safe, open-source tool, and it does not collect any personal information.

---

## ⚠️ Disclaimer

* This program is not affiliated with Blizzard Entertainment and is a **pure web-data overlay tool** that does not modify memory or manipulate game data in any way.
* The user assumes all responsibility for using this program, and the creator is not liable for any consequences.
* Information display may be delayed depending on the server status of the data provider (d2tz.info).

---

## 📢 Contact

* **Email:** mdloopy02@gmail.com

---

<a href="https://lifemoneyhub.com">d2_tz_tracker</a> © 2026 by <a href="https://lifemoneyhub.com">ggeonu-abi</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a>
<img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
<img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
<img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
<img src="https://mirrors.creativecommons.org/presskit/icons/nd.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

**Credits:** Data provided by [D2TZ.info](https://www.d2tz.info/)