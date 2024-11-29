# Spring MVC

Spring MVC는 Model-View-Controller로 대부분 애플리케이션을 개발할 때 사용하는 패턴이다.
* 개발할 때 UI 영역과 비즈니스 영역을 구분하여 서로에게 영향을 주지 않으며 독립적으로 개발과 유지보수 가능하다.
* MVC의 Model은 비즈니스 영역 즉 데이터를 다루고 View는 Client에게 보이는 인터페이스를 뜻한다.
* Controller는 Model, View 사이의 상호작용을 구현한다.

  
## MVC 패턴을 사용하는 이유

Client에게 보이는 인터페이스와 데이터 처리 영역이 밀접하게 결합되면 유지보수가 힘들어진다. 독립적으로 개발되면 MOdel과 View는 각각 자신의 역활에 집중할 수 있으며 중복되는 코드를 줄여준다.

## Model

Model은 클라이언트의 요청을 전달받아 처리하는 작업을 한다. 처리한 데이터를 Client에게 돌려주는 작업을 하는데 이 데이터를 Model이라 한다.

## View 

View는 Model의 데이터를 이용하여 Client에게 화면에 보이는 Resource를 보내준다. 대표적으로 HTML 페이지, XML, JSON 등 특정 포멧으로 변환해서 보내준다.

## Controller

Controller은 Client의 요청을 직접적으로 받아 Model과 View 중간에서 상호작용한다. Client의 요청을 받아 비즈니스 로직을 거친 Model 데이터를 View로 전달하는 역활은 한다.

이러한 상호작용을 MVC 패턴이라 한다.
