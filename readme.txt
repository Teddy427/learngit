git init : initialize the git
git add <file name> : add a file
git commit -m "message" : submit the file to the git and add a description
git status : query the status of git
git diff <file name> : query the difference between the file now and the file in git
git log : query the history of 'commit'
git reset <status> <version> : reset the HEAD pointer
<status> : --hard/--soft/--mixed -> committed / uncommitted / unadded
<version> : HEAD^/HEAD^n/commit id -> to previous version / to previous n-th version / to the version with given id
git reflog : query the history of command 