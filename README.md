# 도커를 사용하는 이유


## 운영하면서 만들어지는 눈송이 서버들(Snowflake Servers)

서버 운영을 오래 해 본 사람이라도, 처음 들어가는 서버에서는 마음 먹은 대로 문제를 해결하기가 어렵습니다.
 이는 서버를 다루는 기술과는 별개로, 각 서버마다 운영 기록이 다르기 때문입니다. 
 똑같은 일을 하는 두 서버가 있다 해도, A 서버는 한 달 전에 구성했고 B 서버는 이제 막 구성했다면, 
 운영체제부터 컴파일러, 설치된 패키지까지 완벽하게 같기는 쉽지 않습니다. 그리고 이러한 차이점들이 장애를 일으키고 말죠. 
 A 서버는 잘 되는데 B 서버는 왜 죽었지?와 같은 일(혹은 그 반대)이 벌어지는 겁니다. 
 이렇게 서로 모양이 다른 서버들이 존재하는 상황을 **눈송이 서버Snowflakes Server**이라고도 합니다. 
 모든 눈송이의 모양이 다르듯, 서버들도 서로 다른 모습이라는 말이죠.