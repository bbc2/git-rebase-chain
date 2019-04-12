# Git-rebase-chain

Rebase several Git branches on top of each other.

## Example

```
> git-rebase-chain master feature-1 depends-on-feature-1
master → feature-1
First, rewinding head to replay your work on top of it...
Applying: Rename variable
Applying: Add feature 1
feature-1 → depends-on-feature-1
First, rewinding head to replay your work on top of it...
Applying: Add feature that depends on feature 1
```
