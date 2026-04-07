##260406##
git -- version
git config --global user.name "Sungyeon.Park"
git config --global user.email "sypdana@gmail.com"
pwd
cd /d
ls
mkdir git_test
cd git_test
git init : 저장소 복제하기
ls -al
touch sample.txt
echo "Hello Git" > sample.txt
cat sample.txt
git status
git add sample.txt
git commit -m "first commit"
echo "수정 1" >> sample.txt
git status
git add .
git commit -m "두번째 커밋"
git log
 git remote add origin https://github.com/sypdana-sys/git-learner.git
 : 새로운 원결 저장소 추가하기
 git remote -v
git push -u origin main
echo "수정 2" >> sample.txt
git commit -m "세번째 커밋"
git push


cd /d
git clone git@github.com:sypdana-sys/git-learner.git : 저장소 복제하기
cd git-learner
cat sample.txt
git pull
git log
git reset --hard <주소>


*rm -rf하지 않기



