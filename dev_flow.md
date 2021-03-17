# Development Flow
## STEP1 Create Remote Repository

Create in Github web page.

## STEP2 Clone
```
git clone <remote-repository>
```

## STEP3 Create 'develop' branch and child branch
```
git branch dev
git checkout -b <branch name>
```

## STEP4 Create and edit files in working tree

## STEP5 Check modified files
```
git status
```

## STEP6 Add modified files to stage
```
git add <files>
```

## STEP7 Local commit
```
git commit -m '<commit message>'
```

## STEP8 Apply latest REMOTE repository to LOCAL one
```
git pull --rebase origin dev
```

### STEP8-1 If conflict occurs

### fix conflicted files.

### Add modified files to stage

```
git add <modified files>
```

### Complete rebase
```
git rebase --continue
```

## STEP9 Upload files to remote repository
```
git push origin dev
```

## STEP10 Pull request
Send pull request in Github web ui.


## STEP11 Repeat review-merge steps from step4 to 11 (if you need)

## Optimize local repository
```
git checkout dev
git pull
```
