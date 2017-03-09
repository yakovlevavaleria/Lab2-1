git init 
git add . 
git commit -m “init” 
git remote add origin https://github.com/yakovlevavaleria/Lab2-1
git push origin master 
git checkout -b test 
git add . 
git commit -m “source files” 
git push origin test 
git pull origin test 
git checkout master 
git merge test –-no-ff -m “Merged master fixed conflict” 
git push origin master test 
