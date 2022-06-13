# wherr-page

###  

~~~
npm run build

git config --global http.sslVerify "false"

git checkout -b gh-pages
git pull gh-pages
git add -f dist
git commit -m 'commit'
git subtree push --prefix dist origin gh-pages

~~~

