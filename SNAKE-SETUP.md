# Optional contribution snake

The workflow is included at `.github/workflows/snake.yml`.

1. Create or use your profile repository: `Harsh-tech81/Harsh-tech81`.
2. Copy the `.github` folder from this package into that repository.
3. In GitHub, open **Settings → Actions → General → Workflow permissions** and allow read/write permissions if required by your repository policy.
4. Run **Actions → Generate contribution snake → Run workflow** once.
5. After the `output` branch is created, add this block to your README:

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Harsh-tech81/Harsh-tech81/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Harsh-tech81/Harsh-tech81/output/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution graph snake animation" src="https://raw.githubusercontent.com/Harsh-tech81/Harsh-tech81/output/github-contribution-grid-snake-dark.svg" width="100%">
</picture>
```

The snake image is intentionally not embedded in the initial README until the workflow has successfully generated it.
