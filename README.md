# Apollo-Kotlin-QraphQL-Jetpack

# Git workflow

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true, 'showCommitLabel':true}} }%%
      gitGraph
      commit
      branch destagev order: 1
      commit
      branch dev order: 2
      commit
      branch feature order: 3
      commit
      commit
      commit
      checkout stage
      merge main
      checkout dev
      merge feature
      checkout feature
      commit
      commit
      checkout dev
      merge feature
      checkout main
      merge dev tag:"release 1.2.3"

```
