# Git Hooks

## Pre-Commit

You can bypass the hook using `git commit --no-verify`

Current checks:

* [WHITESPACE]
* [ESLINT]
* [SPELLING]
* [GIT_COMMIT_MESSAGE]

## Pre-requisite

```
▶ brew install aspell awk
▶ npm install -g eslint eslint-config-airbnb eslint-plugin-react
```

## Result

```
[WHITESPACE] --> 👍 LGTM
[ESLINT] --> 👍 LGTM
[GIT_COMMIT_MESSAGE] --> 🚫 Malformed git commit message. Re-edit? [y/n]

...
```

## Learn about Git Hooks

* [Atlassian's excellent guide](https://www.atlassian.com/git/tutorials/git-hooks)
* [Fit Commit](https://github.com/m1foley/fit-commit)
* [A Note About Git Commit Messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
