# kotlin-blackjack

## Card
1. 모양과 숫자를 가진다.

## Deck
1. 52장의 Card를 갖는다.
2. Deck은 셔플할수있다.
3. Card를 한장 주면 cards에서 한장 없어진다.

## Player
1. 이름을 가지며 생성된다.
2. giveCard 메소드를 통해 하나의 카드를 받을수있다.
3. TotalScore를 통해 토탈 점수를 받는다.
4. 카드의 합이 21을 넘기면 bust한다

## TotalScore
1. Card를 받으면 점수를 반환한다.

## BlackJack
1. 게임 시작 전 플레이어들을 만든다.
2. 게임을 시작하면 플레이어들에게 카드 2장을 준다.
3. 플레이어가 bust하지 않으면 카드를 받을지 말지를 물어본다.
4. 플레이어들의 카드의 합을 비교하여 승부를 가른다.
