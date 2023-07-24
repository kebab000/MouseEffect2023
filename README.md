# JAVASCRIPT : MOUSE EFFECT

![mouse01](https://raw.githubusercontent.com/kebab000/MouseEffect2023/main/img/mouseEffect.png)

<br><br>

> View Site : https://kebab000.github.io/web2023/javascript/mouse/mouseEffect01.html

<br><br>

마우스 이펙트로 상호작용하는 웹 페이지를 만들었습니다. 이 웹 페이지는 자바스크립트를 활용하여 마우스 움직임에 반응하는 흥미로운 효과들을 구현했습니다.마우스 커서를 움직이면 배경이 흔들리고, 오브젝트들이 부드럽게 이동하며, 각종 그래픽 요소들이 마우스 포인터를 따라 움직입니다. 마우스 휠 스크롤에도 반응하여 페이지가 부드럽게 스크롤되는 효과를 추가했습니다.
이 프로젝트에서 javascript 메서드 위주로 학습하였습니다.
<br><br>

## 사용 스택과 메서드
- HTML: HTML 언어를 사용하여 웹 페이지의 구조와 콘텐츠를 정의합니다.
- CSS: CSS(Cascading Style Sheets)를 사용하여 웹 페이지의 스타일을 지정합니다.
- javascript :
  - window.addEventListener: 윈도우 객체에 이벤트 리스너를 추가하는 메서드로, 특정 이벤트가 발생할 때 실행될 함수를 등록합니다.
  - event.clientX: 마우스 포인터의 X 좌표를 반환하는 속성입니다.
  - event.clientY: 마우스 포인터의 Y 좌표를 반환하는 속성입니다.
  - element.getAttribute(): 지정된 속성의 값을 가져오는 메서드입니다. 이 코드에서는 span 요소의 class 속성 값을 가져오기 위해 사용되었습니다.
  - querySelectorAll(): 주어진 선택자에 해당하는 모든 문서 객체를 NodeList 형태로 반환하는 메서드입니다.
  - forEach(): 반복

<br><br>

## 구현 내역

* 마우스 따라다니기
* 마우스 오버
* 조명 효과
* 배경 움직이기1
* 배경 움직이기2