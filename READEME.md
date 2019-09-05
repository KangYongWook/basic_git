# Git 기초
Git 기초 커맨드

## 기본 커맨드

 ~ 'git init': .git이라는 햣 폴더가 생성되며 깃으로 시작할때 최초입력

 깃을 지우고싶으면
 .git을 지우면된다
 rm -rf .git

git status  

git add READEME.md  :staging

git commit : commit

이메일이랑 이름입력

git commit -m 'first commit'

git log :commit history


깃은 해쉬라는 것으로 전송되기 때문에 문자하나의 변경에도 똑똑하게 알아내어 변화를 감지함 
우리가 인터넷을 사용할때 https를 사용하는것도 해쉬를 통해 전송하기때문에 보안성이 엄청뛰어남 2^160이라는 16진코드로 전송되어 역으로 복호화하는게 매우어려움 인터넷은 sha238이라는 업그레이드된 2^240? 버전을 쓴다


git commit -m "finish basic command"
