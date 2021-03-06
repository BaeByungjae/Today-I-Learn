# `1주차 Git Study`

<br>

## 1. `Git` vs `Github`

<img src="https://user-images.githubusercontent.com/45676906/95765769-46d3cc00-0ced-11eb-9f12-b12076bd500a.png">

<br>

`Git`과 `Github`의 차이를 간단하게 정리하면 아래와 같다. 

- `Git`은 분산 버전관리 시스템 도구

- `Github`은 Git을 제공하는 서비스 (Git의 데이터를 저장하는 서버)

<br> <br>

## 그러면 `버전관리 시스템`을 사용하는 이유는 무엇일까??

<img src="https://user-images.githubusercontent.com/45676906/95766359-1f313380-0cee-11eb-94a0-823bf3908608.png">

<br>

위와 같은 기능을 가진 버전 1을 내놓은 앱이 있다고 가정해보자. 다음 버전 1.1을 내기 위해 열심히 개발하여 버전 업데이트를 하였다. 그런데 만약에 
업데이트를 한 버전이 작동이 되지 않는다면 어떻게 할까? 거기에 이전 버전으로 되돌리수도 없다면,,?? 답이 없는 상황이 된다. 그래서 나온 것이 `VCS(Version Control System)`이다.

<br>

막막한 상황에서 시간이 지나 `VCS`를 이용하여 1.1버전을 성공적으로 출시했다. 그런데 만약에 코드를 저장하고 있는 서버가 터지게 된 상황이 왔다. 설상가상으로 현재 개발하고 있는
2.0 버전의 코드도 심각한 에러가 발생했다. 되돌려야 하는데 되돌릴 수가 없어서 난감한 상황이 되었다,,

<br>

그래서 위와 같은 상황이 되지 않기 위해서 개발자들이 이번에는 코드를 `백업` 해놓는 방법을 생각해냈다. 개발자들 각자의 로컬 PC에 서버로부터 코드를 저장해놓는 것이다. 그러면 나중에 
서버가 터지더라도 로컬 PC에 있는 코드를 다시 서버에 올려서 작업을 진행하면 된다. 

<br>

이렇게 여러 대의 컴퓨터와 하나의 메인 서버의 관계가 `Git(컴퓨터들)과 Github(서버)`의 관계이다. 코드가 서버에만 있는 것이 아니라
각자 로컬 PC에 분산되어 있기 때문에 `분산형 버전 관리 시스템(DVCS, Distributed VCS)`이라고 부른다. 
(그렇기 때문에 이제는 코드를 주고 받을 때도 USB에 담아서 or 프로젝트를 압축시켜서 메일이나 카톡으로 전달해줄 필요가 전혀 없다.)

<br>

이러한 기능들과 함께 `Git`의 아주 큰 장점 중에 하나인 `여러 사람이 동시에 개발을 하는 상황에서`도 매우 편리하다. `Git`을 사용하지 않고 각자 작업을 한 코드를 합치는
것은 매우 쉽지 않은 작업이다. 그냥 머리속으로만 생각해도 힘들 것 같다,, 그런데 `Git`을 사용한다면 알아서 코드를 합쳐주고 만약 충돌이 일어난다면 어떤 부분이 `충돌`이 일어나는 지를 보기 쉽게 알려주어 그 부분을 잘 해결할 수 있다.

<br>

<img src="https://user-images.githubusercontent.com/45676906/95769125-5bff2980-0cf2-11eb-853f-e2fe3c01bda6.png">

<br>

위에 사진은 `사용자들(컴퓨터)`와 `메인서버(Github)`의 관계인  `분산형 버전 관리 시스템(DVCS, Distributed VCS)`이라고 생각하면 된다. 


 
<br>

## 정리 

- 여태까지 개발해 온 이력을 확인해야 할 때

- 예전에 작업했던 상태로 다시 되돌려야 할 때

- 여러사람이 동시에 작업을 할 때 편리함

이것 말고도 여러가지 이유가 있지만 이러한 이유들로 인해서 `VCS(Version Control System`를 사용하는 것이다. 





