# Gitlet

Gitlet is smaller, worse version of the Git version-control system, written
in Java as part of Berkeley's CS61B datastructures course.

This repository serves as a public description of the project. For plagarism
prevention purposes, the actual code is in a private repository. If you would
like to view the project code, please reach out to me.

## Specifications

For detailed project specifications, [go here](https://inst.eecs.berkeley.edu/~cs61b/fa19/materials/proj/proj3/). Gitlet
implements most of the important Git commands in a local-only repo.

### Commands

The following commands are implemented as part of the project:

- `init`
- `add`
- `commit`
- `rm`
- `log`
- `global-log` (project specific)
- `find` (project specific)
- `status`
- `checkout`
- `branch`
- `rm-branch` (equivalent to `git branch -D`)
- `reset`
- `merge`
