# Trench Question Banks

This folder contains the shared GCSE question banks.

## Adding a question bank

1. Create a CSV file in this folder.
2. Include a header row.
3. Add your questions.
4. Add the bank to `index.json`.
5. Submit a pull request or commit your changes.

## Supported question types

| Type | Description |
|---|---|
| mc | Multiple choice |
| short | Short answer |
| tf | True or false |
| fill | Fill in the blank |
| extended | Extended written answer |

## CSV columns

- question (required)
- type
- options
- answer
- model_answer
- explanation
- subject
- exam_board
- specification
- topic
- subtopic
- difficulty
- marks

For multiple-choice questions, separate options with ` | `.
