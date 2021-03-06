# Firebase 를 배워봅시다!

## What is Firebase?
Firebase 는 구글의 개발 플랫폼으로, 웹과 앱 개발을 위한 백엔드 구성을 손쉽게 할 수 있게 해준다. 뭘 쉽게 해준다는 걸까? 우선 일반적인 백엔드 개발을 살펴보자.

* **일반적인 백엔드 개발**

  1. 서버 인프라를 구성한다. (AWS 같은 클라우드 서비스에서 빌리든, 직접 하드웨어를 세팅하든)
  1. 인프라에 원하는 서버를 세팅한다. (Rails, Django, Flask, nodejs 등등 원하는 언어 및 프레임워크 사용)
  1. 계정관리, 데이터베이스, 이미지 처리, 특정 함수 등등.. 서비스에 필요한 기능들을 해당 서버에 개발하여 반영한다. 
  1. 서비스를 이용하는 유저가 많아져서 기존의 서버로 감당하기 어려워지면 서버를 증설하는 작업을 한다. 

물론 개발 방법이 하나로 정해져 있는 것이 아니라 다양한 방법이 있지만, 기본적인 흐름은 크게 달라지지 않는다. 그럼 이 방법을 따랐을 때 어떤 문제가 발생할 수 있을지 생각해보자. 

* **일반적인 백엔드 개발의 문제점**

  1. 어렵다. 경력자도 쉽지 않은데, 초보자는 이 모든 기능을 찾아서 반영을 해야한다는 데 부담감을 느끼고 중도 포기할 확률이 높다.
  1. 어찌 이 과정을 잘 따라했다고 해도, 본인의 코드에 확신을 가지기 어렵다. 로그인, 로그아웃과 같은 일반적인 계정관리를 생각해보자. 매우 당연하게 쓰는 기능임에도, 코드를 짜는 건 쉽지 않고 어찌어찌 짰다고 해도 내가 제대로 짰는지, 빠트린 건 없는지, 보안상 치명적인 결함이 없는지 고민하게 되고, 고민이 쌓일수록 포기도 빠르다. 
  1. 무엇보다 이 모든 게 우리가 **만들고자 하는 서비스**와 큰 관련이 없을 확률이 높다! 물론 서버의 역할이 큰 서비스도 많지만, 서버의 역할이 대단치 않은 경우가 더 많다. 내가 생각하는 서비스를 구현하는 데 집중하고 싶은데, 굳이 모든 백엔드 구성방법을 알아야할까? 

<img src="/images/giveup.jpg" width="500px">

## Why Firebase?
코딩을 한다고 꼭 개발자를 직업으로 삼을 필요는 없다. 정석대로 모든 백엔드 기술을 배우는 것은 물론 큰 도움이 되겠지만, 짧은 시간 내에 프로그래밍에 재미를 붙이려면 자신의 손으로 무언가를 만들어냈다는 성취감이 있어야 한다고 생각한다. 

Firebase 가 제공하는 다양한 도구들은 백엔드 부담을 확 줄여줄 뿐 아니라 Google 이 제공하는 만큼 잘 이용하면 오히려 스스로 모든 것을 만드는 것보다 더 안정적인 서비스를 만들 수도 있다. 인터넷으로 Firebase 에 들어가, 새로운 프로젝트를 시작하면 이런 탭이 보인다.

<img src="/images/firebaseTab.png">

* 탭의 항목을 잘 살펴보면, 서비스의 내용을 짐작할 수 있다. 

  1. Authentication (계정관리)
  1. Database(데이터베이스)
  1. Storage(이미지, 동영상 등을 위한 저장소)
  1. Hosting(호스팅)
  1. Functions(백엔드에서 처리할 함수들 설정 가능)
  1. ML kit(머신러닝 활용 서비스 제공)
  1. Analytics(내 서비스 현황분석) 

등등, 웬만한 서비스에서 필요한 대부분의 기능을 제공한다. 심지어 맨 아래에 얼핏 보이듯이, 어느정도의 이용수준까지는 이 모든 것이 Free, **공짜**다!


<hr style="margin-top: 45px;">

<DisqusNew />