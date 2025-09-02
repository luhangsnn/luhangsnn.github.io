To make updates:
notablog generate .
git add .
git commit -m "Update site"
git push origin master
git subtree push --prefix public origin gh-pages
