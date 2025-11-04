# Contributing to Microsoft AI Decision Tree

This is a fork of [ChrisMcKee1/microsoft-ai-decision-tree](https://github.com/ChrisMcKee1/microsoft-ai-decision-tree). This document explains how to keep this fork up-to-date with the original repository.

## Syncing Your Fork with Upstream

To refresh this fork with the latest code from the original repository, follow these steps:

### 1. Add the Upstream Remote (One-time setup)

If you haven't already added the upstream remote, run:

```bash
git remote add upstream https://github.com/ChrisMcKee1/microsoft-ai-decision-tree.git
```

Verify your remotes:

```bash
git remote -v
```

You should see:
- `origin` pointing to `jameswh3/microsoft-ai-decision-tree` (your fork)
- `upstream` pointing to `ChrisMcKee1/microsoft-ai-decision-tree` (original repo)

### 2. Fetch the Latest Changes from Upstream

```bash
git fetch upstream
```

This downloads all new branches and commits from the upstream repository.

### 3. Merge Upstream Changes

Switch to your main branch (or the branch you want to update):

```bash
git checkout main
# or
git checkout copilot/update-fork-with-latest-code
```

Merge the upstream changes:

```bash
git merge upstream/main
```

If there are any conflicts, Git will notify you. Resolve them manually, then:

```bash
git add .
git commit -m "Resolve merge conflicts"
```

### 4. Push Changes to Your Fork

```bash
git push origin main
# or
git push origin copilot/update-fork-with-latest-code
```

## Alternative: Using GitHub's Web Interface

GitHub provides a built-in feature to sync forks:

1. Go to your fork on GitHub: `https://github.com/jameswh3/microsoft-ai-decision-tree`
2. Click the **"Sync fork"** button near the top of the page
3. Click **"Update branch"** to merge the upstream changes

This method works well when there are no conflicts and you want a quick sync.

## Keeping Up-to-Date

To stay current with the upstream repository:

- **Check regularly**: Review the upstream repository periodically for updates
- **Watch the upstream repo**: Click "Watch" on the [original repository](https://github.com/ChrisMcKee1/microsoft-ai-decision-tree) to get notifications
- **Sync before making changes**: Always sync with upstream before starting new work to minimize conflicts

## Contributing Back to Upstream

If you make improvements that would benefit the original repository:

1. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-improvement
   ```

2. Make your changes and commit them

3. Push to your fork:
   ```bash
   git push origin feature/your-improvement
   ```

4. Open a Pull Request from your fork to the upstream repository

## Questions?

For questions about the content, refer to the [original repository](https://github.com/ChrisMcKee1/microsoft-ai-decision-tree) or open an issue there.
