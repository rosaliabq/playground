# README

### First steps

Configure Git:

```bash
git config --global user.name XXX
git config --global user.email YYY
git config --global color.ui true
##check all changes done:
git config --global --list
```

### Git Basic

```bash
#start repo
git init 					
#git status
git status  				
##git adds:
git add <file> 	#add file
git add -A	#add ALL files
git add --ignore-removal #add new and modified files, without deteled
git add -u #add modified and deteled, without new files
##git resets:
git reset --soft <COMMIT> #remove commits until <COMMIT> but keeps code changes
git reset --hard <COMMIT> #remove commits and code until <COMMIT>
git reset --hard HEAD #discards all local changes
```

