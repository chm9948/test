1. 저장소 만들기
git init

2. 저장소 받아오기
git clone C:\Users\최현민-PC\test

3. 추가
git add *
git commit -m "설명~~"

4. push
git push origin master(feature_x)
git remote add origin https://github.com/chm9948/test.git

5. branch 
- feature_x branch 만들기
git checkout -b feature_x

- feature_x branch 삭제
git branch -d feature_x

- master 로 checkout 
git checkout master 
git checkout feature_x

git push origin feature_x

