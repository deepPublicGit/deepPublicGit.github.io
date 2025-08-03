---
layout: opensource
type: opensource
image: img/opensource/kestra-icon.png
title: "kestra-io"
date: 2025-08-01
published: true
repourl: https://github.com/kestra-io/kestra
labels:
  - java
  - workflow
  - templating-engine
  - functions
summary: "Implemented new feature to enhance pebble functions for Workflow Orchestration Platform Kestra."
---

[`Kestra`](https://kestra.io/) is an open-source, event-driven orchestration platform that makes both scheduled and event-driven workflows easy. By bringing Infrastructure as Code best practices to data, process, and microservice orchestration, you can build reliable workflows directly from the UI in just a few lines of YAML.

[`Pebble`](https://kestra.io/docs/concepts/pebble) is a Java templating engine, Kestra uses it to dynamically render variables, inputs, and outputs within the execution context.

## Key Updates in This Project

### Clarification and Implementations
- Feature required implementation of fileSize, fileExists and isEmpty functions.
- Clarified requirements as fileSize already existed and output of pebble functions.
- Closed and Merged feature with PR [#7191](https://github.com/kestra-io/kestra/pull/7191)

### Testing & Deployment
- Included tests for both pebble functions with integration tests passing.

### Miscellaneous Improvements
- Various minor enhancements for readability and maintainability.

For a deeper dive into specific improvements, check out:
- [Commit history](https://github.com/kestra-io/kestra/compare/develop...deepPublicGit:kestra:addnewpebble6888) for a detailed breakdown of changes.
