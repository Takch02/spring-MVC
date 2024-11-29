# Spring MVC

Spring MVC는 Model-View-Controller로 대부분 애플리케이션을 개발할 때 사용하는 패턴이다.
* 개발할 때 UI 영역과 비즈니스 영역을 구분하여 서로에게 영향을 주지 않으며 독립적으로 개발과 유지보수 가능하다.
* MVC의 Model은 비즈니스 영역 즉 데이터를 다루고 View는 Client에게 보이는 인터페이스를 뜻한다.
* Controller는 Model, View 사이의 상호작용을 구현한다.

  
## MVC 패턴을 사용하는 이유

Client에게 보이는 인터페이스와 데이터 처리 영역이 밀접하게 결합되면 유지보수가 힘들어진다. 독립적으로 개발되면 MOdel과 View는 각각 자신의 역활에 집중할 수 있으며 중복되는 코드를 줄여준다.

## Model

