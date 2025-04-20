git init
git add .  (전에 다른 저장소에 저장했던 파일은 인식을 못해서 수정해야 add 할 수 있다.) - 수정 = git pull -rebase origin main 하고 푸시하면 됨
git commit -m "modify"
git remote add origin https:// ~~~
git push -u origin main
git remote remove origin
