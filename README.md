## networkProject 

- 🎮 라이어 게임 (Swing GUI 구현)

📝 게임 개요
여러 명의 클라이언트가 참여하는 게임
각 클라이언트에게 동일한 주제어가 주어짐
단, 한 명만 다른 주제어를 받음 → 이 플레이어가 라이어

🖥 구현 방식
Java Swing을 활용한 GUI 기반 게임
클라이언트-서버 구조로 다중 플레이어 지원
주제어 배포 및 투표 시스템 구현

🔄 게임 진행 방식
1. 각 플레이어가 순서대로 자신의 주제어에 대해 설명
  라이어는 정해진 주제어를 모르므로 티가 나기 쉬움
2. 한 바퀴 돌고 나면 투표 진행
  누가 라이어인지 플레이어들이 투표
  라이어가 맞으면 게임 종료 (라이어 패배)
3. 라이어가 아닌 경우, 한 바퀴 더 설명 진행
  이후 다시 투표
  이 과정을 반복
4. 승리 조건
  라이어가 마지막 3명 중 생존하면 라이어 승리
  라이어가 나머지 플레이어들의 주제어를 맞추면 라이어 승리
  투표로 라이어가 잡히면 라이어 패배
