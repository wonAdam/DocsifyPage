# Widget Event로 Lambda를 넣을 순 없을까?

인턴 과제를 하다가 Widget Event에 Lambda를 넣으면 우아하게 해결될만한 일이 있었다.

하지만 검색 결과, 불가능 한 것 같다.

참고한 자료는 [UE4 Answerhub](https://answers.unrealengine.com/questions/198488/is-there-a-way-to-add-a-lamda-to-the-umg-widgets-e.html)이다.


> No plans - UMG's available delegates are dynamic delegates, which means they are ScriptDelegates under the hood. ScriptDelegates can only callback to UFunctions on UObjects, which precludes using them for lambdas.

내부적으로 ScriptDelegate를 사용하고 있고 이는 UFunction이어야만 하는 것 같다.

> ## 결론은 Lambda를 못 사용한다.