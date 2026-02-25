# Project Conventions

## Language
- Main content in **English** (root / `src/`)
- Italian translation in `src/translations/it/`
- The user writes in Italian; translate to English for the main content and maintain the Italian version in parallel
- **Sync rule**: when one language version is modified, automatically update the other to keep them aligned

## Terminology
- Use **"growth"** instead of **"evolution"** in all content (both EN and IT: "crescita" instead of "evoluzione")

## Push Workflow
When the user says "push":
1. **Check changes** — review all modified files (git diff)
2. **Critical evaluation** — does each change make sense? If not, flag it and stop before committing
3. **Sync translations** — align EN/IT modules and READMEs
4. **Commit and push**
