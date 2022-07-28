# TIL
Today I Learned
* Create Git
* Create Category(TIL / Algorithum / Unity / Java)
* 6/28 Acon Academy 사전 OT
* 6/30 웹 서비스 기반 데이터 분석 및 자바 개발자 양성과정 교육 시작(html, css, javascript 강의(참고 URL:https://ofcourse.kr/css-course/cursor-%EC%86%8D%EC%84%B1))
* 수업 진행 게시판 : https://docs.google.com/document/d/1i7gQUmVn2FaSWVQRmiDY9_J5Y9o90QeMDUF6T_9SkJc/edit
* 6/30 ~ 7/11 : html, css, javascript

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


* 주석 : html - <!-- --> | css&javascript -  // , /* */
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

-----------------------------------------------------------------------------------------------------------------------------------------------------
### 20220705
           
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

-----------------------------------------------------------------------------------------------------------------------------------------------------
### 20220706

* alert, confirm, prompt 모두 콘솔창에서 실행이 가능하고 빌트인함수임.

![image](https://user-images.githubusercontent.com/107795925/177463043-ef6255d5-5ea9-44e6-a687-f13c89a6980c.png)

* 각종 type들을 저장하면서 구조가 조금씩 바뀌기도 하고 변수가 어디에 선언이 되었느냐에 따라 호출하거나 참조하는 방법이 달라진다(아래 3개 사진 참고)

![heap과 stack 구조](https://user-images.githubusercontent.com/107795925/177464259-4ff4a434-806d-4543-80a4-726030d7433a.PNG)

![heap과 stack 구조2](https://user-images.githubusercontent.com/107795925/177464263-95e9adff-5084-4cd5-9231-913ad81f2877.PNG)

![전역변수와 지역변수](https://user-images.githubusercontent.com/107795925/177464270-3221a15c-e3d1-4ba0-aa44-aaff2f0e1c78.PNG)

* 구분해놔야할 상황
object type : 여러 타입의 정보가 서로 섞여잇으면 사용하는 것이 좋음(단 순서가 중요하지 않을 때)<br>
array type : 하나의 타입으로 구성되어 있지만 여러 개가 나열되었을때 사용하는 것이 좋음(순서가 중욯ㄹ때 주로 사용)<br>

* function type -> 특정 시점에 동작할 기능들을 한곳에 모아놨다가 일괄적으로 실행을 시키는 특징을 가지고 있음.
- 참조값은 레퍼런스 값이라고 하며 이는 변수가 아닌 다른 곳에 들어 있을 수도 있음<br>
(ex) 사물함 키가 다른 사물함 안에 있는 경우도 있듯이 참조값도 똑같음.

* git 추가사항

보통 commit을 진행할 때는 git commit -m "~~~" 형식으로 작성하지만 git commit 후에 뒤에 아무것도 없이 enter를 누르면<br>
vi 편집기 화면으로 들어가게 됨.<br>
vi editor는 두가지 모드가 있음(edit mode / command mode)<br>

이 때 맨 밑에 insert라는 글자가 있으면 편집모드로 전환된 것이고 없다면 command 모드로 진행됨.<br>
insert는 i를 누르면 나타났다가 사라지며 화면상 '#'으로 시작되있는 것은 모두 주석처리 된 것이다. 명령모드는 esc를 통해 바꿀 수 있고 이후에는 :wq로 저장하고 나가면 된다.

* 문서 객체는 object와 매우 유사하다.

![문서객체](https://user-images.githubusercontent.com/107795925/177464048-3ba9c19a-2c5c-4448-9200-c566c27aa3f3.PNG)

위의 사진에서 보는 12개의 구성요소는 heap에 각각의 문서 object를 생성한다. 만일 개발자가 필요하다가ㅗ 하면 저 문서 object에 접근할 수 있게 허용해준다.<br>
문서의 참조값을 얻어오는 방법 : 웹페이지 - 검사 - console - document.querySelectorAll(바꿀요소)[몇번째순서].바꿀내용

-----------------------------------------------------------------------------------------
0706 오후

![example1](https://user-images.githubusercontent.com/107795925/177512869-434862a7-f608-47a7-92b1-ef73ba9c2b20.PNG)

![example2](https://user-images.githubusercontent.com/107795925/177512875-9f96021f-9e61-42cc-8095-0dc37863256f.PNG)

![example3](https://user-images.githubusercontent.com/107795925/177512889-e6b54732-b70a-4cda-b1e8-8f8a86f06eff.PNG)

- value 전의 .까지는 input의 값을 말함.

![image](https://user-images.githubusercontent.com/107795925/177686911-6656bed1-5a31-4054-89e8-0230f0c3c56b.png)

------------------------------------------------------------------------------------------------

### 20220707

* event part
### 이벤트 처리를 onXXX="" 속성을 사용해서 처리하면 global 변수(함수)가 필요하다. global 변수(함수)를 많이 만드는 것은 바람직하지 않다.(중요@@@@@@@@@@@@@)
- onclick, onmouse와 같은 명령어를 사용할때는 global영역에 변수가 선언되어 있어야 한다.

![image](https://user-images.githubusercontent.com/107795925/177687205-7e79ae57-5abf-43a7-8f32-bcb506eb7931.png)

```html
            document.querySelector("#myBtn").addEventListener("click",function(){
                        document.querySelector("#console").innerText = "앗 버튼을 눌렀네요?";
            });
```

- addEventListener() 함수는 2개의 값은 전달함. 앞의 값은 string type(이벤트명)을 전달하고<br>
뒤의 값은 function type(callback function)을 전달 [callback 함수는 나중에 자동으로 호출되는 함수를 의미함.]<br>
javascript는 함수를 호출하면서 함수 자체를 전달하는 기능이 있음(함수도 heap영역에 만들어지는 data이기 때문)

* css는 내부와 인라인으로 구분된다.

![image](https://user-images.githubusercontent.com/107795925/177687357-c44431ba-e990-4c8e-b020-3b0cdc4d9e5c.png)


* css를 적용할 요소에 style 속성을 이용해서 직접 css를 작성할 수도 있다.<br>
이러한 css를 인라인 css라고 한다. <br>
인라인 css는 내부 css보다 우선시 된다.(우선시 된다라고 함은 내부 css를 override할 수 있다는 의미)

![image](https://user-images.githubusercontent.com/107795925/177687435-4aea7eee-c46b-4196-8b50-53375191c654.png)

--------------------------------------------------
0707 오후
* git에서 파일 지울때는 git status 확인 후  git restore . 입력 이후 git clean fd 입력하면 파일들 사라짐

![image](https://user-images.githubusercontent.com/107795925/177735548-498f054c-893e-414e-8e67-f2d9a4df9742.png)

- javascript에서는 인라인 요소를 수정할 때css처럼 background-color와 같은 명령프롬프트를 사용불가(javascript에서는 -를 산술연산자로 인식하기 때문)<br>
대신 javascript에서는 backgroundColor와 같이 대문자를 포함해서 적용시킬 수 있다.

- css영역의 style에서 대상의 움직임에 관한 설정을 하고 싶을 때는 transition 사용한다. 이는 움직임에 대한 시간적인 변화를 줄때 사용<br>
linear은 일정한 비율을 의미함.<br>
ease-out은 도착을 부드럽게 함 / ease-in 출발을 부드럽게 함 / 둘다는 ease-in-out

- 코드 작성법에 따른 분류<br?
moveRightBtn을 move_right_btn처럼 작성하는 것을 snake case(_사용)<br>
moveRightBtn은 camel case(대문자사용)<br>
move-right-btn은 kebob case 라고 함(-사용)

* 간편 명령어
```html
div{div$}*num
```
아래 그림 참조

![image](https://user-images.githubusercontent.com/107795925/177736217-866fe06f-de70-405f-9146-3be6f79767fe.png)

-------------------------------------------------------------------------------------

* 20220708

![image](https://user-images.githubusercontent.com/107795925/177956558-f841a025-890f-46fd-965d-07795534c8a7.png)

![image](https://user-images.githubusercontent.com/107795925/177956695-ac77cc44-c1d7-4b88-b614-d1f1e6e2ad88.png)

![image](https://user-images.githubusercontent.com/107795925/177956754-7314056d-11a9-4d97-943c-b614735c1508.png)

![image](https://user-images.githubusercontent.com/107795925/177956815-eeeb81ff-73a4-4d9c-8450-4193c8c30677.png)

![image](https://user-images.githubusercontent.com/107795925/177956858-1edda7c9-6774-4339-b9e4-33b1fe65b9fb.png)

![image](https://user-images.githubusercontent.com/107795925/177956908-1960e982-2889-433f-91bf-01eb92aff6ef.png)

![image](https://user-images.githubusercontent.com/107795925/177956947-5261dcf8-7369-4bec-a8fc-5ed637e110ca.png)

![image](https://user-images.githubusercontent.com/107795925/177956977-72765988-7c3a-4a18-8eb0-a86632a9d08d.png)

-------------------------------------------------------------------------------------

*20220711

![문자열 작성시 insertAdjacentHTML](https://user-images.githubusercontent.com/107795925/178380340-17ddca40-bc5f-423d-9fbe-418055971c55.PNG)


![마진패딩](https://user-images.githubusercontent.com/107795925/178380354-af7a686f-24c4-4cba-8d25-c1b7d473f5d3.PNG)


![3개 작성시(순서는 시계방향임)](https://user-images.githubusercontent.com/107795925/178380359-cd9160a4-27ce-4c29-8650-6c3cf0e55103.PNG)


--------------------------------------------------

*20220712

* Step18_form2.html 파일을 콘솔로 검사를 했을 때
* 아이디가 email인것을 document.querySelector로 변수를 선언해준다음
* 변수.classList를 작성하면 add와 remove가 생김
* 그 상태에서 email.classList.add("is-valid")를 치면 웹페이지에 적용됨.
* 즉, javascript로 원하는 시점에 적용이 가능하다!
* 사진 추가 예정

--------------------------------------------------

* 20220713
            
### Oracle
            
            Oracle

* cmd - sqlplus.exe
- 사용자명 / 비번 : systme / oracle

- (테스트)사용자 계정 & 비밀번호 만들기
- CREATE USER acorn IDENTIFIED BY acron1234;

- 테스트 계정 / 비밀번호 : acorn / acorn1234

- 계정 생성후 접속 권한과 자원을 줘야 함
- GRANT CONNECT, RESOURCE TO acorn;
            -> 위의 과정이 초기설정 완료임

- command창 닫고 acorn계정으로 재접속하기

 DB에 저장하는 정보 종류
 1. 숫자
 2. 문자
 3. 날짜
를 주로 저장을 함.

- key value의 쌍으로 저장하는 db도 있지만
- oracle의 경우는 표(table) 형식으로 정보를 저장한다.

- oracle에서는 테이블의 칼럼을 정해줘야하고 저장하는 정보의 type도 정해줘야 한다.
- oracle = 정보가 추가/삭제될때 row가 추가/삭제되는 형식

- 파일로 저장시 데이터 신뢰성 확보 x / 용량도 많음 / 찾기 힘듬

* oracle 명령어는 대/소문자를 구별하지 않는다!
명령어를 대문자로 표기하면 구분하기 쉽다!
; 이 나오기 전까지는 실행을 안함(그냥 enter누르면 개행이 됨)

CREATE 명령어 : 무언가를 새로 생성하는 명령어
DROP 명령어는 삭제하는 명령어

()안에서 num 칼럼명 NUMBER은 숫자타입, VARCHAR2는 문자타입이고 VARCHAR2 옆의 숫자는 최대 문자크기를 말한다.
* 영문자의 경우에는 1씩 차지하나 한글은 3씩 차지한다.

테이블의 구조를 보고 싶을 땐 'DESC 테이블명'을 치면 된다.
문자를 입력할 때는 싱글 따옴표를 사용한다.

* 정보 입력한거 조회하는 방법
SELECT 요소명 FROM 테이블명; 요소명 대신에 * 을 넣으면 전체를 조회함.
조건달아서 조회할 때는 SELECT 요소명 * FROM 테이블명 WHERE 타입 = 값;
명령어 : SELECT / UPDATE / INSERT / DELETE => commit하기 전까지는 임시반영의 개념

* 갱신하는 방법
UPDATE 테이블명 SET 수정할 사항 WHERE 수정할 테이블의 로우나 칼럼;

* 삭제하는 방법
DELETE FROM 테이블명 WHERE 삭제하려는 정보;

테이블이나 데이터를 수정후 commit을 해야 다른 세션에서 확인이 가능하다.

primary key라는 것을 통해 제약조건을 적용시킬수 있음.
primary key는 해당 칼럼에 대한 데이터는 무조건 입력을 해야함.
동일한 조건을 적게 되면 무결성 제약 조건에 위배된다는 에러메세지 출력됨.
* 선생님이 주신 pdf 파일 참조할 것

특정 하나만 삭제 수정을 하려면 row를 대표할 수 있는 primary key를 활용해야함.




<질문>
선생님 PDF 파일에는 VARCHAR2(50) => 가변 문자열 최대 영문자 50 (한글:25) 글자로 되어있는데 아까 한글은  3정도 먹는다고 하셨는데 둘중에 뭐가 맞는건가요?!


<답변>
한글을 처리하는 방식은 command 프롬프트 환경에서 한들을 처리하는 방식 때문에 3을 먹는거구요
나중에 실제로 java application 을 활용해서 한글을 저장하면 2 를 먹게 됩니다.


변수 크기를 크게 설정하고 값을 입력해주면
컬럼이 밀리는 현상 발생한다 이때 쓰는 방법

SET LINESIZE 200(숫자는 유동적)
COLUMN name FORMAT A10 -> 숫자는 글자 자릿수를 의미
COLUMN addr FORMAT A15
하지만 위의 과정은임시반영이기에 완전반영이 필요할 땐 commit을 실행시켜야함.

DELETE FROM member; 처럼 조건을 안주면 전체삭제가됨.
복구하고 싶으면 ROLLBACK; 명령어를 치면 됨.

날짜 데이터는 SYSDATE를 통해서 나타낼수 있음
- oracle에서도 javascript에서처럼 함수를 호출할때는 ()를 쓰지만
  아무것도 전달하지 않을 때는 소괄호를 사용하지 않는다.

  oracle에서는 우리가 table을 만들지 않아도 dual이라는 테이블이 존재함.

  SELECT test_seq.NEXTVAL FROM dual; 에서 NEXTVAL는 순차적인 값을 보여줌.


계정 쉽게 생성 + 테이블 정보까지 받아오는 방법
-> scott이라는 test계정을 만들고 tiger라는 비밀번호와 안의 테이블까지 가져오는 방법
@하고 파일을 끌어오면 됨. 그러면 파일안의 내용을 모두 실행을 함
(계정 생성부터 테이블 생성 및 샘플데이터 입력까지 모두 되어 있음)


정렬을 쓸때는 ORDER BY 명령어를 쓰고 ASC은 오름차순 DESC는 내림차순이다.

WHERE 절의 효과는 row를 추려내는 효과가 있다!

일시적으로 세션에서 컬럼 깔끔하게 보는 코드
SET LINESIZE 200
COLUMN ENAME FORMAT A10
COLUMN JOB FORMAT A10

명령어는 대소문자를 안가리지만 변수는 가림

칼럼에 별칭을 붙일 수 있다.
칼럼명 뒤에 AS라고 적으면 된다.(AS ALIAS의 약자)
AS는 따옴표로 안감싸도 되고 띄어쓰기 안해도 됨.

SQL연산자 주에서
%j% 에서 %~%는 해당 글자 포함되는 거 출력
_A%에서 _는 한글자를 의미함.
            
            
            
------------------------------------
* 20220714
            
host라고 치면 윈도우 환경으로 나감.
exit치면 다시 돌아옴

SPOOL my_spool.txt 라고 치면 지금부터 내가 기록한 것들은 텍스트파일로 저장한다는 뜻
저장을 여기까지만하겠다고 하면 SPOOL OFF 입력하면 됨.
cmd 안에서 확인할 때는 type spool.txt락 입력한다. 이때 확인은 host명령어를 사용해 윈도우 환경에서 확인해야한다.

dual은 dummy table

중간에 한글 넣고 싶으면 ""로 한글을 감싸줘야함.


DATE -> CHAR : TO_CHAR()
CHAR -> DATE : TO_DATE()
---------------------여기까지 단일행 함수=--------------------



복수행 함수
여러개의 로우 당 하나의 값을 반환하는 함수
group by 절을 쓸떄 select와 from사이에는 group을 대표할 수 있는 값만 써야함


GROUP BY 는 로우에 대한 조건 절이고

HAVING절은 특정 조건을 주고 싶을 때 쓴다.


ORACLE은 JOIN절을 사용하지 않는다면 FROM절에 있는 모든 경우의 수를 다 조합해서 표현한다.
조건이 여러개라면 AND를 통해서 여러개의 조건을 적용시킬 수 있다.
테이블명이 길면 제일 앞글자를 따서 별칭을 이용해 코드를 작성할 수 있다.
ANSI 조인을 사용하면 가독성이 더 좋아짐.

FROM EMP
INNER JOIN DEPT ON
-> EMP 안에 JOIN을 조인해주겠다는 뜻이고 ON 다음에 JOIN 조건을 적어주면 됨, 

USING 절을 활용해서 ANSI JOIN을 좀더 쉽게 할 수 있음
(단 조인을 쓸때 같은 칼럼일때만 USING을 사용해야 한다.)
ORACLE에서 NULL은 비교 불가이기 때문에 연산자를 써야함.

INNER JOIN은 DEFAULT라서 생략해도 가능하다

OUTER JOIN : (+)를 WHERE절 왼쪽 조건뒤에 붙여야 함 -> 보이지 않았던 정보도 OUTER JOIN을 통해 보여줌.
오른쪽의 칼럼이 왼쪽보다 하나 이상 많아서 범주를 벗어나 오른쪽이 삐져나오면 RIGHT OUTER JOIN이라고 함.

            
            ------------------------------------------------------------------------
            
            * 20220715
            rownum은 행번호를 붙이고 싶을 때 사용하는 명령어


서브쿼리는 메인쿼리보다 먼저 실행됨.
단일행 쿼리는 = 와 같은 동등연산자로 비교 가능
다중행 쿼리는 단일행과는 다르게 = 와 같은 동등연산자로 비교불가
그래서 in all any exist를 사용한다.
group by는 서브쿼리가 리턴하는 행의 개수가 여러개일때 사용

* 특정 로우의 위아래값을 같은 로우에 표시하고 싶다면?
lead와 lag는 값이 없을 때 0가 default값이 된다.

문자열로 할때는 문자열의 기본값음 'no'또는 '없음'이라고 하면 됨.




----------오후 시작-----------
localhost:8080/apex 오라클 gui

관계형데이터베이스


dml = commit하기 전까지는 임시반영
* 참고사항 :  primary key = not null + unique
시퀀스 생성

oracle에서 command창은 직접 commit이나 rollback을 해줘야 함,. 

참조하는 방법 -> db 참조방법 사진 참고 (regerence 사용해서 참조)


DESC USER_TABLES는 오라클에서 제공해주는 테이블관련 명령어임.
USER_ 뒤에 단어 붙이면 유저에 대한 정보가 나타남
DESC USER_CONSTRAINTS는 제약조건에 대한 경고를 조회할 수 있는 커리



TABLE_NAME                                                   CONSTRAINT_NAME
          CO
------------------------------------------------------------ ------------------------------------------------------------ --
EMP2                                                         SYS_C004008
          R  REFERENCE
MEMBER                                                       SYS_C004004
          C  NOT NULL
EMP                                                          FK_DEPTNO
          R 
DEPT                                                         PK_DEPT
          P  PRIMARY KEY
EMP                                                          PK_EMP
          P
MESSAGE                                                      SYS_C004003
          P
BIN$6bzPFNdCS4CrUAcWrG0VTA==$0                               BIN$RYNPWeFqQeC3xFOBke2w5w==$0
          P
BIN$ltKOZLEMTKGKfQk7YZLwtg==$0                               BIN$fzww+3yYRC2i17Ln9WYk9A==$0
          P
MEMBER                                                       SYS_C004005
          P
DEPT2                                                        SYS_C004006
          P
EMP2                                                         SYS_C004007
          P

11 개의 행이 선택되었습니다.
fk = 외래기 foreign key





제약조건의 이름을 이쁘게 지으면 관리하기 편해짐.
제약 조건의 이름을 부여하지 않으면 임의로 시스템이 부여함.


객체를 삭제할 땐 DROP 명령어 사용(테이블 삭제는 rollback이 안됨 / 걍 새로만들기)


column level 제약조건 : 칼럼을 정의할 때 바로 정의하는 것
table level 제약조건 : 칼럼 정의할 때 정의 안하는 거
-> 뒤에 언급해줄때 어디에 적용할건지 ()안에다가 명시를 해줘야함.
외래키의 제약조건의 경우는 foreign KEY(참조할 칼럼)이라고 명시해줘야한다.

-----------------------------------------------------------------------------------------------------------------------------------

### 20220718 TIL

-오전-
ORACLE에서 계정을 삭제할 때는 테이블이나 객체가 있을 경우 바로 삭제가 안된다.
REM은 주석
group by로 묶을 때는 그 값을 대표하는 값만을 묶어야 오류가 안생긴다.
USING 쓰면 약자 사용 금지 ex)e.ename 사용 금지


ANSI와 OUTER를 같이 쓸때 FROM에 있는게 왼쪽이고 JOIN다음에 오는게 오른쪽임


테이블에서 전체의 값이 아닌 특정 구간의 데이터만을 빼올려면 서브쿼리를 이용해야한다.
방법 : 정렬을 실시한 후 정렬한 것을 괋호로 묶는다(행번호를 부여해야함)
       이 때 묶은 테이블은 이미 정렬이 된 테이블이며 이후 행번호를 부여한다.
       select 옆 result1.*은 정렬된 select문에대한 값을 의미

rownum은 select한 시점에서 숫자를 반환하는 형식의 함수!
서브쿼리로 묶을 때 where절은 사용불가능함
where절을 써버리면 선택된 레코드가 없다고 뜸(where절의 조건은 false로 반환됨)


- 오후 -
- 제약 조건 CHECK()
- 괄호 안의 값이 나올때만 true를 반환해준다.
- 제약조건으로 걸어놓은 값이 아닌 다른 값을 넣으면 제약조건에 위배된다고 에러뜸
- table 레벨에서는 NOT NULL 불가 / column 레벨의 제약조건에서만 가능


- alter table을 사용할 때 제약조건을 추가할 때는
- add constraint를 사용하며 이때 뒤에는 테이블 레벨의 제약조건을 작성하면 된다.

- 시퀀스 : 수정이 불가하기 때문에 수정하려면 삭제하고 재생성해야함.


-오라클 계정 접근 안될때는 컴퓨터관리 - 서비스 -OracleService XE / OracleXETNSListener 확인
- 이 때 오류 메세지는 tns:프로토콜 어댑터 오류라고 뜸



###<javascript ecma6>

- javascript를 쓸 때 함수에 있는 변수값들을 변경하는 경우가 거의 없음,
- 즉 변경하는 경우가 거의 없기 때문에 const를 자주 사용(단 변수값이 상수 일때만)


--------------------------------------------------------------
###20220719 오전

1. 배열은 map() 함수를 원래 가지고 있다.
2. map() 함수를 호출하면서 함수를 전달해야 한다.
3. 전달한 함수는 배열의 size만큼 즉시 반복 호출한다.
4. 반복호출 하면서 그 함수의 배열에 저장된 item을 순서대로 전달해준다.
5. 함수 안에서 리턴해주는 값을 순서대로 모아 새로운 배열을 map() 함수를 리턴해준다.


-함수 = 동작 -> 함수를 콜하면서 인자로 함수를 전달하는 건 동작을 사용하면서 '동작을 전달했다'는 의미임(동생한테 은행 갔다오라고 해서 동생이 은행에 가고 창구에가서 메모를전달해주면 알아서 해결된다는 의미로 해석)
-함수를 전달하면 그 전달 즉시 호출을 하고 값을 반환해준다.

- 필요한 값만 남겨서 새로운 배열에 넣어놓은 것이 filter함수
- 배열의 filter() 함수는 조건에 맞는 item으로 구성된 새로운 배열을 리턴한다.
true가 리턴된 index의 item으로만 구성된 배열이다
- 가장 첫번째로 true를 리턴한 곳의 item을 리턴하는 find()함수

- 객체 사용
![image](https://user-images.githubusercontent.com/107795925/179661550-7b02cff3-c47b-473c-8c5e-df54697885d3.png)

- 함수 사용
![image](https://user-images.githubusercontent.com/107795925/179661519-461e73f9-b376-4ca7-8521-d932b42c347f.png)

- backtick 기호를 이용해서 문자열을 만들 수 있다.
- backtick은 여러줄의 문자열을 편하게 작성할 수 있다.
- backtick은 변수안에 들어있는 숫자나 문자열을 연결할 때도 편하다.
- backtick은 게인기호도 알아서 입력이 됨

- 다양한 포문(for)
![image](https://user-images.githubusercontent.com/107795925/179661694-191aa8ce-4942-468b-9962-328bfaad6e27.png)
            
- setTimeout() 이라는 builtin 함수가 있다.
- setTimeout(콜백함수, 지연시간(ms))
- 어떤 작업을 일정시간 지연 이후에 하고 싶을 때 사용한다.
- setTimeout 예시 사진 
![image](https://user-images.githubusercontent.com/107795925/179661827-49466976-2c30-4865-a28b-540afd1e91a0.png)

#오후
- 딜레이 비동기 동작(promise)
![image](https://user-images.githubusercontent.com/107795925/179707151-3c7a3a3b-eacb-4203-b814-140399a25c69.png)

![image](https://user-images.githubusercontent.com/107795925/179707247-2b2e675f-ceb2-46be-8215-e35648571f73.png)

- fetch 함수는 실행시킬때는 라이브서버로 작동시켜야함
- 서버에  friends.json 문서를 요청해서 받아온다.(json 파일은 따로 생성해야함)

-------------------------------------------------------------------------
###20220720
#GIT
- git에서 restore기능은 untracked file을 되돌릴수는 없다 그 외에는 가능
- untracked file은 clean -fd로 해야 없어짐

- git 작업 중 작업을 임시종료시키고 다른 branch에서 작업한게 따라오지 않으려면 git stash save라고 쳐서 임시저장을 해야한다.
- 단 untracked file은 임시저장이 따로 안된다,
- 그래서 git stash list라고 저장된 목록을 살펴본다
- git stash pop을 치면 index.html에 변경사항이 다시 살아남.(stash한 list를 불러서 적용시키는 원리)
- pop은 지우면서 긁어와서 적용을 시키는 것이다

- git stash -u 라고 명령어를 치면 untracked file을 포함해서 임시저장한다는 뜻임.


- 작업을 종료할 때는 working tree가 clean한 상태여야 한다.

# JAVASCRIPT ECMA6(ES6)
- str1은 json형식에 따른 것
- JSON.parse(변수명)으로 json형식으로 표시가능
- json 자료 참고링크 : https://www.oracle.com/kr/database/what-is-json/
- json은 javascript와 유사하지만 방의 이름을 ""로 감싸야함
- xml과 json 등 여러가지 언어를 사용할때 형식을 갖추면 편함
- 시간 날때 javascript closure 개념 확인해봅기~!~!~!~!~!~!~!~!!
![image](https://user-images.githubusercontent.com/107795925/179937743-2fb8e785-1357-405f-8224-e1aeff542deb.png)


--------------------------------------------------------------
#20220721

git reflog 는 git에서 행한 작업들에 대한 로그를 모두 보여줌(reflog = reference log)

일반적으로 취소를 할때는 git reset 명령어를 사용하는게 맞지만 사용하면 안될 경우도 있다
그 경우는 commit한 것을 이미 github에 올린상태라면 reset하는걸 고려해보아야함(올린걸 clone해서 다른 작업하고 있으면 대참사발생)
이럴 경우에는 취소하는 이력을 따로 commit해주면 된다.

한 줄에 로그 표시하고 싶으면 git log --oneline

reset은 hard, soft, mixed 3가지의 옵션이 있다!
일부 수정만 할거면 mixed
untracked file까지 강하게 되돌릴거면 hard
좀 약하게 할거면 soft

------------------------------------------------
<java>

- 오른쪽 돋보기 옆 아이콘 누르면 open Perspective 눌러서 환경 변경하면 됨

- 편집기 환경설정하는 곳은 window - preferences 클릭
- 처음 실행하면 preferences에서 encoding을 잡아줘야함
- encoding을 workspace-other-utf8로 변경하기
- workspace에서 .metadata는 java의 설정값을 저장해준다
- 이클립스의 폴더는 이클립스의 기능을 통해서 조작해야함(복붙 금지 -> 동작 안함)

- 자바에서의 패키지는 폴더를 말함.
- xxx.java => 클래스라고 말함

- 디버깅을 할때는 브레이킹 포인트가 설정되는게 선행되어야 함 브레이킹포인트는 숫자옆에 칸을 더블클릭하면됨
- 이후 위족에 벌레모양에 debug as 누르면 프로젝트 눌러서 실행하면되고 다음 걸로 넘어가고 싶으면 f6누르면됨
- 오른쪽 value에서 String값에만 id가 부여되어있음

- 다시 자바환경으로 돌아오려고 하면 오른쪽에서 환경 변경만 하면 됨.

- window-reset preferences하면 최초의 환경으로 돌아옴

- jre - java runtime environment를 의미


- <기본 데이터 타입>
- 숫자 - byte / short / int /long / float / double

- 논리 - boolean

- 문자 - char

- 공통특징 : 소문자로 시작합니다



- <참조 데이터 타입>
- 기본데이터 타입과 상반되는 관계

* 디버깅에서 나타나는 id는 heap영역에서의 참조값이다(사물함 영역의 key값)
- 객체 : 값의 저장소 + 기능(어떠한 동작을 의미) (사물함(heap영역)영역이 만들어지고 그 key값이 참조됨)

- 디버깅 멈추고 싶을 때는 클릭하고 위에 빨간네모 (stop button) 클릭하면 됨.
- 디버깅이 멈춘 상태는 terminated라고 뜸

- 자바에서의 . 은 저장소 혹은 기능을 찾아감 -> 기본데이터값은 아무것도 나오지 않음(참조값이 아니기 때문에)
- 참조데이터만 .을 찍으면 부가 기능이 나온다(참조데이터만의 특징)


-------------------------------------------------------
#20220722

- 스레드(thread) : 순서대로 실행하는 흐름

- main 메서드는 프로젝트에서 다량의 클래스 중 하나만 가지고 있어야한다,

- 자바에서 데이터를 기억시키는 곳은 저장소 또는 필드(기능은 메소드라고 함)

- <선생님 필기>
- 참조 데이터 type 은 사물함 영역(heap) 에 실체가 만들어 진다.
- 그 실체는 객체라고 부른다.
- 객체는 데이터의 저장소(field) + 기능(method) 으로 이루어져 있다.
- 객체의 저장소(fiedl) 에는 java 에서 다루는 다양한 data type 이 들어 있다.
- 그 type 은 기본 데이터 type 8 가지 혹은 참조 data type 이다.
- 메소드 안에서 만드는 지역변수는 stack 영역에 만들어 진다.
- 지역변수는 메소드가 실행중에 만들어 졌다가 해당 메소드가 종료(리턴)되면 사라진다.
- </선생님 필기>

- field는 사물함 영역 안에 만들어지지만 지역변수는 메모리 내 stack 영역에 만들어진다.

- 참조값에 . 을 찍은 것은 객체의 저장소를 참조하거나 참조값의 기능을 사용하기 위함이라고 봐도 됨

- 연두색 동그라미, () : 메소드라고 알려주는 거임
- : 다음에는 data type이 선언되있음

- 자바는 타입이 안 맞으면 아예 호출이 안된다

* 3항 연산자<br>
콜론의 좌촉이 true일때 값  / 우측이 false 일때 값<br>
구조 : isWait(1번) ? "기다려요"(2번) : "기다리지 않아요"(3번); -> 총 3개의 구조를 가지고 있음

----------------------------------------------------------------------------------------------------------------------------------
java 에서의 클래스 (class)

* java에는 static , stack , heap 세가지 영역이 있다
    - static 영역 위에는 클래스가 만들어진다.(클래스 째로 가능하며 field와 method도 추가할 수 있다.)
    - stack 영역에는 지역변수가 만들어진다.
    - heap 영역은 객체가 만들어진다.

* class의 구조
public class 클래스명 {

}

1. 객체의 설계도 역할
    - 해당 클래스로 객체를 만들었을 때(new) 어떤 field(저장소) 와 어떤 method(기능) 를 가지게 할지를 설계할 수 있다.

2. data type 역할
    - 지역변수나 필드를 만들때 선언하는 data type이 역할을 할 수 있다.
    - 변수나 필드의 사용 설명서에 해당된다.

3. static field 혹은 static method를 포함하는 역할
    - 필요에 따라서 객체에 필드나 메소드를 만들지 않고 클래스 자체에 만들어 놓을 수도 있다.
    

-------------------------------------------------------
#20220726
<br>
클래스와 관련해서 앞으로 사용할 클래스를 모두 직접 만들 필요는 없다.
- java에서 기본적으로 제공되는 클래스를 import해서 사용
- 추가로 필요한 유틸리티를 인터넷에서 다움 받아 import 후 사용
- 직접 만들어서 사용<br>
총 3가지의 케이스로 클래스를 사용할 수 있다.
<br>
java에서 기본 제고앻주는 클래스 중에 java.lang 패키지 안에 속해있는
String, System 등의 클래는 import 하지 않아도 기본클래스처럼 사용할 수 있다.

<br>
java 로 프로그래밍을 하는 방법
<br>
heap 영역에 있는 객체의 필드나 메소드를 활용해서 원하는 동작을 하거나
<br>
static 영역에 있는 클래스의 static 필드나 static 메소드를 활용해서 원하는 동작을 한다,

- 특정 작업을 할 때 어떤 type 객체가 필요한지를 학습해야한다.
- 어떤 type 객체의 참조값을 어떻게 얻어내는지를 학습해야한다.<br>
    필요한 객체를 직접 new 하거나,<br>
    이미 생성된 객체를 참조하거나<br>
    메소드를 호출해서 리턴되는 객체를 주로 활용한다.<br>
<br>
[랜덤한 정수를 하나 얻어내서 콘솔창에 출력하는 프로그래밍을 하고 싶다]
<br>
필요한 객체
1. 랜덤한 정수를 만들어주는 객체 -> new Random();
2. 콘솔창에 문자열을 출력해주는 객체 -> sysout
<br>
[키보드로부터 문자열을 입력받아서 콘솔창에 출력하는 프로그래밍]
<br>
필요한 객체
1. 키보드로부터 문자열을 입력 받는 기능을 가지고 있는 객체 -> new Scaner();
2. 콘솔창에 문자열을 출력해주는 객체 -> sysout

----------------------------------------------------------------------
'''java
            public int num = 999;
	
	public static void main(String[] args) {
		
		System.out.println("num : "+this.num);
	}
'''
이건 말이 아예 안됨. static 영역에서의 this. 은 사용을 할 수 없다.
'''java
public static int num = 999;
	
	public static void main(String[] args) {
		
		System.out.println("num : "+MainClass05.num);
	}
'''

올바른 코드(MainClass05.은 생략할 수 있지만 일단은 붙이는 습관을 들이자)

----------------------------------------------------------------------
#20220728 오전
!vsc에서 git 사용방법 정리할 것!
eclipse에서 git 사용하는 방법

프로젝트까지 생성하고 오른쪽마우스 우클릭후 team -> share project
init 폴더를 새로 만들면서 거기에 init을 하는게 맞다
create - browse - 바탕화면 MyGitRepo 선택 - 하고 폴더명 하나 적기 - finish
그러면 희한한 표시들이 막 생김(자동으로 옮겨감)
그다음 생성한 폴더에서 git bash를 연다

그리고 마우스 우클릭 team - commit 누르면 commit에 관련 정보 제공창 뜸

unstaged changes에 있는 목록들을 밑의 staged changes로 끌어내리면 add가 되는거임
이때 파일에 검은색 바탕 * 표시가 나타남

오른쪽칸에 commit 메세지를 넣고 commit 시키면 됨
git으로 관리되는 파일들은 노란색 원기둥 표시가 나타남

그리고 수정 후 add 안된 파일들은 이름 옆에 > 표시가 나타남

team - show in history를 보면 git log처럼 commit한 이력에 대해서 볼수 있다
이 때 각각의 히스토리에 마우스 커서를 두고 우클릭을 하면 별도의 다른 작업도 할 수 있다

* branch 만드는 방법
team - switch to - new branch - 생성하면 왼쪽 explorer에 브랜치명이 보인다

* merge 방법

team - merge - merge할 브랜치 선택하면 merge가 됨

* file을 통째로 올리게 되면 설정파일까지 같이 올라가기 때문에 다른 환경에서 할때 에러가 발생할 수 있다

Dto 생성하는 방법
1. 필드 정의
2. default 생성자 만드리
3. 커서 가져다 놓고 마우스 우클릭 - source - 밑에서 세번째꺼 클릭하면 양식 다 만들어짐
4. generate setters and getters - select all 하면 됨


------------------------------------------------------------

자식클래스 생성자 호출하면 슈퍼클래스 생성자도 같이 호출됨
this.는 자기자신의 참조값 호출
super.는 부모클래스의 참조값 호출

super()는 부모생성자를 호출하는 것을 의미함
