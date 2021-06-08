## Squashing or editing commits (Use with care):

```bash
git rebase -i --root
```

Look at .git/config

## Rebase (Use with care)

```bash
tig
git reflog
git checkout -b msg-correction
tig
git rebase HEAD^
git checkout -
git reset --hard HEAD^
tig
git reflog
git push
git push --force-with-lease
git checkout -
tig
git fetch
tig
git rebase origin/master
git push
git rebase -i origin/master
tig
git push --set-upstream origin msg-correction
```
