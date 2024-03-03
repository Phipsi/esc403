# esc403
ESC 403 Data Science Project Repository

## Project Members
- Julie Tschanz
- Philipp Wyss
- Damian Brühlhaart
- Mike Krähenbühl


## Project Proposal
tbd


## Project Structure
General project structure is derived by "Good enough practices in scientific computing" - G. Wilson et al.
```yml
📁 my_project
|--📁 doc  # text associated documents
|--📁 data  # raw data and metadata
|--📁 results # files generated during cleanup and analysis
|--📁 src # project source code / functions / reports / dashboards
|--📁 bin # external scripts or compiled programs
```

## Branching Strategy (Git)

1. Develop in your personal "development" branch
2. Merge to main when ready and tested

```mermaid
---
title: Example Git diagram
---
gitGraph
   commit id: "initial commit"
   branch philipp
   checkout philipp
   commit
   commit
   checkout main
   merge philipp
   commit
   branch julie
   checkout julie
   commit
   merge julie
```
