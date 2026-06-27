# Setup for enterthevoid8 Profile README

## 1. Create the special profile repository

Create a public GitHub repository named exactly:

```text
enterthevoid8
```

GitHub shows the root README.md of a public repo with the same name as your username on your profile.

## 2. Upload files

Upload these files:

```text
README.md
.github/workflows/snake.yml
```

## 3. Enable GitHub Actions write permission

In the repository:

Settings → Actions → General → Workflow permissions → Read and write permissions → Save

## 4. Run snake workflow

Go to Actions → Generate Contribution Snake → Run workflow.

After it succeeds, the snake animation will appear in the README.

## 5. Optional quick clone/push

```bash
git clone https://github.com/enterthevoid8/enterthevoid8.git
cd enterthevoid8
cp /path/to/README.md README.md
mkdir -p .github/workflows
cp /path/to/snake.yml .github/workflows/snake.yml
git add README.md .github/workflows/snake.yml
git commit -m "Create professional GitHub profile README"
git push origin main
```
