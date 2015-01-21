# Config-Set
Configuration Repo
git config --global --list
#view config settings can also use $cat ~/.gitconfig 
git config --global user.name edbird1
git config --global user.email edbird1@yahoo.com  
git config --system color.ui true
git config --global core.autocrlf true
git config --global push.default simple
git config --global pull.rebase true
#remove the fetch and merge in commit
git config --global rerere.enabled true
#Record all fixes to merge conflicts
git config --global alias.s status -s
#Shorten status
git config --global alias.lg log --oneline --decorate --all --graph
#shorten and pretty log
