# Apollo-Kotlin-QraphQL-Jetpack

# Git workflow

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true, 'showCommitLabel':true}} }%%
gitGraph
  commit
  commit
  branch dev
  commit
  commit
  commit
  checkout dev
  commit
  commit
  branch feature
  commit
  commit
  checkout dev
  commit
  commit
  checkout stage
  commit
  commit
  merge dev
  commit
  commit
  checkout main
  commit
  commit
  merge stage
  commit
  commit
  merge dev tag:"release 1.8.1"

```
