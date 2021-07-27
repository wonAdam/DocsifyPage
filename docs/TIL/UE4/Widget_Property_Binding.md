[:calendar:20210727](/TIL/20210727)

# Widget Property Binding

인턴 과제를 하다가 팀내에서 만든 개발자 메뉴에 내가 만든 기능을 토글하는 기능을 추가하는 업무를 받았다.

그래서 여느때와 같이 개발자 메뉴에 다른 기능들을 참고해서 만드는데, 개발자 메뉴는 블루프린트를 적극 활용해서 만든 모양이었다.

토글을 하는 기능중에 위젯의 부모 C++ 클래스의 `bool` 변수를 특정 조건이 만족되면 어느때이건 알아서 바뀌게 하는 부분이 있었는데 이를 **프로퍼티 바인딩**이라고 하나보다.

[언리얼 도큐먼트](https://docs.unrealengine.com/4.26/ko/InteractiveExperiences/UMG/UserGuide/PropertyBinding/)에도 나와 있다. 

![Image of Yaktocat](./img/property_bind.webp)

위젯을 만들면서 종종 옆에 보이는 Bind 버튼이 무슨 역할인지 궁금했는데 이런 기능이었구만.
