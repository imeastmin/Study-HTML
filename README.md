# 웹 표준 기술
## __*HTML5*__
### **기본태그**
< h1~h6 > : 제목  
< hr > : 구분선  
< br > : 줄 간격  
< align > : 정렬  
< p > : 문단 나누기  
< width > : 가로 길이  
< height > : 세로 길이  
< size > : 크기  
< color > : 색상(RGB코드)

<hr>
<br>  

### **~~폰트~~**  
<i>HTML5에선 잘 사용하지 않는다.</i>  
< font color > : 색 지정  
< font size > : 글자 크기  
< font face > : 폰트 지정

<hr>
<br>

### **이미지**
< img src = "PATH" > : 상대/절대경로 지정  
< img title >  

<hr>
<br>

### **하이퍼링크**
< a href = "URL" >  
< a href = "PATH"> : 다운로드  
< a href = "# id" > : 지정한 ID로 이동  

<hr>
<br>

### **테이블**
< table > : 테이블 생성  
< tr > : table row, 행 추가  
< td > : table data, 셀 추가  
< td colspan > : 셀 합치기  
< td rowspan > : 행 합치기  
< table border > : 테이블 선 두께  
< cellspacing > : 셀과 셀 사이의 간격 설정  
< cellpadding > : 셀 테두리와 내용과의 간격 설정  

<hr>
<br>

### **Form**
< form method > : get, post  
* GET 방식 : 데이터가 노출됨 - 보안에 취약
* POST 방식 : 주로 사용하는 방식  

< form action="" > : 액션 로직을 만들 때 사용  
< input type="" > : 타입 값에 따라 Form 양식이 생성됨  
< input value= > : 버튼이나 서밋 양식 등에 나타낼 표시 값  
< input maxlength= > : 글자 수 제한  
< input required="required" > : 빈 값을 허용하지 않음  
< input autofocus="autofocus" > : 자동으로 선택되는 기능  
< input placeholder > : 텍스트 입력 칸에 설명 글 기능

<br>  

* <b>Form Type</b>  
>radio : 단일선택 기능<b>(name 값을 설정해야 함)</b><br>
checkbox : 다중선택 가능<br>
select-option : 드롭다운 형식<br>
file : 파일을 첨부할 수 있는 기능 제공 <br>
button : 전송 기능이 없는 버튼<br>
submit : action 기능이 있는 버튼<br>
reset : 초기화 기능 버튼<br>
hidden : 웹 상에 표시되지 않는 값<br>
img : 이미지 버튼 생성<br>

<hr>
<br>

### **리스트**
< ul > : Unordering Line, 순서가 없는 리스트  
* < ul type = disc >  
* < ul type = circle >  
* < ul type = square >    

< ol > : Ordering Line, 순서 있는 리스트  
* < ol type = 1 >  
* < ol type = a >  
* < ol type = A >  
* < ol type = i >  
* < ol type = I >  

< li > : 리스트 추가  
<hr>
<br>  

### **텍스트**
textarea cols/rows : 문자입력 상자 생성  
readonly : 텍스트 수정을 거부  
disabled : 텍스트 수정을 거부
 > **readonly**는 값을 전달할 수 있지만 **disabled**은 값을 전달할 수 없다.
