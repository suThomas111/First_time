### Basic command of git
> git pull(update local from github)
git push(update github from local git version, so need to commit first)
git add(add file want to commit, 把當下檔案的內容複製到暫存區，若add後修改要重新add)
git add .
git add *.cpp
git status
>> 1.untracked:new file never been added 
>> 2.tracked:file had been commit before or added currently
>> 3.staged:being add currently
>> 4.commited:had been commited before
git commit -m "建立還原點"
git log(show commit history)
git log --oneline(show commit history briefly)
git diff 3ce13c5 -- main.cpp(compare difference between old version and current)
git checkout 3ce13c5 -- main.cpp(move to old version, remember commit again if need)
git init(add git to record each commit version)