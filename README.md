# Apollo-Kotlin-QraphQL-Jetpack

# Git workflow

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true, 'showCommitLabel':true}} }%%
      gitGraph
      commit
      branch dev order: 1
      commit
      branch stage order: 2
      commit
      commit
      commit
      branch feature order: 3
      commit
      commit
      commit
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
