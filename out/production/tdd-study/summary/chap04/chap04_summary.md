# TDD, 기능 명세, 설계

## 기능 명세
- 소프트웨어의 기능 명세는 다양한 형태로 존재한다.
- 설계는 기능 명세로부터 시작! 
- 기능 명세를 구체화하며 입력과 결과를 도출한다. -> 이 입려과 결과를 토대로 코드를 작성하게 된다.

## TDD와 설계
- TDD를 진행하며 일부 설계가 진행된다.
- 클래스 이름, 메서드 이름, 메서드의 파라미터, 리턴 값등이 테스트 중 설계가 된다.

## TDD와 설계 완급조절
- 테스트를 성공할 만큼만 코드를 구현해야했다. 설계도 마찬가지, 필요한 만큼만 설계하자.
> 미리 변경할 것을 대비한 코드를 설계하지말고, 필요할 때에 하라!
> 테스트를 하는데 필요한 정도만 설계를 하니 코드가 복잡해지는 걸 막을 수 있다. 그런데 객체지향의 사실과 오해 책에선 설계는 변경되지 않는 구조라고 하였는데,해당 구조는 미리 세우는게 낫지 않을까? 라는 의문이 생긴다.

## 기능 명세 구체화
- 기능 명세만으로 개발자는 모든걸 알수 없다. 기획자와 많은걸 얘기해보며 기능 명세를 구체화 하자
- 구체화된 기능명세는 바로 테스트 -> 구현 -> 리팩토링의 과정으로 바로 적용해서 적절히 테스트가 통과되는지 확인하며 개발하자.

## 느낀점
- TDD를 진행하며 기능 명세에 대한 입력과 출력인, 파라미터와, 리턴 타입 그리고 설계인 클래스 이름등이 만들어지는 걸 겪었다. 실제로 일부 설계가 테스트를 통해 코드적으로 구체화 되는 것이 TDD의 장점인 것같다. 테스트 전에 미리 모든 설계를 하는 것보단 더 쉬울 거라 느꼈다.
- 설계도 테스트를 진행하며 일부 만들어진다는게 신기했다. 클래스 이름이라던가, 메서드 이름, 그리고 파라미터와 리턴값등이 테스트를 하며 만들어 졌다. 실제로 난 구현을 한다음 테스트를 진행하며 검증을 할수 없어 리턴값을 수정한 적이 있다. 이런면에서 좋다고 생각 한다. 어차피 테스트로 확인해야 하니!
- 구체화 된 기능명세는 TDD를 통해 테스트 -> 구현 으로 검증한다는건 지금까지 TDD를 공부하면서 당연히 해야할 일이란 생각이 들었다. 그만큼 TDD에 대해 어느정도 이해를 한것 같다 느꼈다. 실제로 연습하는 것이 중요하다!