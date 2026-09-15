<h1 align="center">👋 Hi, I'm Minjun Kim</h1>
<p align="center">
🎮 <b>Game Client Developer (Unity)</b><br/>
실시간 멀티플레이 · 콘텐츠 시스템 · 모바일 최적화
</p>

---

## 🧑‍💻 About Me
- 🎮 게임 클라이언트 개발 경력 4년+
- 🧩 Unreal5 / Unity / Cocos / Roblox 다양한 엔진 경험
- 🌐 네트워크 & 실시간 동기화 처리 경험
- ⚡ 성능 최적화 및 라이브 서비스 경험
- 🔁 기획 → 개발 → 운영까지 End-to-End 경험

---

## 🛠 Tech Stack

### 🎮 Engines & Platforms
<p>
<img src="https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white"/>
<img src="https://img.shields.io/badge/Unreal_Engine_5-313131?style=flat&logo=unrealengine&logoColor=white"/>
<img src="https://img.shields.io/badge/Roblox-000000?style=flat&logo=roblox&logoColor=white"/>
<img src="https://img.shields.io/badge/WinAPI-00599C?style=flat&logo=windows&logoColor=white"/>
</p>

### 💻 Languages
<p>
<img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Lua-2C2D72?style=flat"/>
</p>

### 🌐 Network & Systems
<p>
<img src="https://img.shields.io/badge/WebSocket-010101?style=flat"/>
<img src="https://img.shields.io/badge/Realtime_Multiplayer-FF6F00?style=flat"/>
<img src="https://img.shields.io/badge/Client--Server_Sync-4CAF50?style=flat"/>
</p>

### ⚙️ Optimization
<p>
<img src="https://img.shields.io/badge/Addressables-FF4081?style=flat"/>
<img src="https://img.shields.io/badge/Memory_Optimization-795548?style=flat"/>
<img src="https://img.shields.io/badge/Performance_Tuning-607D8B?style=flat"/>
</p>

### 🧰 Tools
<p>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/SVN-809CC9?style=flat"/>
<img src="https://img.shields.io/badge/GitExtensions-FF9800?style=flat"/>
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white"/>
<img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white"/>
<img src="https://img.shields.io/badge/Wiki-6C757D?style=flat"/>
<img src="https://img.shields.io/badge/JANDI-00C73C?style=flat"/>
</p>

---

## 💼 Career

### 🏢 `2023.03 ~ Present` Smilegate Entertainment
### 🏢 `2022.01 ~ 2023.03` Supertree 

---

## 🚀 Projects

### 🔊 Organic Reverb System
**공간을 시뮬레이션해서 리버브를 도출하는 실시간 음향 시스템** · 개인 포트폴리오 프로젝트

<p>
<img src="https://img.shields.io/badge/Unreal_Engine_5.8-313131?style=flat&logo=unrealengine&logoColor=white"/>
<img src="https://img.shields.io/badge/C++17-00599C?style=flat&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Game_Audio-8E24AA?style=flat"/>
</p>

프리셋 리버브를 구역마다 바꿔 끼우는 대신, 레벨의 방 구조(크기·재질·문)를 자동으로 분석하고 방 사이를 흐르는 음향 에너지를 물리 모델로 계산해 리버브 파라미터를 실시간으로 만든다.

- 🧱 **자동 공간 인식** — 레벨을 복셀로 스캔해 방·문을 자동 분할 (L자 방은 하나로, 긴 복도는 여러 방으로)
- 🌊 **결합 공간 에너지 확산** — 카펫 옷장 + 콘크리트 홀에서 **이중 기울기 감쇠**(초기 0.30 s → 후기 9.10 s) 재현. 프리셋 스위칭으로는 원리상 만들 수 없는 소리
- 🚪 **음원별 전파** — 문을 돌아오는 회절 경로, 벽 투과 손실, 음원별 잔향 Send (Occlusion / Obstruction / Exclusion)
- 🎯 **원거리 총성 거리감** — 모퉁이 너머 47.5 m에서 도착 지연 139 ms, 로우패스 4 kHz, 멀수록 잔향 비중 증가
- ⚡ **성능** — 방 1000개 기준 틱당 약 145 µs, 레벨 스캔은 프레임 분산 + 워커 스레드
- 🧪 **설계 · 검증** — 엔진 독립 Core(헤더 전용) + Unreal 어댑터 구조, 콘솔 테스트 48개 + Unreal Automation 3개

📂 [GitHub 저장소](https://github.com/kmj5515/organic-reverb-ue5)

---

### 🎤 STOVE 출시 프로젝트
| Project | Description | Link |
|--------|------------|------|
| Idol Raising Game | 사내 공모전 선정 / STOVE 데모 출시 | [바로가기](https://store.onstove.com/ko/games/103616) |
| 3D Puzzle Game | 사내 공모전 선정 / STOVE 데모 출시 | [바로가기](https://store.onstove.com/ko/games/103561) |

---

### 🌐 Roblox Projects
| Project | Link |
|--------|------|
| Starvale RP | https://www.roblox.com/ko/games/11092816532/Starvale-RP |
| Hide & Seek: Prop Hunt | https://www.roblox.com/ko/games/10447320248/Hide-and-Seek-Prop-Hunt |
| Everland Official Gate | https://www.roblox.com/ko/games/9794434732/EVERLAND-Official-Gate |
| PlayDapp Gate | https://www.roblox.com/ko/games/7731668829/PlayDapp-Gate |

---

## 🔗 Links
- 📘 Blog: https://smiletree1203.tistory.com/

---

## 📫 Contact
- GitHub: https://github.com/kmj5515
