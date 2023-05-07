# Git Precommit hook

It could be quite useful to check every commit message before submission. It keeps your git log readable and prevents messages like 'WIP'.

The current state of development is `In progress`, but I already use it daily.

In case some of your projects have their own precommit hook, my hook would not prevent them from calling.

## Installation

Before you can run the precommit hook, you need to move it to your global (or not) hooks folder. Use three easy steps for

Create a directory with hooks in the home directory. And set permission for

```
mkdir ~/.git-hooks
chmod ug+x ~/.git-hooks
```

Then copy your exact hooks to the newly created folder and set permissions for them also.

```
cp commit-msg ~/.git-hooks/
chmod ug+x ~/.git-hooks/commit-msg
```

And finally, make them trigger globally on all your git commands.

```
git config --global core.hooksPath ~/.git-hooks
```
