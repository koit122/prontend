# OMDb API
## 목차
1. <a href="#목차1">OMDb API란</a>
1. <a href="#목차2">필요성</a>
1. <a href="#목차3">사용법&특징</a>
1. <a href="#목차4">질문</a>

<a id="목차1"></a>

# OMDb API란
* OMDb API는 영화 데이터를 요청하는 API이다.

<a id="목차2"></a>

# 필요성

<a id="목차3"></a>

# 사용법&특징
1. <a href="#사용법+특징1">사용법</a>
1. <a href="#사용법+특징2">특징</a>
1. <a href="#사용법+특징3">Parameters(매개변수)</a>

<a id="사용법+특징1"></a>

## 사용법
[접속해서 확인](https://www.omdbapi.com/)
1. google 검색창에 OMDb API 검색
1. Usage에서 Query String(쿼리 스트링) 확인<br>
http://www.omdbapi.com/?apikey=[yourkey]&<br>
(omdbapi는 기본적으로 사용자 인증을 통해야만 apikey를 제공한다.)
1. Parameters에서 사용할 수 있는 속성값을 확인 후 사용<br>

<a id="사용법+특징2"></a>

## 특징
1. Query String형식으로 요청시 JSON포멧 형식으로 브라우저에 출력한다.

<a id="사용법+특징3"></a>

# Parameters(매개변수)
1. <a href="#Parameters1">By ID or Title</a>
1. <a href="#Parameters2">By Search</a>

<a id="Parameters1"></a>

## By ID or Title

<a id="Parameters2"></a>
parameter(매개변수) | Required(필수) | Valid Options(유효한 옵션) | Befault Value(기본 값) |Description(설명)
|--|--|--|--|--|
### By Search
parameter(매개변수) | Required(필수) | Valid Options(유효한 옵션) | Befault Value(기본 값) |Description(설명)
|--|--|--|--|--|
<a href="#By Search1">s</a>|Yes||```<empty>```|영화 이름 검색


<a id="By Search1"></a>

### s
>**기능**
>
>영화 이름을 검색해 이름에 부합하는 데이터를 가져온다.
>
>**선언방식** 
>```javascript
>브라우저 검색창
>https://www.omdbapi.com/?apikey=7035c60c&s=Oldboy
>브라우저 창에 출력되는 내용
>{"Search":[{"Title":"Oldboy","Year":"2003",>"imdbID":"tt0364569", ...
>(중략)
>"totalResults":"10","Response":"True"}
>```
>**반환값 :** JSON 데이터 포맷 형태
>
>**특징**
>1. 브라우저에 데이터를 출력하는 방식으로는 해당 데이터를 활용할수가 없음으로 프로젝트에서 http의 요청을 처리해주는 패키지인 axios를 같이 사용한다.
>
---
<a id="목차4"></a>

# 질문
1. <a href="#질문1">질문1</a>

<a id="질문1"></a>

>### 질문1
>* 질문1에 대한 설명