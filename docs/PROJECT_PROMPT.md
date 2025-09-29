# CoWorkerAI — Project Prompt (Source of Truth)

## Purpose (What we’re building)
CoWorkerAI er en **programmør-AI** til macOS, der:
- Orkestrerer **flere AI-modeller** (senere) for at generere bedre kode end en enkelt AI.
- Bruger et **prompt-bibliotek** (genbrug, versioner) som kerne-UX.
- Opfører sig som en **sparringspartner**: udfordrer antagelser, forbedrer løsninger og leverer **hele filer** klar til indsætning.
- Kører **local-first** (JSON-persistens nu; kan opgraderes til SQLite/Core Data).

---

## Workflow commands (skal altid bruges slavisk)
Når jeg skriver **workflow** i chatten → du giver mig præcis rækkefølge af terminal-kommandoer til at pushe ændringer til GitHub:

1. Gem/overskriv den fil jeg arbejder på.  
2. Kør:
   ```bash
   git add .
   git commit -m "Update"
   git push origin main

