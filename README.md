# SnipGPT v2.1

SnipGPT is a lightweight Windows study assistant built for fast screenshot-based answers and quick prompt-based help.

It stays out of the way, listens for your hotkeys, lets you capture part of the screen, and sends the prompt to your selected AI provider. Version 2.1 adds a much faster custom prompt workflow, prompt-only mode, a copy button on the answer overlay, and more appearance customization.

## Features

- Fast screenshot-to-answer workflow
- Support for multiple AI providers
  - OpenAI
  - Gemini
- Selectable models from Settings
- Multiple screenshot modes
  - App mode
  - Windows snipping mode
  - Both
- Floating answer overlay
- Configurable overlay position
- Custom prompt popup
- Configurable prompt hotkey
- Prompt-only mode without taking a screenshot
- Copy button for quick copying answers
- Appearance customization for:
  - answer box
  - answer text
  - copy button
  - custom prompt popup
  - selection rectangle

## What’s New in v2.1

Version 2.1 focuses on speed, flexibility, and quality-of-life improvements.

### New in this version

- Added a **custom prompt popup**
- Added a **custom prompt hotkey**
- Added **prompt-only mode**
  - Press **Shift + Enter** in the prompt popup to send only the typed prompt
  - No screenshot is needed
- Added a **copy button** to the answer overlay
- Added more **appearance settings**
  - answer text transparency
  - copy button transparency
  - custom prompt popup transparency
  - custom prompt text/input transparency
- Improved the custom prompt flow
  - typed prompt can override the saved prompt
  - if no custom prompt is provided, the app falls back to the default built-in prompt
- Improved overlay and prompt popup behavior

## How It Works

SnipGPT runs quietly in the background and waits for your hotkeys.

You can use it in two main ways:

### 1. Screenshot workflow
Use a screenshot hotkey, select an area of the screen, and SnipGPT sends the image with your prompt to the selected AI provider.

### 2. Prompt-only workflow
Open the custom prompt popup, type your question, and press **Shift + Enter** to get an answer without capturing the screen.

## Hotkeys

### Default screenshot hotkey
- `Ctrl + Alt + S` for App mode

### Default custom prompt hotkey
- `Shift + C`

You can change the custom prompt hotkey in Settings.

## Prompt Popup Controls

Inside the custom prompt popup:

- `Enter` = use prompt + screenshot
- `Shift + Enter` = send prompt only
- `Esc` = cancel

## Settings

SnipGPT includes a Settings window where you can configure:

- AI provider
- model
- screenshot mode
- overlay position
- appearance settings
- custom prompt
- custom prompt hotkey

## Appearance Customization

The appearance window lets you adjust the look of the app overlay and popup UI.

### Overlay customization
- background mode
- background transparency
- answer text transparency
- copy button transparency

### Custom prompt popup customization
- popup background transparency
- popup text transparency
- prompt input transparency

### Selection box customization
- selection appearance
- selection fill transparency

## Supported Providers

### OpenAI
Examples:
- `gpt-4.1-mini`
- `gpt-4.1`
- `gpt-5.1`

### Gemini
Examples:
- `gemini-2.5-flash`
- `gemini-2.5-flash-lite`


### Using screenshot mode
1. Start listening
2. Press the screenshot hotkey
3. Select an area on screen
4. Wait for the answer overlay

### Using Windows snipping mode
1. Set screenshot mode to `Windows` or `Both`
2. Open the custom prompt popup or use the default prompt
3. Use `Shift + Win + S`
4. SnipGPT reads the clipboard image and sends it automatically

### Using prompt-only mode
1. Press the custom prompt hotkey
2. Type your prompt
3. Press `Shift + Enter`
4. Read the answer in the overlay
5. Press **Copy** to copy the result

## Why SnipGPT?

SnipGPT is designed for fast and quick problem solving.

It is useful for:
- multiple choice questions
- fast concept checks
- screenshots from lessons, PDFs, or browser pages
- short AI answers without opening a full chat window

## Notes

- The main window stays hidden while the app runs
- The overlay is designed to stay lightweight and unobtrusive
- In Windows screenshot mode, SnipGPT listens for clipboard image updates
- If a typed custom prompt is empty, the app uses the saved custom prompt or the default built-in prompt

## Installation

1. Download the latest **ZIP** from the GitHub repository
2. Extract the ZIP anywhere you want
3. Set the environment variable for the provider you want to use
4. Launch `SnipGPT.exe`

## Environment Variables

SnipGPT reads API keys from Windows environment variables.

### OpenAI
Set:

`OPENAI_API_KEY`

### Gemini
Set:

`GEMINI_API_KEY`

You only need to set the key for the provider you plan to use.

## How to Set Environment Variables on Windows

### OpenAI
Create a user or system environment variable named:

`OPENAI_API_KEY`

and set its value to your OpenAI API key.

### Gemini
Create a user or system environment variable named:

`GEMINI_API_KEY`

and set its value to your Gemini API key.

After setting the variable, restart the app.

## Roadmap

Possible future ideas:
- answer history
- richer overlay controls
- more providers
- better theme presets

## Version

**Current version: 2.1**
