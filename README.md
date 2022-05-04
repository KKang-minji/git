# git


```cd ~/Documents/abc``` 이런식으로 파일 들어갈 폴더 만든 후 ```git init``` 실행

바로 ```git status```실행하면 
```
On branch master
No commits yet 
nothing to commit (create/copy files and use "git add" to track) 
```
과 같은 오류가 나옴 👉 커밋 내용이 없다는 뜻

```echo '파일의 내용' >> oo.txt``` 사용하여 텍스트 파일 하나 만든후
```git status``` 하면 
**Untracked 상태**로 나옴
아직 git add나 git commit을 하지 않았기때문이고 Git이 추적관리 하고 있지 않음
