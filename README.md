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
  
>Git Exercise Three Terminal History
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