# Delete merged-away branches

Removes local branches whose remote branch is gone.

```sh
git fetch -p && git branch -vv | awk '/: gone]/{print $1}' | xargs -r git branch -d
```
