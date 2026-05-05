# Leenium VS Code Theme

Marketplace extension for Leenium editor theme.

## Local test

1. Install tooling:

```bash
npm install -g @vscode/vsce
```

2. Package extension:

```bash
vsce package
```

3. Install generated `.vsix` in VS Code (`Extensions: Install from VSIX...`).

## Publish

1. Create Azure DevOps publisher and PAT.
2. Login:

```bash
vsce login leenium
```

3. Publish:

```bash
vsce publish
```

Extension id used by Leenium theme sync is `leenium.leenium-theme`.
