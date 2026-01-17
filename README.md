# Sound Wave Visualization (HTML5 + Web Audio API)

A lightweight, dependency-free audio player and waveform visualizer built with **HTML5 Canvas** and the **Web Audio API**.  
It supports local audio playback, real-time waveform rendering, idle animation, and customizable spectrum styles.

---

<details>
  <summary><strong>English (Click to expand)</strong></summary>

## ✨ Features

- 🎵 **Local Audio Playback**
  - Drag & drop audio files or select via file input
  - Supports common formats: `mp3`, `wav`, `m4a`, etc.

- 🌊 **Real-time Waveform Visualization**
  - Time-domain waveform rendered on `<canvas>`
  - Smooth animation using `requestAnimationFrame`

- 💤 **Idle Wave Animation**
  - Displays a subtle animated wave when audio is not playing
  - Visible even on initial page load

- 🎨 **Customizable Spectrum Style**
  - Change waveform **color**, **opacity**, and **line width**
  - One-click reset to default values
  - Dark mode–aware default colors

- 🔊 **Independent Audio Analysis**
  - Volume control does **not** affect waveform analysis
  - Analyzer node is placed before the gain node

- 📱 **Responsive & Retina-ready**
  - Automatically scales for device pixel ratio
  - Adapts to window resizing

</details>

---

<details>
  <summary><strong>한국어 (펼치기/접기)</strong></summary>

## 🚀 How to Use

1. Open `sound-visualization.html` in a modern browser  
2. Drag & drop an audio file (or use the file selector)
3. Click **Play** to start playback and visualization
4. Adjust volume or customize waveform style as needed

> ⚠️ Due to browser autoplay policies, audio playback and the AudioContext
> start only after a user interaction (e.g., clicking the Play button).

---

## 🛠️ Tech Stack

- HTML5
- CSS (no framework)
- JavaScript (Vanilla)
- Web Audio API
- Canvas API

---

## 📄 License

This project is provided as-is for learning, experimentation, and personal or commercial use.  
No external libraries or assets are required.

---

# 사운드 웨이브 시각화 (HTML5 + Web Audio API)

**HTML5 Canvas**와 **Web Audio API**만을 사용해 구현한  
가볍고 의존성 없는 오디오 플레이어 + 파형 시각화 예제입니다.

로컬 오디오 재생, 실시간 파형 렌더링, idle 물결 애니메이션,  
그리고 스펙트럼 스타일 커스터마이징 기능을 포함합니다.

---

## ✨ 주요 기능

- 🎵 **로컬 오디오 재생**
  - 드래그 & 드롭 또는 파일 선택
  - `mp3`, `wav`, `m4a` 등 일반적인 오디오 포맷 지원

- 🌊 **실시간 파형 시각화**
  - `<canvas>` 기반 시간 영역(Time Domain) 파형
  - `requestAnimationFrame` 기반 부드러운 애니메이션

- 💤 **Idle 상태 물결 애니메이션**
  - 재생 중이 아닐 때도 잔잔한 물결 표시
  - HTML 최초 로드 시점부터 표시됨

- 🎨 **스펙트럼 스타일 설정**
  - 파형 **색상 / 투명도 / 두께** 실시간 변경
  - 기본값으로 즉시 초기화 가능
  - 다크 모드 자동 대응 기본 색상

- 🔊 **볼륨과 파형 분석 분리**
  - 볼륨을 조절해도 파형 분석에는 영향 없음
  - `AnalyserNode`를 GainNode 앞단에 배치

- 📱 **반응형 & 고해상도 대응**
  - 디바이스 픽셀 비율(DPR) 자동 처리
  - 창 크기 변경 시 자동 리사이즈

---

## 🚀 사용 방법

1. `sound-visualization.html` 파일을 브라우저에서 열기
2. 오디오 파일을 드래그 & 드롭 (또는 파일 선택)
3. **재생** 버튼 클릭
4. 볼륨 조절 및 파형 스타일 설정

> ⚠️ 브라우저 정책상 오디오 재생과 AudioContext는  
> 반드시 사용자 동작(버튼 클릭 등) 이후에 활성화됩니다.

---

## 🛠️ 사용 기술

- HTML5
- CSS (프레임워크 없음)
- JavaScript (Vanilla)
- Web Audio API
- Canvas API

---

## 📄 라이선스

본 프로젝트는 학습, 실험, 개인/상업적 용도로 자유롭게 사용할 수 있습니다.  
외부 라이브러리나 리소스에 의존하지 않습니다.

</details>
