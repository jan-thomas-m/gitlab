# gitlab
A repo to test git stuff in...


## ruleset

```
gh api \
  --method POST \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2026-03-10" \
  /repos/jan-thomas-m/gitlab/rulesets \
  --input - <<< '{ ...
```


```
gh api --method POST -H "Accept: application/vnd.github+json" -H "X-GitHub-Api-Version: 2026-03-10" /repos/jan-thomas-m/gitlab/rulesets --input .github/rulesets/main-branch-protection.json

```

```
gh ruleset list
gh api --method DELETE -H "Accept: application/vnd.github+json" -H "X-GitHub-Api-Version: 2026-03-10" /repos/jan-thomas-m/gitlab/rulesets/id...

```
