# SnipGPT 

> Lightweight Windows overlay that lets you select part of your screen and send it to GPT for an instant answer.

---

##  Features

-  Minimal Windows overlay — stays out of your way
-  Select any region of your screen with a hotkey
-  Instant GPT-powered answers
-  Uses your own OpenAI API key

---

##  Setup

> **SnipGPT requires your own OpenAI API key.**

### Step 1 — Create an API Key

1. Go to [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)
2. Click **Create new secret key**
3. Copy the key — you won't be able to see it again

---

### Step 2 — Set Environment Variable

1. Press **Win + R**, type `sysdm.cpl`, and hit Enter
2. Go to **Advanced** → **Environment Variables**
3. Under **User variables**, click **New**
4. Set the following:

   | Field | Value |
   |-------|-------|
   | **Name** | `OPENAI_API_KEY` |
   | **Value** | `sk-your-key-here` |

5. Click **OK** and **restart the app**

---

##  Usage

1. Launch **SnipGPT.exe**
2. Press the hotkey to activate the overlay
3. Click and drag to select an area of your screen
4. View the GPT answer instantly in the overlay

---

##  Requirements

- Windows 10 / 11
- An [OpenAI API key](https://platform.openai.com/api-keys)

---

##  Disclaimer

This app uses the OpenAI API. Usage is billed to your OpenAI account based on the number of requests made.
