# VelaAI ⌚🤖

An AI-powered assistant designed specifically for smartwatches running Xiaomi Vela, featuring a custom on-device virtual keyboard, QR code configuration pairing, and seamless OpenRouter integration.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://choosealicense.com/licenses/mit/)
![Platform: Xiaomi Vela](https://img.shields.io/badge/Platform-Xiaomi%20Vela-blue)
![Device: Redmi Watch 5](https://img.shields.io/badge/Device-Redmi%20Watch%205-red)

---

## ⚠️ Compatibility Warning
* **Supported Devices:** Redmi Watch 5 (Regular).
* *Note: Support for more Xiaomi Vela-powered smartwatches and wearable form factors is coming soon.*

---

## ✨ Features

* **QR Code Token Provisioning:** Generate a secure QR code via a companion web tool to instantly sync your long API key to the watch without typing it manually.
* **Modern Virtual Keyboard:** Fully tailored on-screen alphanumeric input layout built explicitly for matrix navigation on small watch faces.
* **OpenRouter Integration:** Connects directly to `openrouter.ai` to stream responses using lightning-fast, budget-friendly endpoints.
* **Clean UI & Dark Theme:** Minimalist UI footprint carefully optimized to conserve wearable screen real estate and maximize readability.
* **Real-time Connection Status:** Instant networking telemetry feedback (Connected, Offline, Invalid Key) directly via status bar pills.
* **Quick Configuration Reset:** Instantly wipe local storage keys with an explicit one-tap physical reset action (`✕`) to switch keys or profiles.

---

## 🚀 Installation

Getting VelaAI running on your watch is quick and doesn't require compiling code from scratch:

1. On your computer or smartphone, head to the [VelaAI GitHub Releases](https://github.com/Kwadwo-O/VelaAI/releases) section.
2. Download the latest pre-compiled application package (`.rpk` / build bundle) from the assets.
3. Use the **AIoT-IDE** or your device's sideloading companion tool setup to install the package directly onto your **Redmi Watch 5**.

---

## 🔑 Setup & QR Code Pair Guide

Instead of manually typing a long OpenRouter token using the watch screen, you can use our companion web portal to input your key and pair it instantly via a QR code.

### 1. Get an OpenRouter API Key
1. Go to [OpenRouter](https://openrouter.ai/) and create a free account.
2. Navigate to your dashboard settings, generate a new **API Key**, and copy it to your clipboard.

### 2. Generate Your Setup QR Code
1. Open the [VelaAI Companion Web Tool](https://asermohamed2009.pythonanywhere.com/login-ai) in a web browser.
2. Paste your copied OpenRouter API key into the secure input text field.
3. Input Your **Code given on the watch**. Then press Enctypt and Send to watch.
4. There you have it setup.

### 3. Sync to Your Watch
1. Launch the **VelaAI** app on your Redmi Watch 5.
2. From the initial login/welcome screen, tap the **Scan QR Code** button option.
3. Hold your watch camera up to your browser screen to read the QR code image.
4. Once scanned, your watch will automatically parse the secret string, initialize the authentication handshake, and switch your dashboard to a **Connected** status. You are ready to chat!

---

## 🔮 Future Roadmap

* [ ] **Model Selection Matrix:** Let users toggle between premium LLMs (such as OpenAI's GPT-4o or Anthropic's Claude 3.5 Sonnet) natively inside the app config views.

---

## 📄 License

Distributed under the **MIT License**. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for more information details.
