# kkutu_hack

### 끄투 코리아
---------------------------------------
### 도구
* python
* selenium
* postgresql
* chromedriver
* javascript

##### 1대1을 생각하며 단어를 받아오고, 전송하기까지 가장 빠른 속도를 목적으로 구상했기 때문에 3명 이상에서 같이 플레이 하면 오류가 납니다.
##### postgresql을 이용하여 매너, 어인정 모드를 킨 상태의 단어들을 걸러 no_no_kill.txt 파일에 저장했습니다.


* 게임을 시작한 상태로 아무 문자나 숫자를 입력하면 핵이 작동 됩니다.
* 상대방과 본인이 현재 라운드에서 사용한 단어를 다른 리스트에 옮기고, 다음 라운드가 시작되면 다시 원래 리스트에 추가합니다.
* 상대방이 사용한 단어가 본인의 단어 리스트에 없으면 추가할 단어를 출력합니다.
* 게임이 끝나면 다시 문자나 숫자를 입력할 때까지 기다립니다. 다음 게임에 들어가 다시 문자나 숫자를 입력하면 작동 됩니다.
* TWO_KILL 배열은 이어갈 단어가 별로 없는 끝글자를 모아두었습니다. 그 중에서도 이어갈 단어 개수가 적은 단어를 우선으로 탐색하게 하도록 앞 인덱스에 위치했습니다.

* 상대방이 단어를 입력하면 사

---------------------------------------

##### db, selenium, 크롤링 자체를 처음 접하는 거라 제작 시간이 1주일이 걸렸습니다 .. 
##### 코드가 더럽다고 생각하실지도 너그러운 마음으로 봐주세요 :)
