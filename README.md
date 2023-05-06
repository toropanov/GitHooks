That's initial comment for project. It's still in WIP.

## Install

mkdir ~/.githooks
chmod ug+x ~/.githooks
chmod ug+x ~/.git-hooks/commit-msg
cp commit-msg ~/.git-hooks/
git config --global core.hooksPath ~/.git-hooks
