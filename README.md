# homeserver
리눅스 홈 서버 구축 관련 진행이력 저장을 위함이다.
--(작성중)



## 1. 설치준비(2022.12.17)

### 1.1 장비 사양

데스크탑 PC 를 활용한다.
사양을 자세히 적는 것은 아래 구성의 부품조합에서 
소비전력이 얼마나 나올지에 대해 자료를 만들기 위함 이다.

|부품구분|부품명|설명|
|---|---|---|
|CPU| 인텔® 제온® 프로세서 E3-1230 v3 | - |
|메인보드| ASRock Z87 Extreme4 | - |
|메모리| 삼성전자 DDR3-1600 8GB x 4, 32GB | |
|SSD0| 삼성전자 SSD 850 EVO 500GB | - |
|HDD0| WDC WD6400AAKS 640GB | - |
|VGA| GeForce® GTX 1070 G1 Gaming 8G | - |
|랜카드| EFM ipTIME PX1000 PCI-E 기가비트 랜카드 | - |
|파워서플라이| topower TOP-800WB 80PLUS BRONZE Single Rail | - |
|ODD| topower TOP-800WB 80PLUS BRONZE Single Rail | - |
|케이스| 잘만 Z9 Plus | - |
|기타| 120GB SSD 2개 추가 | - |


소비전력 측정은 X4-LIFE INSPECTOR II KD-302KR 로 했다.



### 1.2 OS 검토

우분투 ubuntu-22.04.1-desktop-amd64.iso 로 설치한다.


### 1.3 USB 설치 미디어 준비

http://mirror.kakao.com/ 에서 ubuntu-release 저장소로 가서 다운로드 받는다.

ISO 파일 이지만, ODD 로 DVD 를 굽지 않고, USB 메모리로 설치 미디어를 만든다.

https://webnautes.tistory.com/1146

https://rufus.ie/ko/

rufus 를 통해 부팅 USB 를 만들 수 있다.

ISO 파일이 거의 4GB 에 가까워, 4GB 이상의 USB 메모리를 사용한다.




## 2. 설치(2022.12.17)

