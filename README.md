## git command summary

`git remote` - Show remote servers

`git branch -a` - List all branches

`git branch -r` - Show remote tracking branches

`git remote show origin` - Show detailed configuration

`git branch -vv` - List local tracking branches and their remotes

`git branch --track 'branch name' origin/'branch name'` - Create local tracking branch

## github summary

|            | git             | github |                                                         |
| ---------- | --------------- | ------ | ------------------------------------------------------- |
| Repository | Local           | Remote | `git remote add origin URL`                             |
| Branches   | Local-Tracking  | Remote | `git branch --track 'branch name' origin/'branch name'` |
|            | Remote-Tracking |        | `git pull/push origin branch`                           |
