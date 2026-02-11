# 🚀 [Tescomwireless SW LAB] Dev Team

> **Plugin-driven Monorepo 기반으로 혁신적인 솔루션을 구축합니다.**
> 우리는 모든 코드의 이력을 추적 가능하게 관리하며, 안정적인 배포 프로세스를 지향합니다.

---

### 🏗️ Software Architecture
우리 조직은 하나의 저장소에서 여러 프로젝트를 효율적으로 관리하는 **Plugin Monorepo** 구조를 채택하고 있습니다. 각 프로젝트는 독립적인 생명주기를 가지면서도 조직의 표준화된 개발 프로세스를 공유합니다.

---

### 🔄 Development Workflow
우리는 모든 작업을 **Issue - Branch - PR - Release**의 선순환 구조로 관리합니다.

#### 1. Issue-Driven Development
* 모든 작업은 GitHub Issue를 통해 시작됩니다. 
* 신규 기능 개발부터 사소한 수정까지 모든 이력을 티켓 기반으로 관리하여 투명성을 확보합니다.

#### 2. Structured Branching Strategy
프로젝트 간 간섭을 최소화하기 위해 계층화된 브랜치 전략을 사용합니다.
* **Mainline (`main`)**: 모든 프로젝트의 안정된 코드가 병합되는 최상위 브랜치입니다.
* **Project Root (`dev-<project>/main`)**: 각 프로젝트별 중심 브랜치입니다.
* **Work Branch**: 실제 개발이 이루어지는 작업 단위 브랜치입니다. (`feat`, `fix`, `refactor`, `docs` 등)

#### 3. Rigorous Code Review
* 모든 코드는 Pull Request(PR)를 통해서만 병합됩니다.
* 변경 요약, 영향 범위 확인, 테스트 결과 검증을 거쳐 동료의 승인을 얻어야 합니다.

#### 4. Tag-Based Release
* 배포되는 모든 결과물은 시맨틱 버저닝(Semantic Versioning)에 따라 엄격하게 태그로 관리됩니다.
* 운영 이슈 발생 시 신속한 대응을 위해 전용 **Hotfix 프로세스**를 운영하고 있습니다.

---

### 🛠 Tech Stack

우리는 공정 자동화와 고성능 웹 서비스를 위해 아래와 같은 기술 스택을 활용합니다.

| Category | Technologies |
| :--- | :--- |
| **Testing Process Automation** | ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Web Development** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) |
| **Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
---

### 🤝 Join Our Journey
조직의 멤버로 합류하셨나요? 
1. **Tescomwireless.com** 메일을 통해 회사 계정을 GitHub에 연결하세요.
2. 내부 Wiki에서 상세한 **Branch Naming & SAP Convention** 가이드를 숙지해 주세요.
3. 첫 작업을 시작하기 전 `Branch Request` 이슈 템플릿을 확인하세요!

---
© 2026 Tescomwireless. All rights reserved.
