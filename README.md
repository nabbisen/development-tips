# development-tips

## Git

* Convert A Local repo to a remote one
```
git init
git add.
git commit -m "Initial commit"
git remote push add origin
```

* Delete file histories completely
```
git filter-branch --tree-filter 'command like rm -rf xxx' HEAD --all
git reflog expire --expire=now --all && git gc --aggressive --prune=now
git push --force origin master
```

* Check changed files
```
git ls-files --other --exclude-standard
```

* angular-ui-bootstrap
- https://www.google.co.jp/search?q=angular+ui+bootstrap+dropdown+init+value&ie=UTF-8&oe=UTF-8&hl=ja-jp&client=safari
- https://www.google.co.jp/search?q=angular+ui+bootstrap+dropdown+selected&client=safari&hl=ja-jp&prmd=vin&ei=E6ExWML6H8GY0QT737mAAQ&start=10&sa=N&biw=375&bih=628
- http://www.infragistics.com/community/blogs/dhananjay_kumar/archive/2015/06/29/how-to-work-with-the-bootstrap-dropdown-in-angularjs.aspx
- http://stackoverflow.com/questions/32983105/angularjs-ui-select-dropdown-default-value
- http://stackoverflow.com/questions/33278097/how-to-display-the-selected-item-on-bootstrap-dropdown-title-in-angular
