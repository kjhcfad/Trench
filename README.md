# TRENCH — The GCSE Dive

**Dive deeper into your GCSE revision.**

Trench is a free, browser-based GCSE revision app built around interactive questions, question banks and progress tracking.

🌊 **[Open Trench](https://kjhcfad.github.io/Trench/)**

---

## Features

- **Revision Dives** — Answer questions and progress through your revision.
- **Automatic Answer Checking** — Get feedback on your answers.
- **Question Library** — Browse available question banks.
- **Custom Question Banks** — Import your own questions using CSV files.
- **Revision Statistics** — Track your accuracy, questions answered and deepest dive.
- **Community Question Banks** — Share question banks with other Trench users.

## Getting Started

1. Visit **[Trench](https://kjhcfad.github.io/Trench/)**.
2. Open the Question Library.
3. Select an available question bank.
4. Choose your questions and begin your dive.
5. Answer questions and track your progress through the Statistics page.

You can also import your own questions using the **Import CSV** section.

## Question Banks

Trench supports shared question banks stored in this repository.

Question banks are kept in:

`question-banks/`

### Adding a question bank

1. Create your question bank as a CSV file.
2. Add the CSV file to the `question-banks/` folder.
3. Register the bank in `question-banks/index.json`, following the existing format.
4. Check that the questions and answers are accurate.
5. Submit your changes through a pull request.

Custom banks imported directly through the website are saved locally in your browser. To share a bank with everyone, contribute it to this repository instead.

## Contributing

**Trench is a public project, and contributions are welcome!**

You can help by:

- Creating question banks for different GCSE subjects.
- Adding questions for different exam boards and specifications.
- Correcting inaccurate answers.
- Improving existing question banks.
- Reporting bugs or suggesting features.

### How to contribute

1. Fork this repository.
2. Make your changes.
3. Test your question bank.
4. Open a pull request explaining what you have added or changed.

Please make sure questions are accurate, clearly worded and appropriate for the stated specification.

## Running Locally

You can run Trench on your own computer.

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Start a local server:

```bash
python -m http.server 8000
```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.

Using a local server allows the app to access repository question-bank files.

## Privacy & Data

Trench does not require an account.

- Your revision statistics are stored locally in your browser.
- Custom question banks imported through the website are stored locally.
- Shared question banks are stored in this public GitHub repository.
- Your personal progress is not automatically shared with other users or synchronised between devices.

Clearing your browser's site data may remove locally stored questions and statistics.

## Hosting

Trench is hosted for free using GitHub Pages.

**Live website:** https://kjhcfad.github.io/Trench/

The site is deployed from the `main` branch of this repository.

---

## Licence

This project is released under the MIT Licence. See [LICENSE](LICENSE) for details.

**Happy revising. See you at the bottom of the Trench.** 🌊
