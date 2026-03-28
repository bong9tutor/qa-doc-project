# 🎮 QA 프로젝트

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.6.1-0E1128?style=for-the-badge&logo=unrealengine)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)
![Project](https://img.shields.io/badge/Project-QA-green?style=for-the-badge)

---

## 📖 목차
- [기술 문서 온라인 보기](#-기술-문서-온라인-보기)

---

## 📄 기술 문서 온라인 보기

> **GitHub Pages**로 호스팅됩니다. 아래 링크를 클릭하면 브라우저에서 바로 확인할 수 있습니다.
>
> GitHub Pages가 활성화되어 있지 않다면 → 레포 **Settings → Pages → Source: Deploy from a branch → Branch: `master` / `/ (root)` → Save**

### 전체 문서 홈

| | 링크 |
|---|---|
| 📋 **문서 홈** | [AVaOut 기술 문서 목록](https://bong9tutor.github.io/qa-doc-project/doc/index.html) |

### 기술 문서

| 문서 | 링크 | 주요 내용 |
|------|------|-----------|
| 01 · 게임 세션 흐름 | [Session Flow](https://bong9tutor.github.io/qa-doc-project/doc/01_session_flow.html) | 6단계 세션 흐름 + Seamless Travel 라이프사이클 + 데이터 영속성 + 음성채팅 |
| 02 · 네트워크 아키텍처 | [Network Architecture](https://bong9tutor.github.io/qa-doc-project/doc/02_network_arch.html) | Authority 모델 + DOREPLIFETIME 조건 + Reliable/Unreliable + GAS Replication |
| 03 · 상태 머신 | [State Machine](https://bong9tutor.github.io/qa-doc-project/doc/03_state_machine.html) | 상태 네트워크 동기화 + AI StateTree 전이 + GAS 연관 + 전체 게임 사이클 |
| 04 · RPC / Replication 흐름 | [RPC & Replication Flow](https://bong9tutor.github.io/qa-doc-project/doc/04_rpc_replication.html) | 5가지 시나리오 + Reliable/Unreliable 가이드 + Replicated 패턴 + 동시 접근 해결 |
| 05 · ServerTravel & 데이터 영속성 | [ServerTravel & Persistence](https://bong9tutor.github.io/qa-doc-project/doc/05_servertravel_persistence.html) | 전체 사이클 다이어그램 + 영속성 매트릭스 + Save/Restore 패턴 + 실패 모드 |
| 06 · 네트워크 버그 패턴 & QA 가이드 | [Network Pitfalls & QA](https://bong9tutor.github.io/qa-doc-project/doc/06_network_pitfalls.html) | RPC/Replication/Authority/Multicast/Travel 함정 + QA 체크리스트 10항목 |

### 소스 코드 리뷰 — 268개 클래스, 20개 카테고리

| | Sonnet 4.6 | Opus 4.6 (심층) |
|---|---|---|
| **허브** | [허브](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet.html) | [허브](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus.html) |

<details>
<summary>전체 카테고리 목록 (20개)</summary>

| # | 카테고리 | 클래스 | Sonnet | Opus |
|---|---------|--------|--------|------|
| 1 | 게임 프레임워크 | 4 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_framework.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_framework.html) |
| 2 | 플레이어 | 2 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_player.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_player.html) |
| 3 | AI 시스템 | 3 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_ai.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_ai.html) |
| 4 | 게임 시스템 | 4 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_systems.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_systems.html) |
| 5 | 게임모드 & 컨트롤러 | 12 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_gamemode.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_gamemode.html) |
| 6 | GAS 어빌리티 | 10 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_abilities.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_abilities.html) |
| 7 | 플레이어 컴포넌트 | 6 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_components.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_components.html) |
| 8 | AI 유형별 | 12 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_ai_types.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_ai_types.html) |
| 9 | 인벤토리 & 아이템 | 9 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_inventory.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_inventory.html) |
| 10 | 상호작용 & UI | 6 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_interaction.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_interaction.html) |
| 11 | StateTree Tasks | 24 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_st_tasks.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_st_tasks.html) |
| 12 | StateTree Conditions | 23 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_st_conditions.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_st_conditions.html) |
| 13 | AI 컨트롤러 & 애니메이션 | 14 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_ai_detail.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_ai_detail.html) |
| 14 | AI GAS & EQS | 18 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_ai_gas_eqs.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_ai_gas_eqs.html) |
| 15 | 퍼즐 시스템 | 21 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_puzzle.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_puzzle.html) |
| 16 | UI 위젯 | 17 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_ui_widgets.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_ui_widgets.html) |
| 17 | 플레이어 확장 | 12 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_player_ext.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_player_ext.html) |
| 18 | 월드 & 인터페이스 | 23 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_world.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_world.html) |
| 19 | 메카닉 & 컴포넌트 | 25 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_mechanics.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_mechanics.html) |
| 20 | 데이터 & 유틸리티 | 23 | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_sonnet_data_util.html) | [링크](https://bong9tutor.github.io/qa-doc-project/doc/code_review_opus_data_util.html) |

</details>
