# noteMD
### Build android ( assemble ) - file APK
./gradlew app:assembleRelease
### bật Debug React-Native
adb shell input keyevent 82

### Create project react-native typeScript 
npx react-native init MyApp --template react-native-template-typescript

### git access denid
windown + R control /name Microsoft.CredentialManager


## BRANCHES

git branch	List all local branches.	
git branch -a	List remote and local branches.	
git checkout -b branch_name	Create a local branch and switch to it.	
git checkout branch_name	Switch to an existing branch.	
git push origin branch_name	Push branch to remote.	
git branch -m new_name	Rename current branch.	
git branch -d branch_name	Delete a local branch.	
git push origin :branch_name	Delete a remote branch.	

## LOGS

git log --oneline	Show commit history in single lines.	
git log -2	Show commit history for last N commits.	
git log -p -2	Show commit history for last N commits with diff.	
git diff	Show all local file changes in the working tree.	
git diff myfile	Show changes made to a file.	
git blame myfile	Show who changed what & when in a file.	
git remote show origin	Show remote branches and their mapping to local.	

## CLEANUP

git clean -f	Delete all untracked files.	
git clean -df	Delete all untracked files and directories.	
git checkout -- .	Undo local modifications to all files.	
git reset HEAD myfile	Unstage a file.	

## TAGS

git pull --tags	Get remote tags.	
git checkout tag_name	Switch to an existing tag.	
git tag	List all tags.	
git tag -a tag_name -m "tag message"	Create a new tag.	
git push --tags	Push all tags to remote repo.	

## STASHES

git stash save "stash name" && git stash	Save changes to a stash.	
git stash list	List all stashes.	
git stash pop	Apply a stash and delete it from stash list.	


