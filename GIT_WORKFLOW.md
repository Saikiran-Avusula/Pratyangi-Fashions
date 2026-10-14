# Git Workflow

## Main rule
Do not develop directly on main.

## Branches
- feature/hero
- feature/products
- feature/experience

## Start of work
git switch main
git pull origin main
git switch <your-branch>
git merge main

## Save work
git status
git add .
git commit -m "feat: <description>"
git push -u origin <your-branch>

## Integration
Open a Pull Request -> review -> approval -> merge into main.

## Important
Do not force-push shared branches.
Avoid editing the same shared files unnecessarily.
