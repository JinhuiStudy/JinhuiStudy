<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:818cf8,100:22c55e&height=230&section=header&text=JINHUI%20PARK&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Firmware%20to%20Cloud%20%E2%80%94%20Engineering%20Without%20Boundaries&descSize=16&descAlignY=56&descColor=c7d2fe&animation=fadeIn" width="100%" />

<!-- TYPING SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=818CF8&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=700&height=80&lines=nRF52840+Firmware+%E2%86%92+Kafka+Pipeline+%E2%86%92+React+Dashboard;UWB+%C2%B110cm+%7C+1%2C500%2B+Booths+%7C+%E2%82%A920B%2B+Auto+Trading" alt="Typing SVG" /></a>

<br/>

<!-- BADGES -->
[![Experience](https://img.shields.io/badge/Experience-8%2B_Years-6366f1?style=for-the-badge&labelColor=0a0a0a)](https://github.com/JinhuiStudy)
[![Products](https://img.shields.io/badge/Products-20%2B_Shipped-22c55e?style=for-the-badge&labelColor=0a0a0a)](https://github.com/JinhuiStudy)
[![Stack](https://img.shields.io/badge/Stack-Firmware_to_Cloud-818cf8?style=for-the-badge&labelColor=0a0a0a)](https://github.com/JinhuiStudy)

</div>

---

### `> whoami`

**UWB 칩셋 위의 C 펌웨어**를 작성하고, **MQTT → Kafka 파이프라인**을 구축하고, **Spring Boot 서버**에서 처리하고, **React 대시보드**로 시각화하고, **Flutter 앱**으로 사용자에게 전달합니다.

하나의 제품에 필요한 **모든 기술 레이어**를 직접 설계하고 구현합니다.

```
Edge Layer     nRF52840 + DWM1001 (Zephyr RTOS, C)        ← UWB ±10cm
Gateway Layer  Raspberry Pi (Spring Boot, Java)            ← BLE 5.0, 100ms batch
Cloud Layer    Kafka + TimescaleDB + Spring Boot           ← 10,000+ pos/sec
Client Layer   Flutter (iOS/Android) + React (Web)         ← Real-time Dashboard
```

---

### `> featured_projects`

<table>
<tr>
<td width="50%">

#### 🟢 Q2 Industrial RTLS
**센티미터 정확도 실시간 위치 추적**
- nRF52840 펌웨어 (3 State Machines)
- 13종 BLE 프레임 프로토콜 설계
- Kafka 16토픽 → TimescaleDB 12 하이퍼테이블
- 11개 Analytics 서비스 (Anomaly/Predictive/Heatmap)
- GraalVM Native (126MB, 콜드스타트 <1s)
- `Samsung Industrial` 적용

</td>
<td width="50%">

#### 🟣 GrowMaps Indoor Platform
**1,500+ 부스 실내 지도 플랫폼**
- A* 경로 탐색 + RBush 공간 인덱스
- Straight Skeleton → 보행 그리드 자동 생성
- Mapbox GL + deck.gl + Three.js 렌더링
- 112 JPA 엔티티, Algolia 4개 국어 검색
- Flutter 앱 + React 웹 + 키오스크
- `KINTEX` · `BEXCO` 상용 운영

</td>
</tr>
<tr>
<td width="50%">

#### 🟡 Space Story + SDK
**AR 관광 앱 + 크로스플랫폼 UWB SDK**
- iOS (Swift, SPM) / Android (Kotlin, Maven) / Flutter
- BLE → UWB 핸드셰이크 프로토콜
- ARKit + ARCore + Mission/Badge 시스템
- `현대백화점` · `홈플러스` 적용

</td>
<td width="50%">

#### 🔵 Jadu MSA Commerce
**Spring Cloud 마이크로서비스 커머스**
- Gateway / Eureka / Config / RabbitMQ
- Saga 패턴 분산 트랜잭션
- OpenSearch 전문 검색
- Prometheus + Grafana 모니터링

</td>
</tr>
<tr>
<td width="50%">

#### 🩷 Crypto Auto Trading
**₩20억+ 실 자금 자동 매매**
- RSI / MACD / Bollinger / ATR 전략 엔진
- 4레이어 리스크 관리
- 13가지 긴급 청산 시나리오
- Double Write 무결성 보장
- **24/7 무장애 운영**

</td>
<td width="50%">

#### 🟠 More Projects
- **따숨** — ESP32-S3 IoT 헬스케어 (BSS 알고리즘)
- **법쇼** — CNN CAPTCHA 95%+ 법률 플랫폼
- **Space Guard** — RANSAC+WLS+EKF 지게차 안전
- **Volvo** — RTK GPS 차량 검사 (NTRIP cm급)
- **KTL ERP** — 공공기관 재무/인사/급여 시스템

</td>
</tr>
</table>

---

### `> tech_stack`

<div align="center">

#### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

#### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

#### Frontend & Mobile
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

#### IoT & Embedded
![Zephyr](https://img.shields.io/badge/Zephyr_RTOS-4A154B?style=flat-square&logoColor=white)
![nRF52840](https://img.shields.io/badge/nRF52840-00A9CE?style=flat-square&logo=nordicsemiconductor&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![BLE](https://img.shields.io/badge/BLE_5.0-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

#### Database & Cloud
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

#### Algorithm & ML
![A*](https://img.shields.io/badge/A*_Pathfinding-6366f1?style=flat-square)
![EKF](https://img.shields.io/badge/EKF_Sensor_Fusion-22c55e?style=flat-square)
![UWB](https://img.shields.io/badge/UWB_DS--TWR-818cf8?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

</div>

---

### `> deployed_at`

<div align="center">

`Samsung` · `KINTEX` · `BEXCO` · `Hyundai Dept.` · `GS HomePlus` · `Volvo Korea` · `KRRI` · `Busan Science Museum` · `KTL`

</div>

---

### `> career`

| Period | Company | Role | Key Work |
|--------|---------|------|----------|
| **2024 — Now** | Freegrow Enterprise | Full-Stack Engineer | UWB RTLS, Indoor Map Platform, IoT Healthcare, AR SDK |
| 2023 — 2024 | Nomadlab | Team Lead | 5인 개발팀 리드, Flutter 아키텍처 표준화 |
| 2020 — 2022 | Law&People | Dev. Director | MSA Commerce, ML CAPTCHA, ₩20B+ Auto Trading |
| 2017 — 2020 | DureSoft | Engineer | KTL ERP (재무/인사/급여), 국세청 연계 |

---

### `> engineering_principles`

```
1. 현재 데이터가 이론을 이긴다     — 모든 알고리즘을 현장 데이터로 검증
2. 점진적 복잡도 추가              — 이전 단계가 부족함을 증명한 후에만
3. 무자비한 제거                   — 효과 없는 것은 즉시 제거 (LPF, ESP32 GW, Kafka*)
4. 분산 신뢰 아키텍처              — 필터링은 엣지에서, 서버는 신뢰
5. 자가 치유 동기화                — 불일치 감지 시 자동 복구
```

---

### `> system_architecture`

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                    What I Build                              │
│                                                             │
│   ┌─────────┐    ┌─────────┐    ┌─────────┐    ┌─────────┐│
│   │Firmware │───▶│Gateway  │───▶│ Cloud   │───▶│ Client  ││
│   │nRF52840 │    │Rasp. Pi │    │Kafka    │    │Flutter  ││
│   │Zephyr C │    │Spring   │    │Timescale│    │React    ││
│   │UWB/BLE  │    │BLE/MQTT │    │Spring   │    │Mapbox   ││
│   └─────────┘    └─────────┘    └─────────┘    └─────────┘│
│                                                             │
│   ← ±10cm UWB →  ← 100ms →  ← 10K pos/s →  ← Real-time → │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0a0a0a&height=1&section=header" width="100%" />

<br/>

```
"현재 데이터가 이론을 이긴다."
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22c55e,50:818cf8,100:6366f1&height=100&section=footer" width="100%" />

</div>
