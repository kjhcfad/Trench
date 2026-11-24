# Trench — The GCSE Dive

A GCSE revision game built around question banks, progress tracking and interactive quizzes.

## Features

- Interactive revision dives
- Multiple question types
- Automatic answer checking
- Question library
- Import your own question banks
- Revision statistics
- Shared community question banks

## Running locally

You can open `index.html` directly for the basic app.

For shared question banks, run a local server:

```bash
python -m http.server 8000
```

Then visit:

http://localhost:8000

## Question banks

Shared question banks are stored in `question-banks/`.

To add a bank:

1. Add a CSV file.
2. Register it in `question-banks/index.json`.
3. Commit your changes.

## Collaboration

Trench is a public project.

Contributions are welcome through GitHub pull requests.

Please check questions for accuracy before submitting them.

## Hosting

Trench can be hosted for free using GitHub Pages.

Go to:

Settings → Pages → Deploy from a branch

Select:

- Branch: main
- Folder: / (root)

## Privacy

Personal questions and statistics are stored locally in your browser.

Shared question banks are stored in this repository.
