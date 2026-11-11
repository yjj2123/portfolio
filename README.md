# 유정재 포트폴리오

게임 기획 · C++ 게임 서버

<br>

# 기획

## 메이플 빌리지

메이플스토리 월드 SRPG · 1인 개발 · 2026.10.31 공개 출시

- 시스템 기획서 24개 장, 장마다 '확인 기준' 절
- 성장 · 난이도 · 민심 수치를 측정 결과로 조정
- 출시 후 6번 업데이트 (v1.0.0 → v1.1.3)
- 규칙 · 수치는 직접 정하고, 문서 정리 · 구현 · 테스트는 AI 세션에 나눠 맡김

[기획 포트폴리오 PDF](assets/maple-village-portfolio.pdf) · [플레이](https://maplestoryworlds.nexon.com/ko/play/d881daaedf5d484f994357db0f8c6438)

<br>

# 서버

## IOCP 채팅 서버

C++17 · Windows IOCP · 개인 프로젝트 (2026.04 ~ 06)

- 컨텐츠 전담 스레드 하나로 컨텐츠 영역 락 제거, DB 호출은 별도 스레드
- Lock-Free 메모리 풀, AES-128-CTR + HMAC-SHA256 패킷 암호화
- 동접 약 1,000 · 2시간 부하 검증, 메모리 변동 0.4% · 에러 0건

[코드](https://github.com/yjj2123/iocp-chatserver)

## TCP Fighter

C++ · select 기반 2D 액션 MMO 서버 · 학원 과제 (2026.01 ~ 03)

- 2만 세션 접속 확인
- 625개 섹터로 나눠 주변 9칸에만 전송
- 서버 권위 좌표 검증

[코드](https://github.com/yjj2123/tcpfighter-select-mmo)

<br>

# 경력

- EA Korea · QA (2023.03 ~ 2025.03) — FC 온라인 리브랜딩
- 프로카데미 · C++ 게임 서버 프로그래밍 (2025.04 ~ 2026.04)
