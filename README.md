# Git

## Bundle 1

### Exercise 1
  
>Git Exercise One Terminal History
```zsh
 1118  git branch -M main
 1119  git add -A
 1120  git commit -m "Add HTML and CSS Files"
 1121  git push --set-upstream origin dev
 1122  git push --force origin main
 1123  git checkout -b dev
 1124  git push --set-upstream origin dev
 1125  git checkout -b test
 1126  git checkout dev
 1127  git branch -D test
```

### Exercise 2
  
>Git Exercise Two Terminal History
```zsh
 1135* git stash -m "Add Home Page"
 1136* git add -A
 1137* git stash -m "Add Home Page"
 1138  ls
 1139  git add -A
 1140  git stash -m "Add Home Page"
 1141  ls
 1142  git status
 1143  git add -A
 1144  git status
 1145  clear
 1146  git stash -m "Add About Page"
 1147  git add -A
 1148  git stash -m "Add Team Page"
 1149  git stash list
 1150  git stash pop stash@{1}
 1151  git stash list
 1152  git stash pop stash@{1}
 1153  git commit -m "Add About and Home Page"
 1154  git status
 1155  git push --set-upstream origin dev
 1156  clear
 1157  git stash list
 1158  git stash pop stash@{0}
 1159  git add -A
 1160  git status
 1161  git reset --hard 
```

## Bundle 2

### Exercise 1
  
>Git Exercise 3 Terminal History
```zsh
 1183  git checkout -b ft/bundle-2
 1184  git push origin ft/bundle-2
 1185  git add -A
 1186  git commit -m "Add services Page"
 1187  git status
 1188  git push origin ft/bundle-2
 1189  clear
 1190  git push --set-upstream origin ft/bundle-2
```

### Exercise 2
  
>Git Exercise 4 Terminal History
```zsh
 1202  git status
 1203  git add -A
 1204  git commit -m "Add ML models as a service"
 1205  git push
 1206  git checkout main
 1207  git add -A
 1208  git commit -m "Add Machine Learning Models as our service"
 1209  git push
 1210  git checkout ft/service-redesign
 1211  ls
 1212  git diff
 1213  git merge main
 1214  git diff
 1215  git merge main
 1216  git add services.html
 1217  git status
 1218  git commit
 1219  git push
```

## Bundle 3

### Exercise 1
  
>Git Exercise 1 Terminal History
```zsh
 1357  git checkout -b ft/team-page
 1358* clear
 1359* git status
 1360* git add team.html
 1361* git commit -m "Feat: Add Team Page"
 1362* git push
 1363* git checkout main
 1364* git checkout -b ft/contact-page
 1365* git checkout ft/team-page
 1366* git log
 1367* git checkout ft/contact-page
 1368* git cherry-pick c02b488a19dc6edd8d5b871b6db4552e4718da5f
 1369* ls
 1370* git status
 1371* git add contact.html
 1372* git commit -m "Feat: Add Contact Page"
 1373* git push
 1374* git status
 1375* git checkout -b ft/faq-page
 1376* clear
 1377  git checkout ft/contact-page
 1378  git checkout ft/faq-page
 1379  git add faq.html
 1380  git commit -m "Feat: Add FAQ Page"
 1381  git push
 1382  git log
 1383  git revert 0491180ac567d34745069e62e0938078ef0aade3
 1384  git status
 1385  git push
```

