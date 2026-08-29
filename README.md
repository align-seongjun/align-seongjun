# align-seongjun

혼자 게임과 유틸리티를 만듭니다. 대부분 "직접 쓰려고 만들었다가 계속 붙잡고 있는" 것들입니다.

## 만들고 있는 것

| 프로젝트 | 무엇 | |
|---|---|---|
| **Rooster** | 게임 숙제(일일/주간 컨텐츠) 마감을 등록해두면 임박했을 때 OS 알림으로 알려주는 데스크톱 유틸리티. Rust 엔진 + CLI + 트레이 상주 GUI 패널 | [문서](https://github.com/align-seongjun/tool-rooster-wiki/wiki) · [릴리즈](https://github.com/align-seongjun/tool-rooster-wiki/releases) |
| **Firewall** | 개발 중인 게임 | [플레이 빌드](https://github.com/align-seongjun/firewall-play) · [문서](https://github.com/align-seongjun/game-spider-wiki/wiki) |

## 작업 방식

- **코드보다 문서를 먼저 씁니다.** 요구사항·아키텍처·ADR을 위키에 두고, 구현이 스펙과 갈라지면 코드가 아니라 문서를 먼저 고칩니다.
- **진행 상황의 단일 소스는 Issues와 Projects 보드입니다.** 문서에는 Phase 단위 요약만 남깁니다.
- **코드 저장소는 private, 문서와 릴리즈는 public으로 둡니다.** 그래서 위 표의 링크는 소스가 아니라 문서/배포 저장소를 가리킵니다.

주로 Rust를 쓰고, 필요에 따라 Flutter/Dart와 TypeScript를 씁니다.
