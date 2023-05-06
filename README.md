# Git Precommit hook

Global basic hook for daily checks of commit messages.

Current state - `WIP`.

## Usage
..

## Installation

Create directory with hooks in home directory. And set permission for.

```
mkdir ~/.githooks
chmod ug+x ~/.githooks
```

Then copy your exact hooks to created folder.
And set permissions for them also.

```
cp commit-msg ~/.git-hooks/
chmod ug+x ~/.git-hooks/commit-msg
```

And finally - Make them to trigger globally on all your git commands.

```
git config --global core.hooksPath ~/.git-hooks
```

## TODO

- [ ] Finish README file
<!-- https://stackoverflow.com/questions/229551/how-to-check-if-a-string-contains-a-substring-in-bash -->
