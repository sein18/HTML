# HTML

* __html__

  : 웹에서 정보를 표현할 목적으로 만든 마크업 언어(Hyper Text Markup Language)

   웹 페이지를 작성하기 위해 사용되는 언어로 웹 브라우저에게 보일 문자열과 이를 감싸는 일종의 해석기호인 태그들로 이루어짐

* __특징__

  * 구조적 설계 지원(시멘틱)
  * 그래픽 및 멀티미디어 기능 강화
  * CSS3 및 Javascript 지원
  * 다양한 API 제공
  * 모바일 웹 지원 및 장치 접근 가능(배터리 정보, 카메라, GPS 등)
  * 웹 브라우저가 서버와 양방향 통신 가능
  * 인터넷이 연결되지 않은 상태에서도 애플리케이션 동작

* __구성요소__

| __구성요소__           | __내 용__                                                    |
| ---------------------- | ------------------------------------------------------------ |
| 태그(Tag)              | ‘< ‘와 ‘>’로 묶인 명령어 시작태그(<태그>)와 종료태그()를 한쌍으로 이용 |
| 요소(Element)          | 시작태그와 종료태그로 이루어진 모든 명령어 하나의 HTML문서는 요소들의 집합 |
| 속성 (Attribute)       | 요소의 시작태그에만 사용 / 명령어 구체화 역할 여러 개의 속성을 사용할 수 있으며 속성의 구분은 공백 |
| 변수/속성값 (Argument) | 속성이 가지는 값, 값 입력 시 “ ” 혹은 ‘ ’를 이용             |

---

* __기본구조__

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

---

* __블록 요소, 인라인 요소__

```HTML
<!-- 블록 요소 -->
<p></p>
<div></div>
<!-- 인라인 요소 -->
<a></a>
<q></q>
<span></span>
```

---

* __글자 관련 태그__

```html
<h3>그 밖에 택스트를 다루는 태그들</h3><br>
<strong>글자를 굵게 표시하는 태그</strong><br>
<b>글자를 굵게 표시하는 태그</b><br><!--단순히 사용-->
<em>글자를 기울이는 태그</em><br>
<i>글자를 기울이는 태그</i><br><!--단순히 사용-->
<blockquote>인용 문구를 나타내는 태그</blockquote>
<q>인용 문구를 나타내는 태그</q><br>
<mark>형광펜 효과를 나타내는 태그</mark><br>
<u>글자에 밑줄 긋는 태그</u><br>
<small>글자를 작게 표시하는 태그</small><br>
기본 글자에 <sub>아래 첨자</sub>를 나타내는 태그와 <sup>윗첨자</sup>를 나타내는 태그.<br>
<s>글자에 취소선을 넣는 태그이다.</s>
```

---

* __리스트__

```html
<ol></ol> <!-- 순차적 -->
<ul></ul> <!-- 비순차적 -->
<!-- 기본형태 -->
<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>
```

---

* __이미지링크__

```html
<!-- 기본형태 -->
<img src="image/img01.png" width="200px" height="250px" alt="미니언즈" >

<!-- 이미지에 링크걸기-->
<a href="html01_block_inline.html">
   <img src="image/img01.png" width="200px" height="250px" alt="미니언즈" >
</a>
```

---

* __테이블__

```html
<!--
<table> : 기본적인 표를 생성.
<tr> : 표의 행을 나타내는 태그
<th> : 표의 제목 셀을 나타내는 태그
<td> : 표의 일반 셀을 나타내는 태그
-->

<table border="1">
     <tr>
         <th>컬럼01</th>
         <th>컬럼02</th>
     </tr>
     <tr> 
         <td>01</td>
         <td>02</td>
     </tr>
     <tr>
         <td>03</td>
         <td>04</td>
     </tr>
</table>
```

