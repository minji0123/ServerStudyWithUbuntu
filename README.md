# ServerStudyWithUbuntu
서버 공부!😗 우분투 공부!😗

우분투를 공부하기 위해 만든 repository 
(이러면 좀 공부하겠징🙄)

---
<h2 id="table-of-contents">🔖 목차</h2>
<details open="open">
  <summary> 목차</summary>
  <ol>
    <li><a href="#pwd">◽ pwd</a></li>
    <li><a href="#cd">◽ cd</a></li>
    <li><a href="#ls">◽ ls</a></li>
    <li><a href="#mkdir">◽ mkdir</a></li>
    <li><a href="#cp">◽ cp</a></li>
    <li><a href="#mv">◽ mv</a></li>
    <li><a href="#rm">◽ rm</a></li>
    <li><a href="#vi">◽ vi</a></li>
  </ol>
</details>



---
## 기본 문법

<h3 id="pwd">◽ 현재 있는 위치: pwd</h3>

```bash
$ pwd
```
Print Working Directory

<h3 id="cd">◽ 폴더 이동: cd</h3>

```bash
$ cd /폴더이름
```
change directory   
폴더명을 입력하지 않으면 상위 폴더로 이동한다.

<h3 id="ls">◽ 경로에 있는 폴더 검색: ls</h3>

```bash
$ ls
```
list   
현재 위치한 폴더 안의 파일, 폴더 목록을 표시   
![''](/images/ls.png)   
리눅스 최상위 경로에 있는 폴더 이름들이다.  


|명령어|뜻|기타|
|------|---|---|
|-a|모든 항목 표시|숨긴파일 포함
|-d|폴더 정보 표시|정보만!
|-F|폴더 정보 표시|/(폴더). *(실행파일), =(소켓파일), @(링크)
|-l|폴더 정보 표시|항목 상세 정보들도 표시
|-m|각 항목들을 쉼표로 구분|
|-r|항목들을 역순으로 표시|
|-R|하위 폴더 내용들도 표시|
|-s|kb(키로바이트) 단위로 표시|
|-t|최종 수정시간을 기준으로 표시|
|-u|최종 엑세스 시간 기준으로 표시| 
|-x|실행 가능한 파일만 표시|


<h3 id="mkdir">◽ 폴더 생성: mkdir</h3>

```bash
$ mkdir 폴더이름
```
make directory  


<h3 id="cp">◽ 폴더 복사: cp</h3>

```bash
$ cp 복사대상파일 새파일이름 or ../경로
```
```bash
$ cp -r 복사대상폴더 새폴더이름 or ../경로
```
copy  


<h3 id="cp">◽ 폴더 이동: mv</h3>

```bash
$ mv 이동대상파일 새파일이름 or ../경로
```
move


<h3 id="rm">◽ 폴더 삭제: rm</h3>

```bash
$ rm 복사대상파일 새파일이름 or ../경로
```
```bash
$ rm -r 복사대상폴더 새폴더이름 or ../경로
```
remove  


<h3 id="vi">◽ 파일열기(생성, 편집): vi</h3>

vi 에디터 실행  
(:wq) 저장 후 종료