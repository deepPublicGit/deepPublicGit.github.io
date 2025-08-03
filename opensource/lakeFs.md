---
layout: opensource
type: opensource
image: img/opensource/lakefs-icon.png
title: "lakeFS"
date: 2025-08-01
published: true
repourl: https://github.com/treeverse/lakeFS
labels:
  - go
  - refactoring
  - storage
  - git
summary: "Refactored codebase and docs to remove unused file storage permission for data version control tool LakeFS."
---

[`lakeFS `](https://lakefs.io/) is an open-source tool that transforms your object storage into a Git-like repository. It enables you to manage your data lake the way you manage your code.

CreateMetaRange was an api operation that allowed users to create [Meta Range](https://docs.lakefs.io/v1.63/understand/how/versioning-internals/) this is now managed internally by lakeFS and needs to be removed from public usage.

## Key Updates in This Project

### Clarification and Implementations
- Clarified requirements from which files the operation needs to be removed
- Closed and Merged feature with PR [#8552](https://github.com/treeverse/lakeFS/pull/8552/)

### Testing & Deployment
- Removed tests for createMetaRange and ensured all other tests passed.

### Miscellaneous Improvements
- Various minor enhancements for readability and maintainability.

For a deeper dive into specific improvements, check out:
- [Commit history](https://github.com/deepPublicGit/lakeFS/commits/fix/removecreatemetarange-%238528/?author=deepPublicGit) for a detailed breakdown of changes.
