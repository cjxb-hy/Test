echo "# Test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:cjxb-hy/Test.git
git push -u origin master
