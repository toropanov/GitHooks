That's initial comment for project. It's still in WIP and not ready for daily usage.

The main idea is to create global hooks for daily checks of commit messages and etc.

## Available hooks
- [x] commit-msg


## Install

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
