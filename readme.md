# gh repo-collab

_* This is a fork of [mislav/gh-repo-collab](https://github.com/mislav/gh-repo-collab) with some personal improvements_

A GitHub CLI extension to manage repository access for users and organization teams.

```
gh extension install mislav/gh-repo-collab
```

```
Usage: gh repo-collab list [<repo>]
       gh repo-collab add <repo> <handle> [--permission {pull|triage|push|maintain|admin}]
       gh repo-collab add <repo> < users-file.txt
       gh repo-collab remove <repo> <handle>

Handle may be a GitHub user login handle or `<org>/<slug>' for an organization team.
```
