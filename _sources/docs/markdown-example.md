# markdown 예시

깃허브 페이지는 markdown 문서를 지원합니다. 

아래와 같은 예시 코드를 입력하면 markdown 문법이 적용됩니다. 

<pre>
<code>
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

그림의 경우 다음과 같이 넣어주세요
![타이틀](../pics/PseudoLab_logo.png)
pics 폴더에 이미지를 넣어주세요.

깃허브 사용이 편하신 분들은 내용이 들어있는 md 파일을 docs에 넣고,

이미지 파일을 pics에 넣어주세요.

그리고 book 폴더에 있는 _toc.yml에 md 파일(파일이름이 addition_md.md라고 한다면)을 추가해주세요.

format: jb-article
root: intro
sections:
- file: docs/markdown-example
- file: docs/addition_md

그리고 pull request 해주세요. 제가 확인 후 merge 하겠습니다.

사용이 어려우신 분들은 md 파일과 이미지 파일을 제게 주세요.

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
</code>
</pre>

입력 결과

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

그림의 경우 다음과 같이 넣어주세요
![타이틀](../pics/PseudoLab_logo.png)
pics 폴더에 이미지를 넣어주세요.

깃허브 사용이 편하신 분들은 내용이 들어있는 md 파일을 docs에 넣고,

이미지 파일을 pics에 넣어주세요.

그리고 book 폴더에 있는 _toc.yml에 md 파일(파일이름이 addition_md.md라고 한다면)을 추가해주세요.

format: jb-article
root: intro
sections:
- file: docs/markdown-example
- file: docs/addition_md

그리고 pull request 해주세요. 제가 확인 후 merge 하겠습니다.

사용이 어려우신 분들은 md 파일과 이미지 파일을 제게 주세요.

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b