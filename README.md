# inSpeak

Voice dictation for Windows. Hold a shortcut, speak, then release it to insert the text into your active application.

[Download the latest installer](https://github.com/Presoon/inSpeak-releases/releases/latest) · [All releases](https://github.com/Presoon/inSpeak-releases/releases) · [Website](https://inspeak.pro)

## Getting started

1. Download `InSpeak-Setup-<version>.exe` from Releases and run it.
2. Open inSpeak. Choose your language and microphone, download the speech model (about 670 MB), and check your shortcut.
3. Click a text field in the application you want to use. Hold **Ctrl + Win**, speak, then release the keys to insert your dictation.

Requires **Windows 10/11 x64**, a microphone, and internet access for the initial model download. You can choose a different keyboard or mouse shortcut in settings.

## What it does

- Recognizes speech locally in 25 European languages, including Polish and English, with automatic language detection and punctuation.
- Shows a floating widget with recording levels and processing status.
- Keeps a searchable local history so you can copy or correct earlier dictations.
- Lets you save names, acronyms, pronunciation variants and correction rules in your own dictionary.
- Supports configurable push-to-talk and toggle recording shortcuts.

Speech recognition works offline after the model download. Recordings, history and dictionary stay on your PC.

## Optional AI editing

AI editing is **off by default**. To use it, enable it in settings and add your own OpenAI API key. Enabling AI means consenting to send text to OpenAI; microphone recordings are not sent.

The widget offers three actions for the full text in your active editable field:

- **Correct** fixes punctuation, capitalization and obvious recognition errors while preserving the meaning.
- **Translate** translates into the language selected in settings.
- **Prompt** turns your text into a clearer prompt for AI.

These actions replace the field's text with the result and do not press Enter. They require internet access and use **separate OpenAI API billing**, which is not included in a ChatGPT subscription. Some applications do not expose a compatible editable field.

Optional spoken commands can also correct a completed dictation, turn it into a prompt, or insert it and press Enter. Enable these separately in **Settings → Commands and AI**.

## Updating

Download and run a newer installer from Releases. Updates retain your settings, history, dictionary and downloaded speech model.

This repository contains the project description and compiled application releases.
