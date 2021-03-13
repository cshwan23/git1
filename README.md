# git1
깃(GIT) 공부(1)



<h2>git(문서)</h2>
한 두개의 문서를 나만 가지고 있는게 아니다. 
깃은 복잡하다.
GIT (버전 관리 시스템)

<h2>GIT의 필요성</h2>
- 수 많은 문서를 관리해야할 경우<br>
- 이 문서들이 자주 변경되는 경우<br>
- 문서의 변경 이력을 체계적으로 관리해야하는 경우<br>
- 문서의 조작을 막아야 하는 경우<br>
- 문서를 안전하게 백업해야 하는 경우<br>
- 문서를 다른 사람과 공유해서 공동으로 작업하는 경우<br>
- (문서: 텍스트 문서에서부터 이미지,소스코드를 망라한 모든파일)<br>

<h2>GIT 사용 목적 3가지</h2>

1. 버전관리 
2. 백업 
3. 협업


<h2>백업</h2>

언제 고장날지 모른다.<br>
github.com 이라는 백업을 해주는 컴퓨터(사업자)가 있다.<br>


- 지역저장소(내컴퓨터에 있는 파일)<br>
- 원격저장소<br>

<h2>push</h2>
밀어넣는다 내컴퓨터의 파일을 원격저장소에.
<h2>pull</h2>
당겨온다. 원격장소에서 내 컴퓨터로.
<p>이게 동기화이다</p>


<h2>협업</h2>
push(밀어넣다) -> 원격저장소 -> pull(땡겨오다)<br>

다른사람 컴퓨터(git 홈페이지) 원격저장소 <br>

<h2>GIT의 종류</h2>
git client<br>
git client의 종류<br>

-Sourcetree : git프로그램<br>

<h2>githurb명령어 </h2>

$ git log : 버전의 목록을 보여줘 <br>
$ git status : 깃의 상태를 보여줘 <br>
$ git commit -am "메시지내용" <br>
$ git push : 야 업로드해 <br>

# git2

# CLI 

# 저장소(repository)만드는 방법
- 깃 에게 특정한 디렉토리를 버전관리하고싶으니까 거기서 관리해를 시킬거다.
- 다큐멘트라는 폴더에 깃이라는 디렉토리 만듬
- cd Dcument/git 이라는 디렉토리를 만듦.
<h4> mkdir hello-git-cli </h4>

<h4> git init . </h4>
: 난 이제부터 여기서 버전관리할 거니까너 이 현재 디렉토리를 이제 버전관리하기 시작해

<h4> cd .git </h4>
이 .git 에 파일에 저장이 될거다.

<h4> ls -al </h4>
절대 이제 .git을 삭제하면 안된다 이제~

# 버전 생성

# Workingtree
버전으로 만들어지기 전단계<br>
수정하는곳 수정한 파일들

# staging Area
버전을 만드려고하는 파일들<br>
버전을 만드려고할 때 파일이 10면 다 10개 버전으로 만들게 아니라 <br>
파일 딱 2개만 버전으로 만들고 싶으면 staging Area 에 올리는거다.

# repository
만들어진 파일들

<hr>

# $ git statius
나의 .git의 상태

# git add hello1.txt
staging area에 올려라는 명령어<br>
change to be committed: 라고 뜬다.


# git commit -m "메세지 입력"
커밋할 파일들을 깃에게 버전으로 만들어<br>
이렇게 하면 버전이 생성된다.<br>
그럼 리파지토리로 가게된다.

# git status 
깃의 상태를 보는데<br>
nothing to commit, working tree clean<br>
버전으로 만들것이 없다.

# git log
버전이 잘되었는지 확인하기 위한 명령어<br>
버전의 역사를 보는 명령어

# q
나가는 명령어

# git add -> git commit -m "" 







