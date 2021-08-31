# -둘째마당

<주요내용>
 1. HTML기본문서는 반드시 필요한 모든 구조가 포함되어 있다. 웹문서는 보통 웹문서의 유형을 지정하는 선언문인<!DOCTYPE html>태그로 시작해 
 웹문서의 시작을 알리는<html>태그,웹 브라우저에 문서 정보를 알려주는<head>태그,웹 브라우저에 내용을 표시하는<body>라는 3개의 영역으로 구성되어있다.
 2.HTML 새 파일을 만들때는 폴더를 우선 선택하고, 새로운 파일을 만들대는 .html 이라는 확장자를 붙여야 비주얼 스튜디오 코드에서 웹 문서를 작성할때 편리하다.
 3.시맨틱 태그란, 웹문서 구조를 만드는데 필요한 태그인데 이 태그가 없어도 웹문서를 만들지 못하는 것은 아니다. 하지만 이 태그를 사용하면 어느부분이 제목이고, 메뉴이고,
 본문인지 쉽게 파악할 수 있다. 또 문서 구조가 정확히 나누어지므로 보다 더 정확한 내용을 전달할 수 있다.
 4.제목을 나타낼때는 <hn>태그를 사용해서 다른 텍스트보다 크고 진하게 표시할 수 있다. h태그 뒤의 숫자 순서로 크기가 작아진다.
 5.줄을 바꿀때는 <br>태그를 사용해서 줄바꿈을 할 수 있다.
 6.순서가 있는 목록을 만들때는 <ol>태그와 그 속에 <li>태그를 삽입해서 표시할 수 있다. 반대로 순서가 없는 목록을 만들때는 <ul>태그와 그 속에 <li>태그를 삽입해서 표시한다.
 7. html에서 중요한 표 만들기에서는 먼저 <table>태그로 감싸주고 표제목을 <caption>태그로 감싸 표시한다. 각각의 행은<tr>태그, 열은<td>태그로 표시할 수 있다.
 8.테이블에서 각 제목과 본문 그리고 요약(foot)부분은 <thead>, <tbody>, <tfoot>을 삽입해서 표현할 수 있다.
 9.테이블의 행이나 열을 합칠때는 행을 합칠때 사용하는 <rowspan>태그와 열을 합칠때 사용하는 <colspan>태그를 삽입해서 나타낼 수 있다.
 10.html문서에 이미지를 삽입하고싶을때는 우선 가장 기본적인 <img>태그를 사용해 나타낼 수 있다. 가장 기본적인 형태는 <img src="이미지 파일 경로"="대체용 텍스트"> 이다.
   이미지의 크기를 조절하고 싶으면 width와 height 속성으로 크기를 조절할 수 있다.
  
 <가장 기본이 되는 html의 구조 소스>
  <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
  </head>
<body>
  <h1>프런트엔드 웹 개발</h1>
  <hr>
  <p>HTML</p>
  <p>CSS</p>
  <p>자바스크립트</p>
</body>
</html>
  
  ##느낀점##
  학교에서 기존에 html을 실습하고 또 나름대로 따로 공부를 했다고 생각했는데 이번에 gs실무교육을 통해서 정말 겉핥기만 했다는 생각이 들었다.
  내가 무엇이 부족하고 어떤점을 더 공부해야할지 깊이 생각해보게되는 시간이 되었다. 단기간에 이런 프로젝트를 한다는 점이 처음에는 
  막막하고 두려웠지만 짧은 시간안에 이걸 해내야한다는 생각으로 팀원들과 협동해서 해결해 나가다보니 완성을하고 수료도 하게되었다.
  솔직하게 gs라는 기업에 내가 들어간다면 더할나위없이 좋겠지만 개인역량과 마음가짐 또한 더 철저히 준비해야겠다고 느꼈다. 비록 들어가지 못하더라도
  이번 교육을 통해 내가 배워간것과 깨달은 점이 많아서 뜻깊은 시간이었고 추후에 이러한 교육이 또 진행된다면 또 참여하고싶다.
