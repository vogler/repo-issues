# repo-issues

Running `./repo-issues` lists all issues mentioned in the current repository. Currently only github is supported but open to PRs.

The first group shows issues created by the current `git config github.user`.
TODO grouping/sorting.


## Why?

List issues of dependencies and their status.
If one collects all issues in a separate file (e.g. README.md) or own issue, the context to the code is missing; if one puts the links as comments in the code, the overview is missing.
