echo "# Test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:github-name/repositories-name.git
git push -u origin master
