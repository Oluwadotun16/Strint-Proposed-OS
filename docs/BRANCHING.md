# Branch Strategy

- main: stable, release-ready code. Only updated by merging develop.
- develop: integration branch. All feature work merges here first.
- feature/<name>: one branch per component or contributor, created from develop.

## Workflow
1. git checkout develop && git pull
2. git checkout -b feature/<name>
3. Commit work, then git push
4. Open a pull request into develop
5. When develop is stable, merge it into main
