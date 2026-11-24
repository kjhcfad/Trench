# Trench · the GCSE Dive

A revision web app where answering GCSE questions at speed, difficulty, and mark value drives your depth descent.

## Folder Structure for GitHub

- `index.html` — Complete app (dive engine, mark selector, prompt breakdown with `✕` on less than full marks, automatic `Needs practice` set tagging, stats, import/export, and `localStorage` persistence).
- `question-sets/` — Put your `.csv` question set files here.
- `question-sets/manifest.json` — Lists the `.csv` filenames inside `question-sets/` so static hosting (such as GitHub Pages) can load them automatically.

## Adding New Question Sets

1. Drop a new `.csv` file into `question-sets/` (for example, `question-sets/aqa-chemistry-bonding.csv`).
2. Add `"aqa-chemistry-bonding.csv"` to `question-sets/manifest.json`.
3. Commit and push to GitHub. Each CSV file's name automatically becomes a **Question set** filter on the Dive and Questions screens unless a `sets` column specifies custom set names.

### CSV Columns Supported
`subject,board,topic,subtopic,difficulty,type,marks,text,options,answer,model,explain,sets`
