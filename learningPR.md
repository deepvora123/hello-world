**Learning how to add a new pull request**


fork repo   :-  g/user/object -> g/rockingdeep/o
git clone g/user/object  remote-> origin
git remote add upstream g/rockingdeep/o   remote-> upstream  
git checkout test   branch-> test

*// Modify*

git add .
git commit -m "" 	changes-> test
git push remote upstream

PR from your branch-> origin/master
