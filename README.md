# 3주차 파이썬 개인과제
1. 시작
    - 플레이어 생성  class 를 통해 만들어 주었고 mp 와 power , magic 을 따로 만들어 일반공격 , 마법공격(1회성필살기 를 만들어주었다)

    - 몬스터 생성 (Monster) 몬스터 3마리를 만들어주었고 그 중 1,2,3 번을 나누어 다른 몬스터를 만나게 했다
2. 전투
    - input 을 통해 행동을 선택할수있게 만들었고 일반공격, 필살기 , 포션이라는 기능도 만들어봤다
    while 을 사용해서 플레이어 , 몬스터가 계속 살아있다면 인풋을 통해 행동을 선택할 수 있게 만들고 행동이 끝나면 몬스터가 공격한다 이후
    플레이어와 몬스터의 alive 값이 참이면 처음부터 루프를 계속 진행한다
3. 종료
    - 몬스터의 공격이 끝난 다음에 플레이어나 몬스터의 alive 의 참 , 거짓을 확인 한 후 거짓이면 게임종료 참이면 다시 반복되도록 했다
