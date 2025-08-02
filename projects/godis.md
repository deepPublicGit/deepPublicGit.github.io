---
layout: project
type: project
image: img/godis/godis-square.png
title: "godis"
date: 2025-08-01
published: true
repourl: https://github.com/deepPublicGit/godis
labels:
  - go
  - redis
  - database
  - nosql
summary: "Implementation of the popular in-memory NoSQL database Redis in Golang."
---

This project is a step-by-step implementation of [`Redis`](https://redis.io/docs/latest/), an NoSQL in-memory database known for its speed and efficiency. The goal is to implement Redis in go (golang) from scratch, understand design decisions like serialization and memory optimizations made by the original developers.

## Key Updates in This Project

### Current Implementations
- Implemented Redis Serialization Protocol (RESP) for Integer, Simple & Bulk Strings, Arrays.
- Added Sync Server to accept Redis Commands.

### Testing & Deployment
- Included parameterized unit tests for Decoder.

### Miscellaneous Improvements
- Various minor enhancements for readability, maintainability, and performance

For a deeper dive into specific improvements, check out:
- [Commit history](https://github.com/deepPublicGit/godis/commits/master/) for a detailed breakdown of changes.
