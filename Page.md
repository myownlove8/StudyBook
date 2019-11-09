# Static Pages와 Dynamic Pages

![page][Image1]

### Static Pages
 - Web Server는 파일 경로 이름을 받아 경로와 일치하는 file contents를 반환한다.
 - 항상 동일한 페이지를 반환한다.
 - Ex)Image, html, css, javascript파일과 같이 컴퓨터에 저장되어 있는 파일들
 
 ### Dynamic Pages
 - 인자의 내용에 맞게 동적인 contents를 반환한다.
 - 즉, 웹 서버에 의해서 실행되는 프로그램을 통해서 만들어진 결과물 *Servlet: WAS 위에서 돌아가는 Java Program
 - 개발자는 Servlet에 doGet()을 구현한다.

[Image1]:./image/page_1.png
