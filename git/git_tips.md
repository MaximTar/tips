### Delete the last commit

```bash
git log

commit a
...
commit b
...

git push origin a #(last commit name)
git reset HEAD^ --hard
git push origin -f
```
