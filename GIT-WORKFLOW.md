# Git Workflow Guide

Følg disse 7 trin hver gang – så undgår du rod i `main`.

1) Start ny branch
   git checkout -b docs/min-aendring

2) Lav ændringer og gem

3) Stage og commit
   git add .
   git commit -m "beskriv kort ændringen"

4) Push til GitHub
   git push origin docs/min-aendring

5) Opret PR (fra terminal)
   gh pr create --fill

6) Merge PR
   gh pr merge --squash --delete-branch

7) Tilbage til main og opdatér
   git checkout main
   git pull origin main

