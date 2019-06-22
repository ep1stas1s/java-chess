# java-chess
체스 게임 구현을 위한 저장소

## 기능구현

- 체스판 (8 x 8)
    - 각 진영은 대문자 소문자로 구분
    - 빈 곳은 점(.)으로 구분
    - 가로 (a~h), 세로(1~8)

- 명령어
    - 시작 : start
    - 종료 : end
    - 이동 방법 : move source위치 target위치 (예. move b2 b3)
    - 항복 : surrender
    - 점수 출력 : status
    
- 승패 및 점수
    - 킹이 잡혔을 경우
    - 상대방이 포기했을 경우
    - 킹(k) 0점, 폰(p) 1점, 나이트(n) 2.5점, 비숍(B) 3점, 룩(r) 5점, 퀸(q) 9점
    
- 체스말 규칙
    - 폰(p) : 처음 2칸까지 가능, 1칸 이동, 잡을 때 대각선
    - 나이트(n) : 1칸 + 그 방향 대각선
    - 룩(r) : 직선 방향 무제한
    - 비숍(b) : 대각선 방향 무제한 
    - 퀸(q) : 직선, 대각선 방향 무제한 
    - 킹(k) : 직선, 대각선 방향 1칸
    
- 특수 규칙
    - 캐슬링
    - 앙파상
    - 체크, 체크메이트
    - 프로모션 (폰 승격)
    - 무르기