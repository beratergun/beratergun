# Installation guide

## 1. Upload the package

Upload these items to the root of the public `beratergun/beratergun` repository:

```text
README.md
assets/
.github/workflows/snake.yml
```

Keep the folder names unchanged because the README uses relative image paths.

## 2. Commit to `main`

A suggested commit message:

```text
feat: redesign profile with AI and cybersecurity interface
```

## 3. Enable the contribution animation

1. Open the `beratergun/beratergun` repository.
2. Select **Actions**.
3. Open **Generate contribution snake**.
4. Select **Run workflow**.
5. Wait for the workflow to complete.

The workflow publishes the generated SVG files to an `output` branch. The README will then display the animation automatically.

If the workflow cannot push, open:

```text
Repository Settings → Actions → General → Workflow permissions
```

Select **Read and write permissions**, save, and run the workflow again.

## 4. Recommended pinned repositories

Pin these first:

1. `Cs50-Portfolio`
2. `artificial-intelligence`
3. A new public repository for `PassGuard`
4. A new public repository for the `MST Graph Optimizer`

A visually strong README attracts attention, but public repositories with clean documentation, tests, screenshots, and meaningful commit history create credibility.

## 5. Keep claims accurate

Update skill levels and certification dates only when they change. Avoid adding security tools or expertise not supported by public work. The design can look highly technical without overstating experience.
