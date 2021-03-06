Use Case
========

### 게임 시작

1.	보드와 게임 말을 세팅 후 기기에 전원을 켠다.

![2.기기에 게임 플레이할 인원 수를 입력한다.](https://github.com/NoNamedSelfDriveing/ModuBuru/blob/master/detailed/%EA%B2%8C%EC%9E%84%EC%8B%9C%EC%9E%91/2.md)

![3.기기에서는 각 인원마다 일정량의 돈을 분배한다.](https://github.com/NoNamedSelfDriveing/ModuBuru/blob/master/detailed/%EA%B2%8C%EC%9E%84%EC%8B%9C%EC%9E%91/3.md)


### 건물 구입

![1. 건물을 구입하려는 토지 카드의 바코드를 인식시킨다.](https://github.com/MagmaTart/ModuBuru/blob/master/detailed/1.md)

2.. 토지 또는 원하는 만큼의 건물별 개수를 선택한다.

![3. 디스플레이에 표시된 건물의 가격만큼 기기에 돈을 넣는다.](https://github.com/MagmaTart/ModuBuru/blob/master/detailed/2.md)

4.. 투입된 금액을 디스플레이에 표시한다.

![5. 투입된 금액이 건물 가격 이상이면 건물 서랍을 연다.](https://github.com/MagmaTart/ModuBuru/blob/master/detailed/3.md)

6.. 잔액을 반환한다.

### 통행료 지불

1.	사용자는 자신의 턴일 때, 주사위를 던진다.

2.	도착한 땅이 증서가 없는 남의 땅일 때나 세금을 내는 지역일 경우, 상대가 가지고 있는 토지 증서를 바코드 리더기에 찍는다.

3.	그렇지 않을 경우, 토지 구입 시퀀스로 넘어간다.

![4. 지불할 액수가 디스플레이에 나오고 그 액수 만큼 돈을 넣는다. (Connected with No. 2)](https://github.com/MagmaTart/ModuBuru/blob/master/detailed/4.md)

5.. 턴을 넘기고, 상황을 종료한다.

### 황금열쇠 사용

1.	사용자가 주사위를 던지고 이동한다.

2.	말이 황금열쇠 칸에 도착한다.

3.	사용자는 황금 열쇠를 하나 집어든다.

4.	사용자는 황금 열쇠에 붙어있는 바코드를 리더기에 인식시킨다.

**5. 해당 황금 열쇠가 지폐의 이동을 일으키는 카드일 경우, 디스플레이에 그 카드를 처리하기 위한 화면이 뜬다.**

6.. 해당 황금 열쇠에 맞춰서 지폐의 투입 또는 인출을 수행한다.

7.. 상황을 종료하고, 턴을 다음 사용자로 넘긴다.

### 파산 - 부동산 판매

1.	걸린 토지의 토지 카드를 찍는다.

![2. 벌금이 현재 소유액보다 높으면 부동산 판매 창으로 넘어간다.](https://github.com/SongKJ00/ModuBuru/blob/master/detailed/%ED%8C%8C%EC%82%B0/%EB%B6%80%EB%8F%99%EC%82%B0_%ED%8C%90%EB%A7%A4_2.md)

![3. 자신이 소유한 부동산 목록을 선택하고 판매한다.](https://github.com/SongKJ00/ModuBuru/blob/master/detailed/%ED%8C%8C%EC%82%B0/%EB%B6%80%EB%8F%99%EC%82%B0_%ED%8C%90%EB%A7%A4_3.md)

4.. 선택한 목록들의 총액이 벌금보다 높으면 판매 버튼을 누른다.

![5. 플레이어 부동산 목록에 판매된 목록을 삭제한다.](https://github.com/SongKJ00/ModuBuru/blob/master/detailed/%ED%8C%8C%EC%82%B0/%EB%B6%80%EB%8F%99%EC%82%B0_%ED%8C%90%EB%A7%A4_5.md)

![6. 첫 번째로, 벌금만큼 돈이 인출된다.(이는 걸린 토지 소유자에게 전달)](https://github.com/SongKJ00/ModuBuru/blob/master/detailed/%ED%8C%8C%EC%82%B0/%EB%B6%80%EB%8F%99%EC%82%B0_%ED%8C%90%EB%A7%A4_6.md)

7.. 두 번째로, 벌금을 제외한 나머지 잔액을 인출한다.

### 파산 - 파산 인정(신청)

1.	걸린 토지의 토지 카드를 찍는다.

2.	벌금이 현재 소유액보다 높으면 부동산 판매 창으로 넘어간다.

3.	파산 신청 버튼을 누른다.

![4. 해당 플레이어의 부동산 목록이 모두 무소유 토지로 변환된다.](https://github.com/SongKJ00/ModuBuru/blob/master/detailed/파산/파산신청_4.md)

![5. 해당 플레이어의 데이터베이스를 삭제한다.](https://github.com/SongKJ00/ModuBuru/blob/master/detailed/%ED%8C%8C%EC%82%B0/%ED%8C%8C%EC%82%B0%EC%8B%A0%EC%B2%AD_5.md)
