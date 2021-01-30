# DesignHouse

HTML과 CSS만을 이용해 간단한 웹 페이지를 만들어 보았습니다.

![DesignHouse](https://user-images.githubusercontent.com/61913417/106359968-4ffaae80-6359-11eb-9e06-58b487baf038.gif)

#### 공부
- @font-face
```
@font-face { 
	font-family: <a-remote-font-name>;
	src: <source> [, <source>]*; 
	[font-weight: <weight>]; 
	[font-style: <style>]; 
 }
```
a-remote-font-name : font 속성에서 폰트명(font face)으로 지정될 이름을 설정한다.  
(현재 프로젝트에서 abster)  
src : 원격 폰트(remote font) 파일의 위치를 나타내는 URL 값을 지정하거나, 사용자 컴퓨터에 설치된 폰트명을 local("Font Name")형식으로 지정하는 속성이다.  
(현재 프로젝트에서 url(font/abster-webfont.woff) format('woff')  
--> format : 이 형식을 지원하는 브라우저만 글꼴을 내려받는다.)  
weight : 폰트의 굵기(font weight) 값
style : 폰트 스타일(font style) 값
