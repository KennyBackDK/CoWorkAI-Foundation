# Preflight checks for nye projekter

1) Gå ind i projektmappen:
   cd "/Users/kenny/Xcode Projects/MitProjekt"

2) Sæt hooks og gør scripts kørbare (kun første gang):
   git config core.hooksPath .githooks
   chmod +x .githooks/pre-commit scripts/*.sh

3) Kør preflight:
   scripts/preflight.sh
   # Forvent: "OK: Preflight passed."

4) (Valgfrit) Ryd DerivedData hvis Xcode driller:
   rm -rf ~/Library/Developer/Xcode/DerivedData/MitProjekt-*

5) Åbn i Xcode og byg:
   # Clean Build Folder
   # Build
   # Run
   Shift+Cmd+K, Cmd+B, Cmd+R

# ✅ Preflight checks for nye projekter

1. Gå ind i projektmappen:
   ```bash
   cd "/Users/kenny/Xcode Projects/MitProjekt"

scripts/preflight.sh

