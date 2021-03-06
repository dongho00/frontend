# frontend

## 참고링크

선생님 작성 (복습) https://github.com/edu-ministori/frontend_08

https://www.w3schools.com/

https://codesandbox.io/s/itac-08-0ye9v?file=/page.html

## HTML

### Introduction

https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시

> 웹 페이지 콘텐츠
>
> - 텍스트 콘텐츠
> - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오

### html Element

https://www.w3schools.com/html/html_elements.asp

`(backtick)

```
<tagname>contents</tagname>
* 시작태그만 있는 경우 : Empty Element
```

> 포함관계(nested)

```
<html>
  <body>
    <h1>heading</h1>
  </body>
</html>
```

> html-body-h1 관계
>
> html = body와의 관계 - 부모요소 / h1과 관계 - 조상요소
>
> body = h1과 관계 - 부모요소 / html과 관계 - 자식요소
>
> h1 = body와 관계 - 자식요소 / html과 관계 - 자손요소

### HTML Attribute

https://www.w3schools.com/html/html_attributes.asp

### HTML Headings

https://www.w3schools.com/html/html_headings.asp

h1~h6 : 제목태그(h : heading) , h1 = the most important heading

### HTML Paragraph

https://www.w3schools.com/html/html_paragraphs.asp

### HTML LINK

https://www.w3schools.com/html/html_links.asp

a : anchor

> url (uniform resource locator) : 파일식별자(위치표시), 가장 넓은 의미의 인터넷 주소
> 인터넷 주소
>
> - IP(internet protocol) : 숫자로 구성된 주소 (192.168.2313)
> - Domain Name : www.naver.com / DNS(domain name server)
> - EX) blog.naver.com/blog/12314567 => URL

### HTML File Paths(경로)

https://www.w3schools.com/html/html_filepaths.asp

절대 vs 상대

- 경로 위치 표시 방식
- 경로 표시 기준의 변경 여부
- 절대 경로 방식
- ex) 대한민국 서울특별시 서초구 ~동 대호빌딩 803호
- 출발지 위치에 상관없이 항상 찾아갈 수 있도록 표시
- ex) 도메인 주소/상세경로 => https://www.naver.com/blog/bimage.jpg
-
- 상대 경로 방식
- ex) 강남역 11번 출구에서 3분
- 출발지 위치를 기준으로 표시
- ex) 상세경로 =>/blog/image.jpg || image.jpg

### HTML List

https://www.w3schools.com/html/html_lists.asp

> 중첩목록(Nested List)=포함되는 목록

### HTML Table

https://www.w3schools.com/html/html_tables.asp

table generator : https://www.tablesgenerator.com/html_tables

### HTML Images

https://www.w3schools.com/html/html_images.asp

alt : alternative

### HTML Video

https://www.w3schools.com/html/html5_video.asp

### HTML Youtube

https://www.w3schools.com/html/html_youtube.asp

### HTML Block & Inline

https://www.w3schools.com/html/html_blocks.asp

>영역의 특성
> - 블럭요소 : 가로길이 - 부모요소에 채워짐 / 세로길이 - 자식요소에 맞춰짐
> - 인라인 요소 : 가로길이와 세로길이 모두 자식요소에 맞춰짐

> 포함관계
>
> - 블럭요소 : 다른 블럭요소, 인라인 요소, 컨텐츠 포함 가능
> - 인라인 요소 : 다른 인라인 요소, 콘텐츠 포함 가능,블럭요소는 포함 불가능
> - 예외 : a - 인라인 요소이지만 블럭 요소를 포함 가능

### HTML Id & Class

https://www.w3schools.com/html/html_id.asp

https://www.w3schools.com/html/html_classes.asp

> id attribute
>
> - id로 붙혀주는 잉름은 한 html 문서 내에서 고유해야 함(한번만 사용)
> - id는 한 대상의 html Element에 하나의 이름만 지정할 수 있음

> class attribute
>
> - class로 붙여주는 이름은 한 html 문서 내에서 여러번 중복 사용할 수 있음
> - class는 한 대상의 html Element에 여러개의 이름을 지정할 수 있음
