> :information_source: this log lists user most visible changes

> :warning: to find all changes use [changelog.txt](https://github.com/andry81-devops/gh-action--git-checkout/blob/master/changelog.txt) file in a directory

## 2022.10.30:
* changed: action.yml: `set-output` command is replaced in favor of `$GITHUB_OUTPUT` variable usage (details: https://github.blog/changelog/2022-10-11-github-actions-deprecating-save-state-and-set-output-commands/ )

## 2022.05.12:
* refactor: action.yml: rename for unique name on GitHub Marketplace

## 2022.05.04:
* new: action.yml: added `COMMIT_MESSAGE_PREFIX` to split an automated user commit message into prefix and suffix parts

## 2022.04.16:
* new: action.yml: added `mkdir-p` to allocate directories after checkout because the `actions/checkout` action script does cleanup a working copy directory before execution
