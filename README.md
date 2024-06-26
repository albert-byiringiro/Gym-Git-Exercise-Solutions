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

### Exercise 2
  
>Git Exercise 2 Terminal History

```zsh
 1392  git checkout -b ft/home-page-redesign
 1393  git checkout main
 1394  git add -all
 1395  git add -A
 1396  git status
 1397  git commit -m "Feat: Add Homepage content"
 1398  git status
 1399  git checkout ft/home-page-redesign
 1400  git rebase main
 1401  git log
 1402  clear
 1403  git status
 1404  git add -A
 1405  git commit -m "Feat: Add My Achievements of this year"
 1406  git push
```

## Bundle 4

### Exercise 1
  
>Git Exercise 1 Terminal History
```zsh
 1430  git checkout main
 1431  clear
 1432  git log
 1433  git remote add git-copy https://github.com/albert-byiringiro/git-exercise-clone.git
 1434  git remote
 1435  git add home.html
 1436  git commit -m "Feat: Add Ebenezer Motto"
 1437  git push
 1438  git push git-copy
```

### Exercise 2
  
>Git Exercise 2 Terminal History
```zsh
 1446  git checkout -b ft/footer
 1447  git add footer.html
 1448  git commit -m "Feat: Add footer file"
 1449  git status
 1450  git add footer.html
 1451  git commit -m "Feat: Add footer content"
 1452  git status
 1453  git push
 1454  git push --set-upstream origin ft/footer
 1455  git checkout main
 1456  git checkout -b ft/squashing
 1457  git merge --squash ft/footer
 1458  git log
 1459  git status
 1460  git commit -m "footer changes squashing"
 1461  git log
 1462  clear
 1463  git push origin ft/squashing
```

## Bundle 5

### Exercise 1
  
>Git Exercise 1 Terminal History
```zsh
- On your github repo enable github pages
- Check if the link is publicly visible to anyone
```

### Exercise 2
  
>Git Exercise 2 Terminal History
```zsh
 1494  git add index.html
 1495  git commit -m "feat: rename the title"
 1496  git push
```

## Bundle 6

### Exercise 1
  
>Git Exercise 1 Terminal History
```zsh
 1780  git checkout -b ft/menu
 1781  git status
 1782  git add -A
 1783  git commit -m "Feat: Menu page for our restaurant"
 1784  git push
 1785  git push --set-upstream origin ft/menu
```

### Exercise 2
  
>Git Exercise 2 Terminal History
```zsh
 1821  git checkout -b fx/contact
 1822  git add -A
 1823  git commit -m "Fix: Change file from index-4 to contact"
 1824  git push
 1825  git push --set-upstream origin fx/contact

```

### Exercise 3
  
>Git Exercise 3 Terminal History
```zsh
 1832  git add -A
 1833  git commit -m "Fix: Change telephone number"
 1834  git push

```

# Git advanced Exercises

## Refining Git History

### Exercise 1: Missing File Fix
```zsh
2914  touch test{1..4}.md
2915  git add test1.md && git commit -m "chore: Create initial file"\n
2916  git add test2.md && git commit -m "chore: Create another file"\n
2917  git add test3.md && git commit -m "chore: Create third and fourth files"\n
2918  git status
2918  git add test4.md
2919  git log
2920* git commit --amend -m "chore: Create third and fourth files"
2921 git status
2922 git log
```

### Exercise 2: Editing Commit History

```zsh
# Start interactive rebase for the last two commits
git rebase -i HEAD~2

# Editor will open, change 'pick' to 'reword' for the commit to be modified, then save and close

# Amend the commit message
git commit --amend -m "chore: Create second file"

# Continue the rebase
git rebase --continue

# Verify the commit history
git log

```

### Exercise 3: Keeping History Tidy - Squashing Commits:

```zsh
# Start interactive rebase for the last two commits
git rebase -i --root

# Editor will open; change 'pick' to 'squash' for the second commit, then save and close

# Edit the commit message to combine them meaningfully, then save and close

# Verify the commit history
git log
```

### Exercise 4: Splitting a Commit

```zsh
# Reset the last commit, keeping changes in the working directory
git reset HEAD~1

# Stage and commit test3.md
git add test3.md
git commit -m "chore: Create third file"

# Stage and commit test4.md
git add test4.md
git commit -m "chore: Create fourth file"

# Verify the commit history
git log
```

### Exercise 5: Advanced Squashing:

```zsh
# Start interactive rebase for the last two commits
git rebase -i HEAD~2

# Editor will open; change 'pick' to 'squash' for the second commit, then save and close

# Edit the commit message to combine them meaningfully, then save and close

# Verify the commit history
git log

```

### Exercise 6: Dropping a Commit:


```zsh
# Verify the commit history
git log

# Start interactive rebase for the last two commits
git rebase -i HEAD~2

# In the editor, change 'pick' to 'drop' for the unwanted commit, then save and close

# Verify the commit history
git log

```

### Exercise 7: Reordering Commits


```zsh
# Check the current commit history
git log --oneline

# Start interactive rebase for the last three commits / git for all commits on the repo: git rebase -i --root
git rebase -i HEAD~3 

# In the editor, change the order of the commits, then save and close

# If there are conflicts, resolve them and continue the rebase
git rebase --continue

# Verify the commit history
git log --oneline

```

### Exercise 8: Cherry-Picking Commits:


```zsh
# Create and switch to a new branch
git checkout -b ft/branch

# Create the file with some content
echo "This is test file 5." > test5.md

# Stage and commit the new file
git add test5.md
git commit -m "Implemented test 5"

# Switch back to the main branch
git checkout main

# Get the commit hash from the ft/branch
git log ft/branch --oneline

# Cherry-pick the commit into the main branch
git cherry-pick 6662094

# Verify the commit history and the presence of the file
git log --oneline


```