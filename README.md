# Service Topic
친구 관리 프로그램 
# Data Fields
1. 이름 - 이름 입력 form
2. 관계 - ex) 친구, 교수님, 부모님, 동네친구, 학과 동기 등 관계적인 요소를 입력하는 form
3. 전화번호 - 전화번호 입력하는 form
4. 주소 - 주소 입력 form
5. 생일 - 생일을 입력함 input type을 date로 둬서 날짜를 선택할 수 있게 두었다.
6. 이메일 - 이메일 입력 form

# List Page
이름, 관계, 전화번호, 이메일 Feild를 넣었다.
상세보기 버튼을 누르면 view.html로 이동
새 친구 등록을 누르면 add.html로 이동
# Validation 
1. 이름 길이가 2글자 미만이면 이름을 써달라는 alert()
2. 관계 form이 공백이면 써달라는 alert()
3. 이메일에 @ 가 들어가지 않으면, 올바른 이메일 형식을 쓰라는 alert()
4. 생일을 선택하지 않으면 선택하라는 alert()
# RWD
미디어 쿼리를 사용하여, 화면이 768px이하인 경우 즉, 모바일인 경우 btn-mobile-full 을 적용하여 버튼의 가로 길이를 다 채워서 클릭에 편리하도록 함. 폰트 사이즈도 조절
# Bootstrap
1. Container,row,col같은 레이아웃 요소를 사용하였고, md sm등으로 마진 조절에 사용함. mx-auto요소를 사용하여 박스크기를 자동으로 조절되게 함. 
2. Card 클래스를 사용하여, 카드 형태로 친구의 정보를 화면에 띄우게 구성함.
3. form-label, form-control 으로 입력 form을 구성하고 form에 어떤내용을 입력해야하는지와 화면에 따른 폼크기를 자동 조절되게함.
4. button을 사용하여 primary,secondary와 같은 버튼 요소로, 다른 html파일로 이동하게 끔 구성함.
5. justify-content-between, align-items-center와 같은 요소를 사용하여, 화면 양끝으로 각 요소들을 밀어내거나, 요소들을 가운대로 모을 때 사용함. 
6. shadow-sm, rounded, bg-white와 같은 스타일 요소를 사용하여, 그림자를 주거나, 둥글게 모서리를 구성하거나, 배경색을 수정하는데 bootstrap 클래스를 사용함.
# Problem & Solution 
이번 과제를 수행하다가, 래이아웃을 수정해야하는 상황들이 자주 나왔는데, elements들을 양끝으로 밀어내거나 가운데 정렬을 하고 싶은 상황에 어떤 bootstrap 클래스를 사용해야하는지를 모르는 문제들이 생겼다. 이는 AI에 어떤 클래스를 사용하면 좋을지 조언을 구함으로써 해결함.
# Reflection
여러가지 부트스트랩의 클래스와 컴포넌트들을 익혀보고 정리할 수 있었으며, CRUD의 기본적인 구성을 익히고, java script로 validation을 수정하면서, alert()를 주면서 사용자가 올바르지 않은 값을 주어도 그것을 막는 구조를 익혔다.
