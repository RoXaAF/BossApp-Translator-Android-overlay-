# Boss Translator

A fast, clean translation tool that turns text between languages in seconds. Built to be simple to use, quick to run, and easy to extend.

![Boss Translator main screen](screenshots/main.png)

## Features

- Translate text between multiple languages
- Automatic source-language detection
- One-click copy of the translated output
- Clean, responsive interface for desktop and mobile
- Lightweight, with no heavy dependencies

## Screenshots

| Main screen | Translation result |
|---|---|
| ![Main screen](screenshots/main.png) | ![Result](screenshots/result.png) |

> Add your own images to the `screenshots/` folder and keep the same file names, or update the paths above.

## Getting Started

### Prerequisites

- Node.js 18+ and npm (or the runtime your project uses)

### Installation

```bash
git clone https://github.com/<your-username>/Boss-translator.git
cd Boss-translator
npm install
```

### Running Locally

```bash
npm start
```

Then open `http://localhost:3000` in your browser.

## Usage

1. Type or paste the text you want to translate.
2. Choose the source and target languages (or leave source as *auto-detect*).
3. Click **Translate**.
4. Copy the result with one click.

## Project Structure

```
Boss-translator/
├── src/            # Application source code
├── screenshots/    # Images used in this README
├── LICENSE
└── README.md
```

## Roadmap

- [ ] Translation history
- [ ] Offline mode
- [ ] Additional language packs
- [ ] Keyboard shortcuts

## Contributing

Contributions are welcome. Please fork the repository, create a feature branch, and open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
