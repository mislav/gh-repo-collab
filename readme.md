# gh repo-collab

_* This is a fork of [mislav/gh-repo-collab](https://github.com/mislav/gh-repo-collab) with some personal improvements_

A GitHub CLI extension to manage repository collaborators.

```
gh extension install mislav/gh-repo-collab
```

```
Usage: gh repo-collab list [<repo>]
       gh repo-collab add <repo> <login> [--permission <string>]
       gh repo-collab add <repo> < logins-file.txt
       gh repo-collab remove <repo> <login>

Valid permission is one of: pull, triage, push, maintain, admin.
```
