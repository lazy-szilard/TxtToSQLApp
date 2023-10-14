# RecallSQL: Natural Language to SQL Converter

RecallSQL is a Python application that seamlessly translates natural language queries into SQL code using OpenAI's text-davinci-003 engine. It simplifies SQL query writing, making it accessible to users with varying levels of expertise.

## Features

- **Easy Conversion**: Effortlessly convert plain English queries into structured SQL code.
- **OpenAI Integration**: Utilizes OpenAI's text generation capabilities for accurate SQL generation.
- **User-Friendly Interface**: Intuitive GUI built with tkinter for a smooth user experience.
- **Clipboard Integration**: Copy generated SQL code to the clipboard with a single click.

## Usage

1. **Input Query**: Enter your natural language query in the input box.
2. **Conversion**: Click "Convert" to generate the corresponding SQL code.
3. **Output Display**: View the generated SQL code in the output box.
4. **Copy to Clipboard**: Click "Copy" to copy the SQL code to your clipboard.

## Getting Started

### Prerequisites

- Python 3.x
- `openai` Python library (Install using `pip install openai`)
- `tkinter` Python library (Usually included in Python standard library)

### Installation and Usage

```bash
git clone https://github.com/lazy-szilard/TxtToSQLApp.git
cd RecallSQL
python main.py
```

Replace `"enter your api-key here"` in `main.py` with your OpenAI API key.

## Contributing

1. **Fork** the repository.
2. Create a new branch for your feature or bug fix.
3. Make changes and submit a **pull request**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Disclaimer:** RecallSQL is a community project and is not affiliated with or endorsed by OpenAI. Please review and comply with OpenAI's usage policies before extensive use.
