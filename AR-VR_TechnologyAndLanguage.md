# AR / VR 개발을 위한 기술 및 언어  

**Augmented Reality (증강 현실) / Virtual Reality (가상 현실) 개발을 위해 필요한 지식들**

---

<img src="https://github.com/ChaeDoll/Presentation/assets/108540812/593c4755-a0db-4f91-b6e5-d532d9018082" width="60%">

---

### 기본적으로 필요한 능력

- 새로운 UX에 대한 이해 (User Experience - 사용자의 느낌, 태도, 행동을 설계하는 기술)
- 3D엔진에 대한 이해
- Java, C#, Swift, Javascript 등을 사용하여 상속, 추상화, 캡슐화와 같은 객체지향프로그래밍(OOP)을 사용할 수 있는 숙련도
- 보이지 않는 부분은 그리지 않도록 하는 최적화 능력  
+ Shader에 대한 이해가 있다면 시각적으로 훌륭한 효과 구현 가능  

### 현재 AR과 VR의 발전은 어디까지 이루어져 있는가?

- 흔히 AR(증강현실)의 대표격으로 ‘포켓몬 고’를 떠올림
- 현재 AR기술은 의료, 디자인, 관광, 교육, 군사 등 여러 분야에 걸쳐 발전 중
    
    *아래 사진은 AR기술을 사용한 네비게이션의 모습 (네이버)*
    <img src="https://github.com/ChaeDoll/Presentation/assets/108540812/f45750da-c07f-4bf8-9988-b9461f98ae91" width="35%">  
   
    *IVAS(통합 시각 증강 시스템)*
    <img src="https://github.com/ChaeDoll/Presentation/assets/108540812/2e526b64-9763-48a3-92fa-7ce47e802276" width="35%">  
    (지도, 나침반, 시야공유, 전장공유, 번역기, 조준/야간투시 기능, 열상 기능 등)  
    
- 인스타그램, 스노우 등 카메라를 사용하는 어플리케이션에 있는 필터
    
    *AR 기술을 사용한 카메라 필터는 유튜브 쇼츠, 인스타, 틱톡 등 널리 쓰이고 있다*
    <img src="https://github.com/ChaeDoll/Presentation/assets/108540812/5543fc46-c2d4-4657-b978-4a5f851397b4" width="35%">  
    
- VR은 시뮬레이션에 주로 사용 (스포츠, 군사, 의료 등)  
    <img src="https://github.com/ChaeDoll/Presentation/assets/108540812/c1d28f6c-20b4-4a6d-9812-774fee14a88e" width="35%">  
    
    <img src="https://github.com/ChaeDoll/Presentation/assets/108540812/0ceeb511-2a22-46a3-92d9-6dca7c2b2bd4" width="35%">  
    
    <img src="https://github.com/ChaeDoll/Presentation/assets/108540812/a6804e42-3f62-4aca-9dc4-6079f8cc9259" width="35%">  
    
- 몰입 체험형 게임 / 영상 관람

---

### AR / VR 개발에 사용되는 프로그래밍 언어, 기술들

- Spark AR - Javascript 기반 AR 콘텐츠 개발 키트 (인스타그램, 페이스북에서만 구동)
- ARKit, ARCore - 각각 애플, 구글이 만든 AR 개발 API (소프트웨어 빌드 및 통합 정의, 프로토콜 세트) , AR 엔진을 Native로 구현 가능하여 최고의 성능을 기대할 수 있음. 단, 플랫폼 마다(iOS/Android) 언어와 API가 다르기에 따로 만들어야 함
- Unity AR Foundation - 위 두 개를 하나로 합쳐 사용 가능하도록 개발하는 엔진. 두 엔진의 기능을 100% 발휘할 수는 없지만 C#언어 하나만으로 iOS, Android 두 가지 모두 사용가능한 개발 가능
- 8th wall - 웹에서 AR을 실행할 수 있도록 한 웹 AR API. 다만 웹에서 구현되다 보니 성능이 그리 좋지 않음
- WebXR - 위에 있는 8th wall의 성능을 대폭 개선한 개발 엔진. 앱과 유사한 수준의 성능을 기대할 수 있다. 아직 개발 단계에 있는 인터페이스.

---

### 내가 제일 관심을 가지고 있는 기술 → WebXR API

데스크탑, 스마트폰, VR기기, AR기기 모든 디바이스에서 접속할 수 있고 체험할 수 있음 ⇒ 
*반응형 웹을 상상하면 편하다!*

> API 란? Application Programming Interface의 약자로서 두 어플리케이션 간 통신에 사용되는 언어나 메세지를 의미한다. 여기에서는 사용자(디바이스)와 가상공간(소프트웨어) 간의 연결을 의미하는 것으로 사용된다. 가상/증강현실 소프트웨어를 다양한 웹 디바이스에서 제어할 수 있도록 하는 것! 

웹 사이트 형태로 존재하는 가상/증강현실 소프트웨어를 제어할 수 있는 기술이 준비되었으니 이제 웹에 가상현실을 띄울 수만 있으면 된다.

- Babylon.js - Javascript 3D 엔진
- A-Frame - 웹에서 가상현실을 시작하는 Javascript Framework
- Three.js - 몰입형 환경을 위한 3D 라이브러리
- WebGL - 웹그래픽라이브러리를 통해 별도 플러그인을 사용하지 않고도 웹에 고성능 3D, 2D 그래픽을 렌더링 할 수 있는  Javascript API
