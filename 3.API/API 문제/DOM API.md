# DOM API

## 목차
1. <a href="#목차1">DOM API란</a>
1. <a href="#목차3">DOM API 메서드</a>
1. <a href="#목차4">Document객체 메서드 </a>

<a id="목차1"></a>

# DOM API

## API란
* API는 Application Programming lnterface의 약어로  정의 및 프로토콜 집합을 사용하여 두 소프트웨어 구성 요소가 서로 통신할수 있게 하는 메커니즘 이다.  (javascript에서 파생된 계념은 아니다)
예를 들어 기상청의 소프트웨어 시스템에는 일일 기상 데이터가 있다. 휴대폰의 날씨 앱은 API를 통해서 이 시스탬과 **대화**하여 휴대폰에 일일 기상 데이터를 가져온다.

## DOM이란
* DOM 는 Document Object Model의 약어로 HTML, XML의 프로그래밍 인터페이스다.  
DOM은 원본HTML 문서의 객체 기반 표현 방식이다. 단순 텍스트로 구성된 HTML문서의 내용과 구조가 객체 모델로 변환되어 다양한 프로그램에서 사용될 수 있다는 점이 DOM과 HTML의 근본적인 차이이다. DOM의 객체 구조는 "노드 트리"로 표현된다.

## DOM의 역활
1. 문서의 구조화된 표현을 제공하여 프로그래밍 언어가 DOM구조에 접근할 수 있는 방법을 제공
2. 여러 프로그램들이  접근하여  문서 구조, 스타일, 내용 등을 변경 할 수 있게 돕는다.
3. 웹 페이지를 스크립트 또는 프로그래밍 언어들에서 사용할 수 있도록 연결 시켜준다.

## DOM API란
* 웹 문서와 스크립트,프로그래밍이 서로 통신을 할 수 있게 도움을 주는 API이다.

<a id="목차2"><a>

## DOM API 메서드

<a id="목차3"></a>
### Document객체 메서드
* 어떠한 HTML문서가 웹 페이지에 로드될 때, 해당 HTML문서가 바로 
Document객체이다.  
Document객체는 HTML의 root node이기도 하다.  
대표적인 API는 아래와 같다.

|메소드/속성  |기능  |
|--|--|
|getElementById("id")  | 매개변수로 받은 값을 id로 가진 Element를 반환해준다. |
|getELementByClassName("class")|매개변수로 받은 값을 class로 가진 Element를 반환해준다.
|querySelector()| 매개변수로 css의 지시자를 받고, 이 지시자와 일치한 첫번째 Element를 반환한다.
[나머지 부분 ]([DOM Node 조작해보기(DOM API) :: Ratel의 개발일지 (tistory.com)](https://straw961030.tistory.com/116))
