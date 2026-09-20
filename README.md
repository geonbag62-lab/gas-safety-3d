# 🛡️ Gas Safety Inspection 3D

> 브라우저에서 직접 플레이하며 배우는 3D 가스안전 대응 시뮬레이션

**Gas Safety Inspection 3D**는 가스 누출이 의심되는 상황을 3D 게임 형태로 체험하면서, 올바른 안전 대응 절차를 학습할 수 있도록 제작한 브라우저 기반 교육용 시뮬레이션입니다.

실제 누출 상황에서 임의로 원인을 찾거나 수리하는 것이 아니라, 안전한 범위에서 차단, 자연 환기, 대피, 신고로 이어지는 대응 절차를 게임의 미션으로 구성했습니다.

## 🎮 Play

**[▶️ Play the game](https://YOUR-USERNAME.github.io/gas-safety-3d/)**

> GitHub Pages 배포 후 위 주소를 실제 저장소 주소로 변경하세요.

## ✨ Features

* 🏠 3D 실내 공간 탐색
* 🎮 WASD 기반 이동
* 🖱️ 마우스를 이용한 시점 회전
* 🔎 오브젝트 상호작용
* ⛽ 가스 농도 변화 시스템
* ⏱️ 플레이 시간 측정
* 🏆 점수 및 감점 시스템
* 📋 단계별 안전 미션
* 🧠 안전 수칙 퀴즈
* 📞 119 신고 상황 체험
* 🔊 효과음 및 절차적 배경음
* 💡 상황별 안전 정보 안내
* 📊 미션 완료 결과 및 평가

## 🎯 Mission

게임에서는 다음과 같은 순서의 안전 대응 과정을 경험합니다.

1. 가스레인지 불을 끄고 밸브 잠그기
2. 안전하게 접근할 수 있을 때 메인밸브 잠그기
3. 전기 조작 없이 문과 창문을 열어 자연 환기
4. 핵심 안전 수칙 확인하기
5. 문 밖 안전지대로 대피하기
6. 외부에서 119 신고하기

각 단계는 실제 게임 내 상호작용과 미션 진행을 통해 수행하도록 구성되어 있습니다.

## 🕹️ Controls

| Action      | Control         |
| ----------- | --------------- |
| Move        | `W` `A` `S` `D` |
| Look around | Mouse drag      |
| Interact    | Click / Press   |
| Pause       | `ESC`           |

## 🧩 Technology

* HTML5
* CSS3
* JavaScript
* [Three.js](https://threejs.org/)
* Web Audio API
* WebGL

Three.js를 이용해 별도의 게임 엔진 없이 브라우저에서 3D 공간과 상호작용 시스템을 구현했습니다.

## 🔊 Audio

게임의 배경음과 효과음은 Web Audio API를 활용해 브라우저에서 직접 생성되도록 구성했습니다.

따라서 별도의 음악 파일을 프로젝트에 포함하지 않고도 기본적인 게임 사운드를 구현할 수 있습니다.

## 🌐 Run Locally

별도의 빌드 과정 없이 최신 데스크톱 브라우저에서 실행할 수 있습니다.

```bash
git clone https://github.com/YOUR-USERNAME/gas-safety-3d.git

cd gas-safety-3d
```

그 다음 `index.html`을 브라우저에서 실행합니다.

> 프로젝트는 키보드와 마우스 조작을 사용하는 데스크톱 환경을 기준으로 제작되었습니다.

## 🎮 Play the Game

[▶️ Play Gas Safety Inspection 3D](gas-safe.netlify.app)

## 📸 Screenshots

### Gameplay

![Gameplay](screenshots/gameplay.png)

### Mission System

![Mission System](screenshots/mission.png)

### Result

![Result](screenshots/result.png)

## 📚 Educational Purpose

이 프로젝트는 게임이라는 인터랙티브한 형식을 통해 가스 누출 의심 상황에서의 안전 대응 절차를 체험하도록 설계된 교육용 시뮬레이션입니다.

게임 시작 화면에서도 실제 누출 의심 상황에서는 원인을 찾거나 수리하지 말고, 전기 조작을 피하며 안전한 범위에서 대응하도록 안내합니다.

## ⚠️ Disclaimer

본 프로젝트는 교육 및 시뮬레이션을 목적으로 제작되었습니다.

실제 가스 누출이 의심되는 상황에서는 게임의 내용만을 근거로 행동하지 말고, 관계 기관 및 전문가의 공식 안전 안내를 따라야 합니다.

## 📄 License

MIT License
