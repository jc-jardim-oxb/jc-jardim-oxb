# Useful snippets
Signing all commits from a specified commit
```
git rebase --exec 'git commit --amend --no-edit -n -S' -i <hash>
```
