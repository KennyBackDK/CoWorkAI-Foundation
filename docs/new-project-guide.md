# 🚀 Ny app fra CoWorkAI-Foundation (huskeliste)

## 1) Opret repo fra template
- Gå til GitHub → **Use this template** på `CoWorkAI-Foundation`
- Navngiv fx `MinApp`

## 2) Klon lokalt
```bash
cd "/Users/kenny/Xcode Projects"
git clone https://github.com/KennyBackDK/MinApp.git
cd MinApp

git config core.hooksPath .githooks
chmod +x .githooks/pre-commit scripts/*.sh
scripts/preflight.sh

git add .
git commit -m "Init fra Foundation"
git push origin main

