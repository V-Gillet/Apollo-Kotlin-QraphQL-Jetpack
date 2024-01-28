# Apollo-Kotlin-QraphQL-Jetpack

# Git workflow

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true, 'showCommitLabel':true}} }%%
      gitGraph
      commit
      branch stage order: 1
      branch dev order: 2
      checkout dev
      branch feature order: 3
      checkout feature
      commit
      commit
      commit
      checkout dev
      merge feature
      checkout stage
      merge dev
      checkout main
      merge dev tag:"release 1.2.3"

```
