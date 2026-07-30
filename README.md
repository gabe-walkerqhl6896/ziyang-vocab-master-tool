# Ziyang Vocab Master - Vocabulary Study Tool 2026

> **Ziyang Vocab Master is a browser-based vocabulary learning tool that converts PDF word lists into enriched flashcard decks saved locally, with optional AI-powered study assistance.**

[![Platform](https://img.shields.io/badge/Platform-Browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/gabe-walkerqhl6896/ziyang-vocab-master-tool?style=flat-square)](https://github.com/gabe-walkerqhl6896/ziyang-vocab-master-tool)

---

<p align="center">
  <a href="https://gabe-walkerqhl6896.github.io/ziyang-vocab-master-tool/">
    <img src="https://img.shields.io/badge/Download-Ziyang%20Vocab%20Master%20Latest-brightgreen?style=for-the-badge" alt="Download Ziyang Vocab Master">
  </a>
</p>

> **[Download Ziyang Vocab Master Latest](https://gabe-walkerqhl6896.github.io/ziyang-vocab-master-tool/)**

---

[Download Latest Build](https://gabe-walkerqhl6896.github.io/ziyang-vocab-master-tool/)

---

## What Is Ziyang Vocab Master?

Turn a vocabulary PDF into a more useful study resource directly in your browser. Ziyang Vocab Master reads candidate terms from PDF files, filters out common or less useful words, and produces a clean CSV that can serve as the starting point for a vocabulary deck.

The app can optionally expand each word with definitions, word origins, related terms, common collocations, example sentences, and visual prompts. Your decks stay in local browser storage, and four flashcard formats plus microphone-based pronunciation practice let you choose how to review.

---

## Key Capabilities

- Read potential vocabulary items from PDF documents
- Remove frequently seen words that are unlikely to be useful for study
- Save a selected, cleaned vocabulary list as CSV
- Enrich entries with AI-assisted definitions, etymology, synonyms, collocations, and examples
- Add image prompts obtained through Pexels
- Review material in four flashcard modes
- Rehearse pronunciation with the device microphone
- Keep the complete workflow in the browser with locally stored decks
- Work without an account, application server, or telemetry

---

## Getting Started

### Use the hosted version

Launch the current build in a modern web browser:

[Launch Ziyang Vocab Master](https://gabe-walkerqhl6896.github.io/ziyang-vocab-master-tool/)

### Use a local repository checkout

```bash
git clone https://github.com/gabe-walkerqhl6896/ziyang-vocab-master-tool.git
cd REPO
```

Open the application's HTML entry file in your browser. If local file access is restricted, serve the repository through any basic local web server instead.

---

## Typical Workflow

1. Start Ziyang Vocab Master in a browser.
2. Import the PDF containing the words you want to learn.
3. Inspect the extracted vocabulary and delete entries you do not need.
4. Export the refined list to CSV, or request AI-supported enrichment for the terms.
5. Add image cues when they help reinforce a word.
6. Save the completed deck in local browser storage.
7. Choose one of the four available flashcard modes.
8. Practice saying the vocabulary with microphone-based pronunciation review.

---

## Settings and Services

Ziyang Vocab Master is intended to run without a hosted account. Study decks are kept in browser-local storage.

When enabled, AI enrichment can use Gemini and image cues can use Pexels. Enter or configure the necessary service information through the application's available settings.

```text
Storage: Browser-local decks
AI enrichment: Gemini
Image cues: Pexels
Account: Not required
Telemetry: Not used
```

---

## System Requirements

- A current web browser with JavaScript enabled
- Local storage support in the browser
- Microphone permission for pronunciation exercises
- PDF documents containing the source vocabulary
- Internet connectivity for Gemini enrichment or Pexels image cues
- Enough browser storage to retain your local decks

---

## Frequently Asked Questions

### Is registration required?

No. The application can be used without creating an account.

### Where does the app keep my decks?

Decks are saved in the browser's local storage. Removing browser data or switching browser profiles can make locally stored decks unavailable.

### Can I study without connecting an AI service?

Yes. PDF importing, word filtering, CSV creation, and flashcard review do not require AI enrichment. Enrichment is an optional stage of the process.

### Which information can Gemini add?

Gemini enrichment can supply definitions, etymology, synonyms, collocations, and example sentences.

### What should I check if pronunciation practice fails?

Confirm that the browser has permission to use the microphone and that the intended input device is available. Browser compatibility and privacy controls may also prevent microphone access.

### What is the CSV export useful for?

The CSV provides a portable version of the filtered vocabulary. You can keep it as a backup or process the terms in another tool before building your study routine.

### How can I use the newest version?

Open the latest hosted build through the project link, or pull the newest repository changes and reopen the browser application.

### How do I report a problem?

Create an issue in the project repository. Include your browser, operating system, steps to reproduce the problem, and any useful console output.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
