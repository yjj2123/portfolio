# 🖥 TCP Fighter

> select 기반 2D 액션 MMO 서버 · 학원 과제 (2026.01 ~ 03)

<a href="https://github.com/yjj2123/tcpfighter-select-mmo"><img src="https://img.shields.io/badge/GitHub-코드_보기-181717?style=for-the-badge&logo=github"></a>

`C++` `Winsock2 select` `섹터 AOI`

## 핵심

- **2만 세션 접속** 확인 (목표 15,000)
- **625개 섹터 AOI** — 주변 9칸에만 전송해 전송량 절감
- **서버 권위 좌표 검증** — 클라이언트 좌표가 50px 이상 다르면 서버 좌표로 동기화
- **select 한계 측정** — 세션이 늘 때 Loop/sec 125,539 → 8,142, IOCP 로 옮긴 근거

클라이언트와 더미 클라이언트는 학원 제공물이라 코드 저장소에는 서버 코드만 있습니다.

[← 처음으로](..)
