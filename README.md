# SnipGPT

SnipGPT is a lightweight Windows desktop tool that lets you select any area of your screen and instantly send it to an OpenAI model for analysis. The response appears in a small overlay window directly on your screen — no switching windows, no copy-pasting.

---

## Features

- **Custom screen region selection** via `Ctrl + Alt + S`
- **Overlay response window** — stays on top of your screen
- **Real-time model switching** — no restart required
- **Customizable overlay position**
- **High-DPI accurate screenshot capture** — works on 100%, 125%, 150%+ scaling
- **Supported models:**
  - `gpt-4.1`
  - `gpt-4.1-mini`
  - `gpt-5.1` *(if available to your API key)*

---

## Requirements

- Windows
- [.NET Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet)
- OpenAI API key

---

## Setup

**1. Download and extract the application files.**

**2. Add your OpenAI API key as a system environment variable:**

- Open **System Properties**
- Go to **Advanced → Environment Variables**
- Under **System variables**, click **New**
- Set the variable name to:

```
OPENAI_API_KEY
```

- Set the value to your API key

**3. Restart the application** so the variable is applied.

**4. Run the application executable.**

---

## Usage

1. Launch the application
2. Open **Settings** to choose your model and overlay position
3. Click **"Start Listening"**
4. Press `Ctrl + Alt + S`
5. Draw a selection around any region of your screen
6. The AI response will appear in the overlay window

> Changes made in Settings apply instantly — no restart needed.

---

## Version History

| Version | Changes |
|---------|---------|
| `v1.1` | Fixed DPI scaling issue causing screenshot edge cropping; improved capture accuracy on high-DPI displays |
| `v1.0` | First stable release — model selection, overlay customization, hotkey support |

---

## Notes

Model availability depends on your OpenAI API key permissions. If a model does not appear in the settings menu, it is not accessible to your account.
