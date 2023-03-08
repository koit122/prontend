# axios
[접속해서 확인](https://github.com/axios/axios)
## 목차
1. <a href="#목차1">axios란</a>
1. <a href="#목차2">필요성</a>
1. <a href="#목차3">사용법&특징</a>
1. <a href="#목차4">질문</a>

<a id="목차1"></a>

# axios란
* promise라는 js에서 사용할 수 있는 객체를 기반으로 하는 HTTP Client다 browser과 node.js에서 사용 가능하며, 한마디로
HTTP의 요청을 처리해주는 패키지이다.

<a id="목차2"></a>

# 필요성
* 필요성에 대한 내용

<a id="목차3"></a>

# 사용법&특징
1. <a href="#사용법+특징1">설치</a>
1. <a href="#사용법+특징2">axios 메서드</a>

<a id="사용법+특징1"></a>

## 설치
1. 터미널 환경에서 npm install axios

<a id="사용법+특징2"></a>

## axios 메서드
메서드|기능
|--|--|
<a href="#method1">get</a>| 웹의 데이터를 가져온다.

<a id="method1"></a>

### method1
>**기능**
>
>인수로 주소를 넣어주면 get메서드가 해당 주소로 접근으르 해서 해당 페이지의 정보를 가지고 와 프로젝트(main.js...등)에서 활용할 수 있도록 도와준다.
>
>**선언방식** 
>```javascript	
>import axios from 'axios'
>
>function fetchMovies(){
>  axios
>  .get('https://www.omdbapi.com/?apikey=7035c60c&s=Oldboy')
>  .then((response) => {
>    console.log(response)
>  })
>}
>
>fetchMovies();
>```
>** 코드 설명 **
>
>get메소드로 데이터를 가져와서 then으로 처리한다.
>get이 서버로 요청을해 응답을 받은 데이터를 then이라는 메소드의 콜백함수 내부에서 활용한다.
>
>**인수정보**
>인수 | 데이터 정보
>|--|--|
>
>**반환값 :** Array
>
>**특징**
>
---

<a id="목차4"></a>

# 질문
1. <a href="#질문1">질문1</a>

<a id="질문1"></a>

>### 질문1
>* 질문1에 대한 설명