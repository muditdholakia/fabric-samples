# Curated learning fork

Source: https://github.com/microsoft/fabric-samples
Purpose: curated fabric learning reference for muditdholakia. This is a fork, not original authorship.
Upstream license: MIT. Preserve LICENSE, file-level notices, attribution, and any asset-specific terms.
Setup: follow the upstream README and the prerequisites of the selected sample. Use synthetic data and a development tenant.
Upstream snapshot: 618b765245eee371003d0aa011a3d921f45b6d24

## Synchronization

```sh
git fetch --unshallow upstream  # once, if this clone is shallow
git fetch upstream
git switch main
git merge upstream/main
git push origin main
```

Review conflicts and dependency/runtime changes before executing upstream code.
Curator documentation is additive; upstream copyright and README are retained.
Security: see CURATOR_SECURITY.md. Fork Actions remain disabled until manually reviewed.
Troubleshooting: shallow merge errors require fetching full history; authentication errors require `gh auth status`.
