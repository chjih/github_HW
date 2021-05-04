# ***Markdown 사용 방법 (Basic Syntax)***

<br>

# - **목차**

15. 이미지 (Images)
16. 이스케이프 문자 (Escape Literal)
17. HTML
18. GitHub Flavered Markdown (GFM) 사용 방법

<br>
<br>
<br>
<br>
<br>
<br>

# **2. 단락 (paragraphs)**

## - 사용 방법

- 빈 줄을 사용하여 하나 이상의 텍스트 줄을 구분해야 함

### *예)*

    첫 번째 문단입니다

    두 번째 문단입니다.

### *<출력 결과>*
---

첫 번째 문단입니다.

두 번째 문단입니다.

---

<br>

- 단락이 목록에 없으면,  공백이나 탭으로 문단을 들여쓰지 않는다.

### *예)*

        이로 인해 예기치 않은 포맷 문제가 발생할 수 있습니다.

      문단 앞에 탭이나 공백을 추가하지 마십시오.

<br>
<br>
<br>

# **3. 줄 바꿈 (Line Breaks)**

## - 사용 방법

- 두 개 이상의 공백으로 줄을 끝냄<br>
- 혹은 \<br> 사용

### *예)*

    첫 번째 줄입니다.  //공백 두개
    두 번째 줄입니다.

    첫 번째 줄입니다.<br>
    두 번째 줄입니다.

### *<출력 결과>* 

---
첫 번째 줄입니다.  
두 번째 줄입니다.

첫 번째 줄입니다.<br>
두 번째 줄입니다.

---
<br>
<br>
<br>

# **4. 강조 (Emphasis)**

- 굵게(Bold) 또는 기울임(Italic)으로 강조 할 수 있음

## 1. *Bold (굵게)*
<br>

### - 사용 방법

- 구문 앞 뒤에 두 개의 별표(**) or 밑줄(__) 추가  
- 중간 단어를 강조하려면 두 개의 별표 사용

### *예)*

    I just love **bold text**.  
    I just love __bold text__.  
    Love**is**bold

### *<출력 결과>*
---
I just love **bold text**.  
I just love __bold text__.  
Love**is**bold

---
<br>

- 이 때, 단어 중간에 있는 것을 강조를 할 때 '__' 사용하면 안 됨  

### *예)*

    Love**is**bold (o)
    Love__is__bold (x)

<br>
<br>

## 2. *Italic (기울기)*
<br>

### - 사용 방법

- 구문 앞 뒤에 한 개의 별표(*) or 한 개의 밑줄(_) 추가
- 단어 중간에 사용 시 문자 주위에 공백없이 별표 추가  

### *예)*

    Italicized text is the *cat's meow*.  
    Italicized text is the _cat's meow_.
    A*cat*meow.

### *<출력 결과>*
---

Italicized text is the *cat's meow*.  
Italicized text is the _cat's meow_.  
A*cat*meow.

---
<br>

- 이 때, 단어 중간에 있는 것을 기울릴 때 '_' 사용하면 안 됨
### *예)*

    A*cat*meow. (o)
    A_cat_meow. (x)

<br>

## 3. *Bold and Italic (굵은 기울임)*
<br>

### - 사용 방법

- 단어나 구 앞뒤에 별표 or 밑줄 세 개 추가
- 단어 중간을 굵고 기울게 표시하려고 한다면 별표 세 개(***) 사용

### *예)*

    This text is ***really important***.  
    This text is __*really important*__.  
    This text is _**really important**_.  
    This text is ***really important***.  

### *<출력 결과>*

---

This text is ***really important***.  
This text is __*really important*__.  
This text is _**really important**_.  
This text is really***very***important.  

---

- 이 때, 단어 중간에 Bold and Italic을 사용 시 밑줄 사용하면 안됨
### *예)*

    This is really***very***important text. (o)  
    This is really___very___important text. (x)

<br>
<br>
<br>

# **5. 인용구 (Blockquotes)**

## - 사용 방법

- 단락 앞에 '>' 추가

### *예)*

    > Dorothy followed her through many of the beautiful rooms in her castle.

### *<출력 결과>*

> Dorothy followed her through many of the beautiful rooms in her castle.

## <br>*1. 여러 단락이 있는 인용구*

- '>' 단락사이의 빈 줄 추가

### *예)*

    > Dorothy followed her through many of the beautiful rooms in her castle.
    >
    > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### *<출력 결과>*
<br>

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## <br>2. *중첩 인용구*

- 중첩하려는 단락 앞에 '>>' 추가

### *예)*
    > Dorothy followed her through many of the beautiful rooms in her castle.
    >
    >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### *<출력 결과>*
<br>

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## <br>3. *다른 요소가 있는 인용구*

<br>

- 인용구는 다른 마크 다운 형식의 요소를 포함할 수 있다.  
- 하지만, 모든 요소를 사용할 수 있지는 않는다.  
<br>

# **6. 목록 (Lists)**

- 정렬 된 리스트과 정렬되지 않은 리스트로 구성 가능

## 1. **정렬된 리스트 (Ordered Lists)**  

### - 사용 방법

- 숫자 + '.'  
- 숫자는 숫자 순서일 필요는 없음 (단, 목록은 숫자 1로 시작해야함)

### *예)*

    1. First item
    2. Second item
    3. Third item
    4. Fourth item  

    <br>

    1. First item
    1. Second item
    4. Third item

### *<출력 결과>*
---
1. First item
2. Second item
3. Third item
4. Fourth item

<br>

1. First item
1. Second item
4. Third item
---

- '숫자)'도 사용 가능하지만, 호환성 측면에서 좋은 옵션이 아님 -> 마침표만 사용

<br>

## 2. **정렬되지 않은 리스트 (Unordered Lists)**

### - 사용 방법

- 대시 (-), 별표(*), 더하기(+) 기호 추가  
- 중첩된 목록 만들 시 하나 이상의 항목 더 들여씀

### *예)*


    - First item
    - Second item
    - Third item

    * First item
    * Second item
    * Third item

    + First item
    + Second item
    + Third item

    - First item
        -Second item

### *<출력 결과>*

---

- First item
- Second item
- Third item  

* First item
* Second item
* Third item  

+ First item
+ Second item
+ Third item

- First item
    - Second item
---
<br>

- 이 때, 호환성을 위해 동일한 목록에서 구분 기호를 혼합시켜 사용하지 말아야 함

### *예)*

    + First item
    - Second item
    * Third item

<br>

## 3. **목록에 요소 추가**

### - 사용 방법

- 목록의 연속성을 유지하면서 목록에 다른 요소를 추가하려면 공백 4개 or 탭 1개로 들여 써야 한다.

### 1) *단락*
<br>

#### *예)*

    - First item
        add paragraph
    - Second item

#### *<출력 결과>*
---
- First item

    add paragraph

- Second item
---

<br>
<br>

### 2) *인용구*
<br>

#### *예)*

    - First item
        > add Blockqoutes
    - Second item

#### *<출력 결과>*

---

- First item

    > add Blockqoutes

- Second item

---

<br>
<br>

### 3) *코드 블록*
<br>

#### *예)*

    - First item

            codeblock
        
    - Second item

#### *<출력 결과>*

---

- First item

        codeblock

- Second item

---

<br>
<br>

### 4) *이미지*
<br>

#### *예)*

    - First item

        ![flower](flower.jpg)

    - Second item

#### *<출력 결과>*

---

- First item

    ![flower](flower.jpg)

- Second item

---

<br>
<br>

### 5) *리스트*
<br>

#### *예)*

    1. First item
    2. Second item
    3. Third item
        - Indented item
        - Indented item
    4. Fourth item

#### *<출력 결과>*
---
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
---

<br>
<br>
<br>

# **7. 암호 (Code)**

## - 사용 방법

- 단어나 구를 코드로 표시하려면 ( ` (백틱))으로 묶어야 함  

### *예)*

    At the command prompt, type `nano`.

### *<출력 결과>*
---

At the command prompt, type `nano`.

---  

<br>
<br>
<br>

# **8. 백틱 탈출 (Escaping Backticks)**

## - 사용 방법
- 코드에 백틱이 포함되어 있는 경우 단어나 구를 이중 백틱( `` )으로 묶어 이스케이프 할 수 있음  

### *예)*

    ``Use `code` in your Markdown file.``


### *<출력 결과>*

---

``Use `code` in your Markdown file.``

---

<br>
<br>
<br>

# **9. 코드 블록 (Code Block)**

## - 사용 방법

- 블록의 모든 줄을 최소 4개의 공백 or 1개의 탭으로 들여 써야함  
(위의 예시 코드들이 들어있는 것이 코드 블럭으로 표현 된 것)  

### *예)*
    code block start

        code

    code block end

### *<출력 결과>*

---

code block start

    code

code block end

---

<br>
<br>
<br>

# **10. 수평 규칙 (Horizontal Rules)**

## - 사용 방법

-3 개 이상의 별표(***), 대시(---), 또는 밑줄(___)을 한줄에 단독 사용 (출력 결과는 모두 동일하게 보임)  
- 이 때, 호환성을 위해 수평 규칙 앞 뒤에 빈 줄을 넣어야 한다.

### *예)*

    put a blank before

    ---

    and after.

### *<출력 결과>*

---

<br>

put a blank before

---

and after.

<br>

---

<br>
<br>
<br>

# **11. 링크 (Links)**

## - 사용 방법

- 링크 텍스트를 괄호로 묶은 다음 바로 뒤에 URL을 괄호로 묶는다. 

### *예)*

    네이버로 연결 [NAVER](https://www.naver.com/)

### *<출력 결과>*

---

네이버로 연결 [NAVER](https://www.naver.com/)

---

<br>

## - **제목 추가 (Adding Titles)**

- URL 뒤 ("")로 묶어야함  
- 사용자가 링크 위로 마우스를 가져가면 설명이 표시 됨  

### *예)*

    네이버로 연결 [NAVER](https://www.naver.com/ "네이버로 이동합니다.")

### *<출력 결과>*

---

네이버로 연결 [NAVER](https://www.naver.com/ "네이버로 이동합니다.")

---

<br>
<br>
<br>

# **12. URL 및 이메일 주소 (URLs and Email Addresses)**

## - 사용 방법

- URL 또는 이메일 주소를 링크로 빠르게 전환하려면 '<'로 묶어야 함

### *예)*

    <https://www.naver.com/>
    <fake@example.com>

### *<출력 결과>*

---

<https://www.naver.com/>
<fake@example.com>

---

<br>
<br>
<br>

# **13. 링크 서식 지정 (Formatting Links)**

## - 사용 방법
- 링크 강조 가능 (* 사용)
- 코드로 표시할 시 괄호 안에 백틱 추가

### *예)*

    I love supporting the **[EFF](http://eff.org)**.  
    This is the *[Markdown Guide](https://www.markdownguide.org)*.
    See the section on [`code`](#code).

### *<출력 결과>*

---

I love supporting the **[EFF](http://eff.org)**.  
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

---

<br>

## - *유의할 점*

- 마크 다운 애플리케이션은 호환성을 위해 URL 중간의 공백을 %20으로 표현해야함

### *예)*

    [link](https://www.example.com/my%20great%20page)   //(o)

    [link](https://www.example.com/my great page)   //(x)

<br>
<br>
<br>

# **14. 참조 스타일 링크 (Reference-style Links)**

## *Reference-style Link* 란?  
- 마크 다운에서 URL을 더 쉽게 표시, 읽을 수 있게 해주는 종류의 링크  

<br>

## 1) **첫 번째 부분 서식 지정**
### - 사용 방법
- [링크 텍스트][링크를 가르키는 레이블(label)] 

### *예)*

    [hobbit-hole][1]
<br>

## 2) **두 번째 부분 서식 지정**

### - 사용 방법

- [레이블 이름]:링크의 URL (+"adding titles")  
- 마크 다운 문서의 아무 곳에나 배치 가능  
- 보통 미주나 각주에 사용

### *예)*

    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
    [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

<br>

## 3) **조합**
<br>

#### *예)*

    In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
    of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
    eat: it was a [hobbit-hole][1], and that means comfort.

    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

<br>

#### *<출력 결과>*

---

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

---

<br>
<br>
<br>

# **15. 이미지 (Images)**

## - 사용 방법
- ![텍스트](사진 경로 URL(+"adding titles"))

### *예)*

    ![Philadelphia's Magic Gardens. This place was so cool!](flower.jpg "This is flower")


### *<출력 결과>*

![Philadelphia's Magic Gardens. This place was so cool!](flower.jpg "This is flower")

## - **이미지 연결**
- 뒤에 (URL) 추가

### *예)*

    [![Philadelphia's Magic Gardens. This place was so cool!](flower.jpg "This is flower")](https://mbdrive.gettyimageskorea.com/image/main/?image_id=978049074)

<br>
<br>
<br>

# **16. 이스케이프 문자 (Escape Literal)**

## - 사용 방법

- 제일 앞에 ( \\ ) 추가  

### *예)*

    \* Without the backslash, this would be a bullet in an unordered list.

### *<출력 결과>*

---

\* Without the backslash, this would be a bullet in an unordered list.

---

<br>

- 백 슬래시가 없었으면 정렬되지 않은 리스트로 글이 표현된다. 

<br>

## - **탈출할 수 있는 캐릭터 (Characters You Can Escape)**
<br>

1. \\
1. `
1. \*
1. _
1. {}
1. []
1. <>
1. ()
1. \#
1. \+
1. \-
1. .
1. !
1. |

<br>

# **17. HTML**

- Markdown 응용 프로그램 사용 시 Markdown 형식의 텍스트에서 HTML 사용 가능  
- 마크 다운 구문보다 특정 HTML 태그를 선호하는 경우에 유용  
- 모든 마크다운 애플리케이션이 HTML을 지원하는 것은 아님 (확실한 것은 마크다운 프로그램의 설명서 확인)

- 빈 줄을 사용하여 블록 레벨 HTML 요소(예: \<div>, \<table>, \<pre>, \<p>)를 주변 컨텐츠에서 분리해야 함
- 형식 지정에 방해가 될 수 있는 탭이나 공백으로 태그를 들여쓰지 않도록 함

- 블록 수준 HTML 태그 내부에서는 Markdown 구문을 사용할 수 없습니다.  
- 예를 들어, \<p>\*italic\*과 \*\*bold**\</p>는 작동하지 않음

<br>
<br>
<br>

# **18. GitHub Flavered Markdown (GFM) 사용 방법**

- [GitHub repository URL](https://github.com/jihong5091/firtprj)