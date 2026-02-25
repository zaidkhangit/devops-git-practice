setup & config
 - git init 
 - git config --global user.name="...."
 - git config --list
 - git config --global user.email="..."
basic workflows
 - git add
 - git commit
 - git merge
 - git swich 
 - git branch
 - git stash
 - git rebase
viewing changes
 - git logs
 - git logs --oneline


GIT-CLI
- gh auth login
- gh auth logout
- gh create repo repo-name --public --description""
- git repo view 'myrepo' --json(for specific field) --web
- git repo list
- gh issue create \ --title\ --body \--base(which branch)\ --repo
- gh issue list  --repo --state open
- gh issue view 1 --repo
- gh issue close 
- gh pr create \ --title \ --body \ --base(branch to merge in) \ --head(branch u push)
- gh pr list --repo --state open
- gh pr merge --repo (can use --squash / --rebase)
- gh pr create --reviewer usrname 

