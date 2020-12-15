# 암호화

암호화 작업을 통해서 암호화 복호화 하는 작업을 알아보자

## 단방향 암호화

hash 알고리즘 이라고도 하는데 , 

<img src="./gitImages/hashAlgorithm.png" />

위 사진과 같이 단순히 데이터를 넣어서 암호화만을 시킬 뿐 다시 복호화를 시키진 않는다.

데이터의 <b>무결성</b>을 유지하기 위하여 필요한 암호화이다.

## 양방향 암호화

대칭키 방식이라고도 하는데 

해당 <a href="https://aesencryption.net/">사이트</a> 에 들어가서 예를 보면,

<img src="./gitImages/enc.jpg" />

해당 텍스트를 128 Bit 로 MyPassword 라는 키와 같이 암호화 시키면

<img src="./gitImages/enc_result.jpg" />

가 나오며 이 결과를 바탕으로

<img src="./gitImages/dec.jpg" />

이 텍스트를 위와 같은 조건에서 복호화 시키면

<img src="./gitImages/dec_result.jpg" />

가 된다.


