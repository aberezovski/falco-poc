1. Create a branch

```shell
# git branch --delete old-branch

git branch enable-falco-rules
```

2. Use new created branch

```shell
git checkout enable-falco-rules
```

3. Commit the change

```shell
git add custom_falco_rules.yaml
git commit -m "enable rule 'Uncommon Process Execution'"
```

4. Push the changes back to Github

```shell
git checkout main
git push origin enable-falco-rules
```