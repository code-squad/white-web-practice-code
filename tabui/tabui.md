# tabui 만들기

이 작업을 위해서는 서버가 필요합니다.
 \> python -m SimpleHTTPServer 8000 등을 사용.

## 완성 UI
<img src="https://github.com/code-squad/white-web-practice-code/blob/master/tabui/result/tabui.jpg" width="600px;" style="border:1px solid gray;">

## 요구사항
- 그림과 같은 모습이 되도록 css 개발을 합니다.
- 탭 영역을 클릭하면 선택된 탭의 배경색이 변경됩니다.
- 탭 영역을 클릭하면 하단의 서버로부터 전달받은 콘텐츠가 표시됩니다.
- 탭마다 보여야할 콘텐츠 영역은 다릅니다.


## 각 탭에서 요청해야 할 서버 URL
http://jsonplaceholder.typicode.com/posts/1

http://jsonplaceholder.typicode.com/posts/2

http://jsonplaceholder.typicode.com/posts/3

http://jsonplaceholder.typicode.com/posts/4

## 화면에 보여야 할 콘텐츠 내용.
응답 데이터 중 title 과 body부분을 화면에 자유롭게 표시합니다