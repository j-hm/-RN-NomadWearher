# ReactNative

 * ReactNative를 배우기로한 이유
 	: 쓰고 싶은 앱이 있는데 마땅한게 없어서 내가 만들기로 함
 * 2022.03.13
 * expo로 스마트폰(디바이스)으로 바로 확인할 수 있다는 점이 마음에 들었다. 안드로이드 스튜디오와 비교하며 공부하게 될 것 같음.

## NomadCoder 강의

 * react native rules
    - 모든 텍스트는 ```<TEXT>```안에서
    - div는 ```<VIEW>```안에서
    - REACT NATIVE는 브라우저가 아닌 개발자가 앱을 만들기 편하게 하는 인터페이스다
 * layout system
    - flex-row설정으로 인해 화면에 overflow가 생겨도 스크롤 할 수 없다. 이건 브라우저가 아니기 때문.
    - 웹과 달리 flex의 기본값이 ```column```이다.
    - width, height를 사용하지 않을 것이다. 스크린 사이즈에 따라 맞춰야 하니까.
    - 대신, flex를 이용해 비율을 사용한다.
    - 부모 flexbox가 중요하다. 자식 flexbox의 비율을 계산하는 기준이 된다. (정확하게 이런 의미는 아닌 것 같은데. 아무튼.)