# 👑 오버로드 II (Overlord II) 완전판 통합 한국어 패치 v1.0

<div align="center">

![Overlord II](https://img.shields.io/badge/Game-Overlord%20II-red?style=for-the-badge&logo=steam)
![Version](https://img.shields.io/badge/Patch%20Version-v1.0.0-brightgreen?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Korean%20100%25-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-lightgrey?style=for-the-badge)
![Compatibility](https://img.shields.io/badge/Compatibility-Steam%20%7C%20GOG-orange?style=for-the-badge)

<br/>

**"사악함에는 언제나 길이 있는 법... 이제 완벽한 한국어로 미니언 군단을 지휘하십시오!"**

**오버로드 II (Overlord II)**의 모든 텍스트(UI, 퀘스트, 튜토리얼, 컷신, 스토리 대사, 로딩 팁, 미니언 이름)를 100% 완벽하게 로컬라이징한 통합 한국어 패치입니다.  
최신 Windows 10/11 환경의 고질적인 무한 로딩 버그를 해결하는 최적화 패치가 기본 포함되어 있습니다.

</div>

---

## 📑 목차
- [주요 특징](#-주요-특징)
- [패치 상세 내역](#-패치-상세-내역)
- [다운로드 및 설치 방법](#-다운로드-및-설치-방법)
  - [방법 1. GUI 자동 설치기 (권장)](#방법-1-gui-자동-설치기-가장-쉬운-방법)
  - [방법 2. 배치 파일 자동 설치 (BAT)](#방법-2-배치-파일-자동-설치-bat)
  - [방법 3. 수동 복사 설치](#방법-3-수동-직접-복사-설치)
- [자주 묻는 질문 (FAQ)](#-자주-묻는-질문-faq)
- [삭제 및 원본 복구 안내](#-삭제-및-원본-복구-안내)
- [패치 파일 구조](#-패치-파일-구조)
- [저작권 및 주의사항](#-저작권-및-주의사항)

---

## ✨ 주요 특징

- **100% 완전 한글화**: 메뉴, 설정, 대사, 퀘스트, 튜토리얼, 로딩 팁, 904종 미니언 이름까지 완벽 번역
- **편리한 설치 프로그램 제공**: 경로 자동 탐색 및 폴더 선택 기능이 탑재된 전용 GUI 설치기(`Installer.exe`) 및 BAT 스크립트 제공
- **Windows 10 / 11 무한 로딩 원천 해결**: 구버전 PhysX 충돌로 인한 실행 불가/무한 로딩 픽스(`PhysXCore.dll`) 내장
- **원본 컨테이너 바이트 무결성 유지**: 게임 엔진 크래시 방지를 위해 RPK 바이트 밸런싱을 적용하여 엔진 안정성 극대화
- **세이브 파일 안전 보호**: 한글 프로필명으로 인한 세이브 경로 깨짐 현상을 원천 방지하는 세이프가드 적용
- **선명한 고해상도 글꼴**: 가독성을 극대화한 맑은 고딕 기반 전용 비트맵/벡터 폰트 탑재

---

## 🔍 패치 상세 내역

### 1. 인터페이스 및 시스템 (Interface.prp & System.psp)
- 메인 메뉴, 싱글플레이, 화면 분할(Split Screen), 그래픽/오디오 세부 설정 전체 번역
- 조작 키 안내 및 게임패드 버튼 태그(`<I=10>`, `<I=21>` 등) 100% 매핑
- 암흑의 탑 알현실, 대장간(무기/갑옷 벼리기), 무기고, 주문 강화 창 완벽 지원

### 2. 메인 퀘스트 및 서브 목표 (System_Quests)
- 프롤로그부터 최종 결전까지 모든 퀘스트 타이틀 및 서브 태스크 한글화
- 목표 HUD 메시지(예: *"성소에서 암흑탑 심장을 충전하십시오"*, *"마법의 방에서 주문을 강화하십시오"* 등) 완벽 지원

### 3. 전체 챕터 스토리 및 NPC 대사 (Language\*.8ld 총 46개)
- **프롤로그(Prelude)**: 노드버그 마을 축제, 눈싸움 튜토리얼, 마법소년 컷신 전수 한글화
- **캠페인 전편**: 노드버그(Nordberg), 에버라이트(Everlight), 황무지(Wastelands), 제국 수도 및 투기장(Empire City & Arena), 암흑의 탑(Netherworld)
- **개성 넘치는 환경 대사**: 시민 수다, 군단병 잡담, 히피 엘프들의 대사까지 생생한 어조로 로컬라이징

### 4. 튜토리얼 및 게임 팁
- 키보드/마우스 및 엑스박스 패드 튜토리얼 100% 일치 (얼음 요새 스위핑, 마법 시전 등 완벽 번역)
- 로딩 화면 팁 67종 전수 번역 완료

---

## 📥 다운로드 및 설치 방법

[**👉 최신 버전 다운로드 (Releases 바로가기)**](https://github.com/) 에서 `Overlord2_Korean_Patch_v1.0.zip` 파일을 다운로드합니다.

다운로드한 압축 파일(`Overlord2_Korean_Patch_v1.0.zip`)을 압축 해제하면 다음 파일들이 나타납니다:
- `Overlord2_Korean_Patch_Installer.exe` (전용 GUI 설치기)
- `한글패치_자동설치.bat` (배치 스크립트 설치기)
- `PhysXCore.dll`
- `Language` 폴더
- `Resources` 폴더

---

### 방법 1. GUI 자동 설치기 (가장 쉬운 방법)

1. `Overlord2_Korean_Patch_Installer.exe`를 실행합니다.
2. 스팀 기본 설치 경로가 자동으로 인식됩니다.
   - 만약 다른 드라이브나 폴더에 설치되어 있다면 **[찾아보기]** 버튼을 눌러 `Overlord2.exe`가 있는 폴더를 선택합니다.
   - *스팀 기본 경로: `C:\Program Files (x86)\Steam\steamapps\common\Overlord II`*
3. **[한글 패치 설치 시작]** 버튼을 클릭합니다.
4. 자동으로 원본 파일 백업 및 패치 파일 복사가 진행되며, 완료 메시지가 뜨면 게임을 실행합니다.

---

### 방법 2. 배치 파일 자동 설치 (BAT)

1. 압축 해제한 파일들을 **오버로드 II 게임 설치 폴더** 안으로 모두 이동시킵니다.
2. `한글패치_자동설치.bat`를 더블 클릭하여 실행합니다.
3. 화면의 안내에 따라 설치가 진행됩니다 (기본 백업 자동 생성).
4. `설치가 성공적으로 완료되었습니다!` 메시지가 뜨면 창을 닫고 게임을 실행합니다.

---

### 방법 3. 수동 직접 복사 설치

1. `Overlord2_Korean_Patch_v1.0.zip`의 압축을 풉니다.
2. `Language` 폴더, `Resources` 폴더, `PhysXCore.dll` 파일을 게임 설치 경로(`Overlord2.exe`가 있는 곳)에 붙여넣고 덮어쓰기합니다.

---

## ❓ 자주 묻는 질문 (FAQ)

#### Q1. 새 프로필(New Profile) 생성 시 이름이 영어로 나옵니다. 오류인가요?
> **정상입니다.** 오버로드 II 엔진은 윈도우 사용자 문서 폴더(`Documents\My Games\Overlord II\Saves`)에 프로필명으로 세이브 폴더를 생성합니다. 이때 프로필 이름에 한글이 들어가면 윈도우 인코딩 충돌로 세이브가 저장되지 않거나 게임이 튕기는 심각한 버그가 발생합니다.  
> 이를 방지하기 위해 기본 프로필 명칭을 안전한 영문인 **`Overlord II`**로 고정해 두었습니다.

#### Q2. 게임 실행 시 화면이 멈추거나 무한 로딩이 걸립니다.
> 패키지에 동봉된 **`PhysXCore.dll`** 파일이 게임 실행 파일(`Overlord2.exe`)과 동일한 폴더에 있는지 확인해 주세요. 최신 Windows 10/11 시스템에서 지포스 드라이버 충돌로 발생하는 문제를 해결해 줍니다.

#### Q3. 스팀 도전과제나 도전 모드도 정상 작동하나요?
> 네, 순수 언어 리소스 및 폰트 레이어만 교체하므로 스팀 도전과제 달성 및 모든 게임 기능이 정상 작동합니다.

---

## 🔄 삭제 및 원본 복구 안내

언제든지 순정 원본 상태로 복구할 수 있습니다.

- **스팀 무결성 검사 (가장 깔끔한 방법)**:
  1. Steam 라이브러리에서 **Overlord II** 우클릭 $\rightarrow$ **[속성]** 선택
  2. **[설치된 파일]** 탭 $\rightarrow$ **[게임 파일 무결성 검사]** 클릭
- **자동 백업 복원**:
  - 패치 설치 시 게임 폴더 내 `backup_original` 폴더에 원본 파일이 자동 백업되어 있으므로, 해당 폴더의 내용을 복원하셔도 됩니다.

---

## 📂 패치 파일 구조

```
Overlord II/
│
├── Overlord2.exe                     <- 게임 실행 파일
├── PhysXCore.dll                     <- Win 10/11 무한 로딩 방지 런타임 DLL
├── Overlord2_Korean_Patch_Installer.exe <- 전용 GUI 원클릭 설치기
├── 한글패치_자동설치.bat              <- 배치 스크립트 설치기
├── README.md                         <- 본 안내 문서
│
├── Resources/
│   ├── Interface.prp                 <- UI, 메뉴, 시스템 한글 패치 (10,572,055 Bytes 유지)
│   ├── PC Pack.prp                   <- PC 플랫폼 문자열 패치
│   └── System.psp                    <- 퀘스트, 튜토리얼, 툴팁 시스템 패치 (11,948,137 Bytes 유지)
│
└── Language/
    ├── ENGLISH/
    │   ├── Overlord.TTF              <- 메인 UI 글꼴
    │   ├── Subtitle.ttf              <- 자막 전용 글꼴
    │   └── Title.TTF                 <- 타이틀 전용 글꼴
    │
    ├── Prelude.8ld                   <- 프롤로그 전체 한글화
    ├── Ambient_*.8ld                 <- 챕터별 환경 대사 한글화 (5종)
    ├── Empire*.8ld                   <- 제국 챕터 스토리/투기장/최종전 한글화 (4종)
    ├── Everlight*.8ld                <- 에버라이트 정글/사원/마을 한글화 (5종)
    ├── Nordberg*.8ld                 <- 노드버그 마을/성소 한글화 (3종)
    ├── NW_*.8ld                      <- 암흑의 탑/알현실/막사/대장간 한글화 (3종)
    ├── Wastelands*.8ld               <- 황무지/성소 한글화 (2종)
    └── Resources/
        ├── Interface.8ld             <- 인터페이스 단어 사전
        ├── System.8ld                <- 시스템 명칭 및 장비 설명
        ├── System_Quests.8ld         <- 메인/서브 퀘스트 목표 풀 한글화
        ├── TutorialMessages_*.8ld    <- 마우스/패드 튜토리얼 풀 한글화
        ├── Loading_Screen_*.8ld      <- 로딩 화면 게임 팁 67종 풀 한글화
        ├── Minion_Names.8ld          <- 904종 개별 미니언 이름 풀 한글화
        └── MinionCausesOfDeath.8ld   <- 미니언 사망 원인 한글화
```

---

## ⚖️ 저작권 및 주의사항

- 본 한국어 패치는 비영리 목적으로 제작된 순수 팬 패치입니다.
- 게임의 모든 저작권 및 지적재산권은 원저작권자인 **Triumph Studios** 및 **Codemasters**에 있습니다.
- 본 패치 파일의 무단 재가공, 상업적 판매 또는 유료 사이트 재배포를 금지합니다.
