# TIL
Today I Learned
* Create Git
* Create Category(TIL / Algorithum / Unity / Java)
* 6/28 Acon Academy 사전 OT
* 6/30 웹 서비스 기반 데이터 분석 및 자바 개발자 양성과정 교육 시작(html, css, javascript 강의(참고 URL:https://ofcourse.kr/css-course/cursor-%EC%86%8D%EC%84%B1))
* 수업 진행 게시판 : https://docs.google.com/document/d/1i7gQUmVn2FaSWVQRmiDY9_J5Y9o90QeMDUF6T_9SkJc/edit

---------------------------------------------------------------------------------------------------------------------------------------------------------------

## 훈련과정명 : 웹 서비스 기반 빅데이터 분석 및 개발자 양성과정
* 2022.06.28 - 사전OT 및 사전평가 진행 / 담당 매니저 : 조은미 팀장(02-538-3747)
* 2022.06.30 - 첫 등원(제 3 강의장) / 이정호 선생님(JAVA)
-------------------------------------------------------------------------------------------------------------------------------------------
* 강의 진도 순서(사용 개발툴 : visual studio code)
1. html, css, javascript(정보, 디자인. 동작언어)
2. oracle database
3. java
4. jsp
5. spring framework
6. vue
7. 마지막 2주는 중간 프로젝트
-------------------------------------------------------------------------------------------------------------------------------------------

### 2022.06.30

##### html, css, javascript

- html은 markup 언어(꺽쇄를 열고 닫는 것)
- element를 닫을때 / 사용안하면 중간에 넣을 요소가 없다는 뜻으로 해석(즉 단독으로 존재한다는 의미임.)
- 비주얼 코드 내에서 browser 열고 싶으면 alt+b 단축키
- h1 => h1(headline)이라는 element(요소)를 생성한다는 뜻
- headline은 최대 h6까지 생성 가능(단, 숫자가 늘어날때마다 폰트 크기는 점점 작아짐)


* 주석 : html - <!-- --> | css&javascript -  , /* */
- <!DOCTYPE html> => 이 문서는 html5 형식의 문서라고 웹브라우저에게 알리는 선언부
- html 문서는 head 요소와 body 요소로 구성된다.
- body 요소에는 주로 화면에 나타낼 요소를 작성한다.
- <script></script> => 여기에 작성한 javascript는 페이지 로딩시에 웹브라우저가 해석한다.


* alert 같이 개발자가 실행할 때 편하게 하도록 하기 위한 함수 : 빌트인 함수


- greet 라는 이름의 함수(기능) 만들기 -> 페이지 로딩시에 해석 x / 예약어 개념
로딩시에는 준비했다가 사용자가 특정 행위를 행했을 때 함수가 실행되도록 설정함!
콘솔에서 실행하여 함수를 표시할 수 있고 함수이름 + ()하면 실행됨.

- function은 함수 안에는 실행할 javascript를 작성할 수 있다.(미리 준비해 놓는 역할) (단, 함수를 로딩시에 실행시키면 작동을 하더라도 정상적인 작동이 아님.)

- xxx(attribute main/속성명)=""(attribute value/속성값) => attribute

-------------------------------------------------------------------------------------------------------------------------------------------

*  CSS에서 style을 지정해 줄때는 p, h1등은 그냥 바로 선언해주지만 id를 선언해줄때는 앞에 #이 붙어야함. (즉, 특정요소를 선택해서 선언해줄때는 #이 붙어야함.)

* id와 상관없이 그룹명으로 찾고 싶을 때는 앞에 .을 붙인다

* img 요소의 src 속성의 값으로는 로딩할 이미지가 위치한 경로를 적어놓으면 웹브라우저가 해당경로를 찾아서 이미지 데이터를 받아와서 화면상에 표시해 준다. alt 속성의 값으로는 이미지의 자세한 설명을 적으면 된다. img 요소는 인라인 요소이기 때문에 개행을 따로 해주지 않으면 한줄에 표기된다.
-> 쉽게 말해서 h1처럼 글자 입력 후 그림이 밑으로 내려오는 이유는 display에서 block으로 설정되어 있기 때문임. 단, 이미지는 이미지 출력에 필요한 공간만 확보되면 출력이 됨. 그림처럼 옆으로 한줄로 쌓이는 성격을 띔 => inline elemnet라고 함. 반대로 h1처럼 위에서 아래로 쌓이는 것은 block element라고 함.

*  id 속성은 특정 요소를 유일하게 식별하고자 할 때 사용하는 속성이다. 동일한 id 부여할 경우에는 markup 오류가 발생.
* class 속성은 특정 요소들을 같은 그룹으로 구성하고자 할 때 사용하는 속성이다.
* 선택자에서 띄어쓰기를 하면 자손 요소를 의미한다.

* span : 눈에 보이지 않지만 \n을 계속해서 해석해줌. 하지만 웹브라우저는 해석 x(스페이스바로 인식)

* b 요소는 단순히 굵은 글씨 / strong요소는 굵은 글씨 + 강조 의 의미도 가지고 있다.
* i요소는 단순히 이텔릭체 / em 요소는 이텍릭체 + 강조 의 의미도 가지고 있다
* inline 요소는 아무리 개입을 해도 한줄에 표기를 함

* ul : 순서 없는 목록(unordered list)
어떤 목록을 나타낼 때 문자열을 단순히 나열하는게 아니고 아래오 같이 구조화를 해서 나열해야 한다는 특징을 가지고 있음.
* ol : 순서 있는 목록(ordered list)
-> css영역에서 수정을 할 때 list-style-type는 목록 표시할 때 나타나는 숫자나 문양의 타입을 말하는 것임.


* dl : 정의형 목록(definition list)
-> dl 안에 dt & dd는 한 세트로 적용한다고 보면 됨. dd는 출력 시 왼쪽 마진만을 가지고 있는 것이 특징.

* table(표) 형식 정보를 출력하려고 할 시에는 약식과 정석이 존재.
* 약식

![image](https://user-images.githubusercontent.com/107795925/176635429-e25e40f9-7483-476a-a6bf-641898ff7be6.png)

* table 요소들을 사용한 정석

![image](https://user-images.githubusercontent.com/107795925/176635620-c3ef7644-a1fe-4cc1-a769-26f85909bb10.png)
            
* table border="" -> 표의 테두리선 굵기를 지정하는 것이다.
* 표의 제목은 caption에 명시해주면 됨.
* "<colgroup>" 은 column의 폭을 조절하는 함수로 내부에 width나 height를 설정해주면 됨.
* table의 자식 요소로는 thead, tbody, tfoot가 올 수 있다.

* tfoot : 최종으로 중요한 정보를 먼저 읽을 수 있도록 위로 올려주는 역할을 하는게 tfoot(tbody의 내용을 skip할 수 있음)
-> 시각적으로는 밑에 나오지만 body보다 먼저 읽어줌.

* column이나 row를 합칠 시에는 colspan OR rowspan 함수를 사용하면 됨.
           
![image](https://user-images.githubusercontent.com/107795925/176635714-9169cda4-7d10-481a-abe0-33309f15e98e.png)
                             
-------------------------------------------------------------------------------------------------------------------------------------------
* 참고 사항

- 1em = 16px
- block-start = top
- block-end = bottom

- body와 div는 부모와 자식 관계 / body와 img는 자손관계(단, img는 div와 부모자식관계여야 성립이 됨

- display에서 block<-> inline 서로 상반되는 개념


-------------------------------------------------------------------------------------------------------------------------------------------


### 20220701
            
##### html, css, javascript

* form 요소 - 서버에 전송할 양식을 일컫는다.
- form action 속성 : 입력한 내용이 어디로 보내지는지를 설명해주며 작성은 action="서버에 전송할 경로" / 단, 웹서버가 존재해야 웹브라우저에서 실행이 가능하다
* label의 for속성의 값과 input의 id속성의 값과 동일하게 작성되어야 한다. name 속성의 값은 서버에서 필요한 값이다.

![image](https://user-images.githubusercontent.com/107795925/176819105-4012a721-d9d3-4f36-8b92-60bf7439058b.png)

* 제출 버튼은 반드시 form 요소 안에 위치해야 함!
* 서버에서는 name 속성을 이용해서 서버에 어떤 정보가 입력됐는지 읽어내 구분함.
* input의 id 속성의 value는 label의 for 속성과 동일하게 부여해야한다.
            
* fieldset / legend 요소 : 정보를 선택할때 사용            
            
![image](https://user-images.githubusercontent.com/107795925/176819458-d63f192a-82dd-45fc-be88-79a03f8caab5.png)

- name속성의 value가 같으면 같은 그룹으로 묶이게 됨(같은 그룹으로 바뀌면 된다고 봐도 동일함            
- radio의 경우에는 따로 지정된 value값이 없으면 웹서버로 정보 전송이 불가함
- checkbox는 name속성의 value가 같아도 같은 그룹이기는 하나 복수 선택이 가능함(radio와 checkbox의 차이 알아둘 것) 
- option에 value가 없으면 innerText(요소 사이에 출력되는 text가 전송된다. (ex) 라면 쫄면 김밥 같은 한글로 적은 옵션을 뜻함
            
![image](https://user-images.githubusercontent.com/107795925/176819747-22c2ae81-f566-49b4-b43c-027deab4b5a8.png)

- input의 file 속성에서 본래 웹브라우저는 보안성때문에 파일시스템에 접근하는 것을 제한하지만 file타입을 사용하면 첨부파일 선택이 가능하다!

* html5에서는 추가된 form 요소들이 존재함(ex, color, range, date. time 등등)<br>
-> 웹브라우저의 종류와 버전별로 지원 가능과 불가능한 요소들이 존재<br>
-> 이는 caniuse.com에서 개발지원이 되는지 확인할 수 있다.
- 관련 링크 : "https://caniuse.com"
            
- input의 range 타입에서는 value값이 초기값으로 설정됨
            
* 폼 요소에 기본값 설정 : 서버에서 클라이언트에게 폼을 응답할 대 이미 저장된 값을 출력한 채로 응답을 해야할 때가 있다.<br>
  예를 들어 회원 가입된 정보 보기로 이동한다면 DB에 이미 저장된 내용을 출력해 주어야 한다.            
            
-  textarea의 초기값은 textarea의 innerText로 출력해놓아야 한다

* anchor : a로 단축키가 쓰이며 a(ancor) 요소는 하이퍼링크. 책갈피, javascript 등을 수행할 때 사용한다.<br>
inline 요소(폭을 필요한 만큼만)는 원래 block 요소(폭을 싸그리 사용)를 자식요소로 가질수 없다.<br>
단, a 요소만 예외적으로 div 같은 블럭요소를 자식요소로 가질수 있다.
            
![image](https://user-images.githubusercontent.com/107795925/176821922-f2696760-f326-4323-b201-dd658ededdbe.png)

            
- emmet.io 홈페이지에서는 html, css 등 markup language에서 사용가능한 편리한 단축키 목록들을 제공하고 있다.<br>
이는 visual studio에서도 적용된다.

- 특정 div를 가운데 정렬하는 방법<br>
1. width를 결정한다.(가운데 정렬을 하기 위해서는 폭값을 결정해야함)<br>
2. 좌우 마진을 auto로 설정하면 좌우 마진이 같게 설정되어 가운데 정렬이 된다.

* 책갈피 기능

![image](https://user-images.githubusercontent.com/107795925/176859665-79db907c-3aa3-40d2-8855-17143a6daf7b.png)<br>
anchor에서 속성값 부여할 때 #을 붙이면 id와 연결된다!

- 개발을 하다가 의미 없는 말들을 채워넣어서 화면을 구성해야 할때는 p선언 후 lorem 을 이용하면 됨

* anchor의 다른 기능<br>

![image](https://user-images.githubusercontent.com/107795925/176860736-6d563e3c-4557-4f77-b32b-9a188d5fedde.png)

-------------------------------------------------------------------------------------------------------------------------------------------

##### GIT & GITHUB
            
git-scm.com 들어가서 git 설치<br>
설치 후 명령 프롬포트 실행<br>
명령 프롬포트에서 c:\로 디레토리 변경 후 git 입력해서 설치 제대로 됐는지 확인<br>
            
untracked file은 아직 사진이 찍히지 않았다는 뜻<br>

commit 하면  working tree가 clean하다고 나옴<br>

git log하면 commit 내역 나옴(commit의 앞 7자리가 대표 일련번호)<br>

git add . 은 모든 변경사항을 다올리겠다는 얘기<br>
화면 높이 낮을 때는 엔터누르면 내려가고 q누르면 exit됨<br>

git reset --hard HEAD~ => 잘못쓴거 제거하는거(~모양은 몇단계를 내릴지 정하는 거임)<br>


HEAD는 커서다<br>

branch pointer = master<br>


이력이 추가될때 마다 master & head가 수정된 걸로 동시에 올라감(아래 그림처럼 실행이 됨)<br>
branch pointer는 여러개 생성이 가능(헤드만 옮기는 것으로 해결 가능)<br>



index <- master <- head<br>

            
v1 < master < head<br>
index<br>

v2 < master < head<br>
v1<br>
index <br>





다시 복구 시킬때는 로그 확인후에 해당 식별번호나 id명을 입력시켜줘야함<br>

로그 확인  : git reflog<br>
복구 명령어 : git reset --hard id명(HEAD@{2}) || git reset --hard 식별번호<br>

폴더 만들고 먼저 git init해도 됨.<br>


안전한 공간에서 실험을 하는 방법 : branch를 하나 더 만드는 방법(데모버전으로 실험하는 것) 아래 상황 참고<br>

              lab1 ->  v2 < master < head           이후 헤드(커서)를 lab쪽으로 올리고(얹히고) 성공하면 commit 후에 master에 반영<br>
                       v1<br>
                     index <br>

commit의 결과는 이렇게 됨.<br>

 head  -> lab1 ->  v3<br>
                   v2 < master <br>
                   v1<br>
                   index <br>




branch 만드는 방법 <br>
* git branch 하고 엔터 -> branch 목록이 보여짐<br>
* git branch lab1하고 엔터 -> lab1 branch 생성 (*가 있는 것은 해당 branch에 커서가 있는 거임)<br>
커서를 움직이는 명령어 : checkout<br>
* git checkout lab1 -> branch를 lab1으로 이동시킴<br>


만약 성공해서 master의 포인트를 올려서 하고 싶다면?<br>
merge 명령어 사용<br>
git merge lab1 엔터 => 병합이 되면서 master가 lab1가 병합됨<br>

만약 실험중에 master에서 버그가 생겨서 양갈래로 갈려진다면 그 위에단에 lab1이랑 합치면 됨,<br>

-------------------------------------------------------------------------------------------------------------------------------------------

### 20220704
            
![git의 구조](https://user-images.githubusercontent.com/107795925/177078245-06aecd7b-14ef-45a2-904a-3af7d6be2050.PNG)
            
git gui 누르면 gui를 조작할 수 있는 창이 뜸(gui사용시간동안은 bash에서 명령어 사용 불가)<br>
repository에서 visualize all branch history를 클릭하면 현재 상태와 히스토리가 뜸<br>
git gui & -> git bash 말고 새로운 프로세스에서 gui를 실행한다는 뜻(독립적으로 하기 때문에 bash에서 명령어 사용 가능)<br>
-> 즉, 독릭접이 프로세스를 사용하겠다는 말<br>

커서를 바꾸면 git gui에서 진한 글씨로 표시됨.<br>

lab1에서의 실험을 master로 합병시킬때는 merge 명령어 사용(master에서 변경사항 없을 때는 쉽게 merge 가능)<br>
-> 이러한 방식을 fast-foward 방식이라고 함<br>
            
![fast-foward 방식](https://user-images.githubusercontent.com/107795925/177078147-69568712-6e09-4d75-97e4-f280769341bc.PNG)

![fast-foward 방식 결과](https://user-images.githubusercontent.com/107795925/177078165-85e33694-fe8f-4c64-a23d-e9dcfa86ab18.PNG)
            
삭제 방법 : git branch -d lab1(lab1 branch포인트를 삭제하는 명령어)<br>
            
![branch 포인터 삭제 방법](https://user-images.githubusercontent.com/107795925/177078178-667a0bee-82f9-40c6-8a54-a293431cb811.PNG)
            
![branch 포인터 삭제 결과](https://user-images.githubusercontent.com/107795925/177078184-f359cc58-46df-412c-95fb-053c2e0e46e3.PNG)

중간에 branch가 갈라졌을 때는 병합을 시킬려면 master로 이동한다<br>
충돌이 날 경우에는 충돌해결-add-commit 하면 됨.<br>

![branch 갈라졌을 때](https://user-images.githubusercontent.com/107795925/177078205-28307577-df84-47a4-8586-ceba0ab07157.PNG)

![충돌(conflict 발생) 화면](https://user-images.githubusercontent.com/107795925/177078219-78a4dec7-3597-49d0-8d42-9c922d0b0023.PNG)






            
* 그냥 merge를 할 경우에는 conflict라는 충돌메세지가 나타남(에러는 아님)<br>
==== / >>>> 이런 이상한 기호는 모두 지운 후에 정리한다.<br>
            
![갈라졌을 때 최종 merge 결과](https://user-images.githubusercontent.com/107795925/177078226-669e93ce-c428-40f3-83ad-a67b11316b56.PNG)

---------------------------------------------------------------------------------------------------------


* git bash 로컬저장소의 파일들을 github 원격 저장소에 원격저장하는 방법<br>
- 공유시트에 주소 다 나와있음.

* git remote add origin https://github.com/silverstone2/my_repo.git에서 origin은 이름을 의미함
위의 명령어를 git bash에 치고 엔터<br>
이후 git remote -v를 쳐서 등록한다 그러면 두개의 주소가 나오는데 등록이 정상적으로 된거임.<br>
* git push -u origin main(main은 branch명을 적으면 됨) 바로 push 불가능
계정과 비밀번호만으로는 불가하고 인증키(토큰)을 발급받아야함.<br>
한번 발급 받으면 저장을 해놔야함(잃어버리면 삭제하고 다시 재발급 받아야함.)<br>

깃헙 본인계정 - settings - developer settings - personal access tokens를 발급받아야함<br>
new generate - 비밀번호 입력 - note 알아서 적고 Expiration은 no Expiration으로 설정<br>
그리고 밑에 repo 체크(권한은 다 체크하고 싶으면 다 체크해도 됨) 그리고 generate<br>
토큰 나오면 이 토큰을 저장해야함 한번에 저장해야함!<br>

* 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

git push -u origin main 치면 창이 하나 뜸 그때 토큰 누르고 아까 발급받은 토큰 입력<br>
토큰 정보가 맞으면 push가 진행됨.<br>
윈도우 검색 - 자격증명 관리자 - window뭐시기 자격 보면 github에 대한 자격증명있고 암호 다 젖아되어 있어서 다음에 자동으로 가능함


git remote -v : 저장된 목록 확인(연동된)

origin/master는 master보다 하나 더 ahead 되어 있다. origin/master가 master보다 하나 더 올라와 있다는 뜻.
local에는 원격저장소를 tracking하는 branch가 있다.
local과 remote가 맞춰지려면 두번 푸시를 진행해야한다.
'Your branch is up to date'문구가 나오면 끝났다는거임

최초에 add commit하고나서 하면 push를 진행하면 'Your branch is ahead of 'origin/master' by 1 commit'이라는 문구가 뜸
이러면 한번더 push를 진행해주면 된다.[스샷 push과정 참조]

집에서 할 때는 git에 저장되어 있는 상태 그대로 clone을 해줘야함. clone의 경우는 최초에 한번만 해주면 됨.
단순히 파일만 가져오는 것이 아니라 브랜치/커밋 등 모든 상태를 다 끌고 올 수가 있음.


push 코드 순서<br>
init-add-commit-remote add origin 주소-push -u origin.aster-remote -v-add-commit-status -> ahead 확인-origin master-status<br>
->up to date 확인-add-commit-status ahead-origin master-push-uptodate 확인

![push과정](https://user-images.githubusercontent.com/107795925/177121227-61fb7be3-a782-45e4-a8cf-f968a9a6041a.PNG)

![push1](https://user-images.githubusercontent.com/107795925/177121351-c9fc62f9-28e8-4665-9218-a6d6a139eeae.PNG)

![push2](https://user-images.githubusercontent.com/107795925/177121362-95c7b1d9-bcb9-4d45-9c8f-a50107753e1a.PNG)

![push3](https://user-images.githubusercontent.com/107795925/177121378-981511ae-4c6a-4aa4-bf52-1ef41d537979.PNG)

![push4](https://user-images.githubusercontent.com/107795925/177121392-17e61d5d-705b-4074-9c20-eeb79d52d6bc.PNG)

clone하는 과정 : git clone repository주소
-> 저장소의 이름대로 폴더가 복제가 됨(단지 폴더 자체만 복사될뿐임 그러므로 git bash를 안쪽으로 들어가줘야함)
cd 폴더명 입력하고 이후 git status 하면 Your branch is up to date with 'origin/master'. 요러한 문구가 나옴.
이후부터는 commit을 그냥 내려받기만 하면 됨 -> 이는 fetch라고 부름.

![clone 구조](https://user-images.githubusercontent.com/107795925/177121408-905f36af-4b4a-415c-b42b-f44264cee2c5.PNG)

![clone1](https://user-images.githubusercontent.com/107795925/177121431-c2dcc114-867b-4f20-8d17-21a7e95b3efe.PNG)

fetch를 진행하면 오리진 마스터가 마스터보다 어헤드가 됨. 그러면 merge를 통해서 합병시켜버리면 됨
원격저장소에서 가장 최신으로 받는 건 fetch+merge 방법 / 원격저장소로 보내는 건 push

fetch진행방법 : git fetch origin
이후 git status에서 보면 어헤드되어있음. 그래서 git merge origin/master로 merge를 진행해준다.

![Fetch를 진행했을 때의 구조](https://user-images.githubusercontent.com/107795925/177121464-cb11310f-57ff-4e46-a7b9-742f3f1fdfe8.PNG)

똑같은 곳을 수정 안하면 자동 머지가 됨.

![fetch 이후 merge진행하면 master가 제일 위로 올라옴](https://user-images.githubusercontent.com/107795925/177121527-83d16afe-2410-483a-9e42-2d882c3308f6.PNG)


그러면 파란 글자가 써져있는 글이 뜨는데 이건 bash 편집기 이고
뜨면 :wq쓰고 엔터하면 됨. 그러면 merge가 됨.

![최종구조(fetch 후 merge)](https://user-images.githubusercontent.com/107795925/177121487-12e1d833-f070-4681-a733-768acc1320af.PNG)


---------------------------------------------------------------------------------------------------------

### javascript
* head와 body에 있는 script 영역은 페이지 로딩시점에 입력이 됨.<br>
페이지 검사-console에서의 javascript는 입력하고 엔터를 누르는 시점에 입력이 됨.<br>
문자의 경우는 '나 "로 감싸야 입력이 됨.
* javascript는 head의 안쪽이나 body의 안쪽에서 영역을 생성할 수 있음.
* javascript에서의 변수 -> 검사-console에서 기능 사용 가능(단, vscode에서는 사용 x)
* 변수를 만들때는 미리 약속된 예약어 let을 사용한다.<br>
let 다음에는 변수의 이름을 정한다.<br>
'=' 의 우측에 있는 값이 = 의 좌측에 들어간다(대입된다)<br>
한줄의 끝에는 ;을 작성한다.<br>

* 변수를 이용한 연산을 한 그 위치는 결과값으로 나타난다.

*  숫자 1 옆에 있는 `로도 문자열을 받을 수 있다! `는 back tick이라고 칭한다. back tick을 이용하면 여러줄의 문자열을 편리학 작성할 수 있다.

* 연산을 할 때 값이 들어 있는 변수명으로 연산을 할 수도 있다.


* 참과 거짓을 나타낼 때 사용하는 boolean type<br>
boolean type 데이터가 들어가는 변수의 이름을 대화식으로 지으면 가독성이 좋다. (isXXX, canXXX)

* 나의 변수명으로 여러개의 값을 한번에 관리 가능하면 좋겠다라는 생각이 들음<br>
특정키값으로 여러값을 한번에 저장하는 type ex) { key:value, key2:value2, ,,,,,,}<br>
페이지 - 검사 - console에서 확인하는 명령어는 변수명.key ex)mem1.num , mem1.name ,,,<br>


* 하나의 변수명으로 여러개의 값을 한번에 관리 가능하면 좋겠다라는 생각이 들으면 이때는 object type을 사용하면 된다.

![image](https://user-images.githubusercontent.com/107795925/177246482-b61aff50-b939-4076-b6eb-c4d6aeb00e83.png)

![image](https://user-images.githubusercontent.com/107795925/177246514-344b7579-9bdc-4aff-8d6b-a4e9ed5bfd7d.png)

![image](https://user-images.githubusercontent.com/107795925/177246559-2a85db1b-d476-44c0-a8d9-384e1a6ee24f.png)

![image](https://user-images.githubusercontent.com/107795925/177246587-47a2e952-363c-4430-addd-53d187fa1df3.png)

number, string, boolean type이 들어 있는 변수 안에는 실제로 그 값이 들어 있다고 생각해도 무방하다.<br>

object, array, function type은 heap 영역에 만들어진다.(사물함 영역에 만들어진다)<br>

![==에 대한 정확한 정보](https://user-images.githubusercontent.com/107795925/177289080-6c3d3b34-0abf-4720-8853-41a72ea81554.PNG)

![참조  type 분류1](https://user-images.githubusercontent.com/107795925/177289055-08da9925-e31f-4c56-b6d5-4012024dc7cf.PNG)

사물함은 사물함 번호로 관리가 된다. (즉 heap 영역 안에서의 변수들이 할당받는 주소값이 다르다는 뜻으로 해석하면 됨)<br>
사물함 번호를 프로그래밍적인 관점에서는 "참조값"이라고 부른다.<br>
"참조값"은 사물함 key라고 상상을 하면 된다. <br>

![object와 배열의 상관관계](https://user-images.githubusercontent.com/107795925/177289012-a4ee5ffa-6cb8-4273-a8f4-490d6e3130a1.png)

![object끼리 비교했을 때 다른 이유](https://user-images.githubusercontent.com/107795925/177289033-4fc38555-6920-49bb-b866-af8d8a93bae5.PNG)

프로그래밍관점에서 봤을 때 사람이 필요한 물건을 주머니에 넣고 바로 꺼내쓰는 것과는 다르게 heap이라는 영역에 함수가 미리 만들어져있고 이를 끌어다 쓴다.<br>
key 값이 필요함 이것들을 사용하려면!<br>

![image](https://user-images.githubusercontent.com/107795925/177288443-f17905ff-78e3-469e-b185-bd442a48d71c.png)

![image](https://user-images.githubusercontent.com/107795925/177288547-9a68eaaa-77d0-4713-8619-b92c7bbf25fe.png)

![image](https://user-images.githubusercontent.com/107795925/177288602-a4939260-f19d-4258-aa02-9a0f448b7fae.png)

![image](https://user-images.githubusercontent.com/107795925/177288691-6dc828ab-ad3e-4bc1-af90-3f42fdce9edf.png)

* 선생님의 저장소를 사용하는 방법
1. 그냥 download zip해서 압축 풀어서 사용한다(매번 해줘야하는 번거로움이 있음)
2. 나의 computer의 특정 폴더로 선생님의 저장소를 clone해서 사용한다.(fetch+merge를 통해 update가능하지만 push 불가)
3. 선생님의 github 저장소를 나의 github로 fork한다.<br>
    나의 github에 있는 fork된 저장소를 나의 computer의 특정 폴더로 저장소를 clone해서 사용한다.<br>
    (fork하는 그 시점만 가능 / 주기적으로 업데이트 해야함)<br>
    -> remote 저장소가 두개가 되는거임.<br>
    2번 방법 적용하여 깃에서 끌고 옴<br>

![선생님 저장소 사용하는 방법 2번방법](https://user-images.githubusercontent.com/107795925/177288927-338a83d9-037b-4b19-b7b1-be3df61bc001.PNG)

![선생님 저장소 사용하는 방법 3번 방법3](https://user-images.githubusercontent.com/107795925/177288942-1f44d8b3-a3c7-4599-a99e-1dc210bedf4d.PNG)


