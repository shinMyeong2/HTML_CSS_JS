DOM 접근 메서드

.getElementById("id명"); // id선택자로 접근, 반환값 하나
ex) document.getElementById("heading");

.getElementsByClassName("class명"); // class값으로 접근
ex) document.getElementsByClassName("bright");

.getElementsByTagName("태그명"); // 태그 이름으로 접근
ex) document.getElementsByTagName("p");

노드.querySelector(선택자); // 다양한 노드 제어 가능, 반환값 하나
ex) querySelector("#heading"); // id일 경우 앞에 # 사용

노드.querySelectorAll(선택자 or 태그); // 다양한 노드 제어 가능, 반환값 다수
ex) querySelectorAll(".bright"); // class일 경우 앞에 . 사용