…or create a new repository on the command line

echo "# git-cmd" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/haoyi2015/git-cmd.git
git push -u origin master


…or push an existing repository from the command line

 git remote add origin https://github.com/haoyi2015/git-cmd.git
git push -u origin master