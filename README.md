# JS

폼 요소와 컨트롤 요소 가져오기

DOM 메서드로 가져오는 방법

let menu = document.getElmentById("menu1);

let options = menu.getElmentByTagName("option");

querySelectorAll 메서드를 사용하면 성별 정보를 구하는 라디어 버튼 목록을 다음과 같이 가져올 수 있다

let inputs = document.querySelectorAll("#form1 input[type='radio']");

form 프로퍼티로 form 요소 가져오기

문서안의 form 요소 목록은 Document 객체의 forms 프로퍼티에서도 가져올 수 있다.
forms 프로퍼티 값은 HTMLCollection 객체이다. HTMLCollection 객체의 요소는 배열 요소의 인덱스는 물론 id 속성 값,
name속성 값으로 가져올 수 있다.
