# Screen AI Helper – VS Code Extension

Screen AI Helper is a powerful Visual Studio Code extension that helps developers **instantly understand coding errors** without switching between apps or pasting code into ChatGPT.

It highlights the exact error, analyses diagnostics, and (optionally) uses AI to explain the problem in simple language — improving the debugging experience and reducing context switching.

---

## 🚀 Features

### 🔍 1. Automatic Error Detection
- Detects VS Code diagnostics (errors & warnings)
- Finds the exact line and column where the error occurs
- Highlights the problematic code snippet automatically

### 🤖 2. AI-Powered Error Explanation (Optional)
If an OpenAI API key is configured, the extension:
- Generates human-friendly explanations
- Explains why the error occurred  
- Suggests how to fix it  
- Provides corrected code examples  
- Helps beginners debug faster  

(*AI features work after adding API credits — completely optional*)

### 🖥️ 3. Non-AI Mode (Free to use)
Even without an API key:
- Error highlighting works  
- Error extraction works  
- You still get a clean diagnostics viewer  

### 🪟 4. Interactive Side Panel
The extension displays results in a custom Webview panel:
- Shows error snippet
- Shows file name, language, and error message
- Shows AI explanation (if enabled)
- Clean UI for debugging

---

🔮 Future Work / Upcoming Enhancements

Screen AI Helper is actively evolving. Here are the next planned improvements and upcoming features:

✅ 1. Multi-Error Analysis (Batch Mode)

Instead of explaining only the currently selected error, the extension will:

Scan the entire file

Detect all diagnostics

Provide explanations for each

Offer a summarized view of all issues

Useful for large files with multiple errors.

🌐 2. Support for Multiple AI Providers

Right now the extension supports OpenAI.
Future versions will include:

Gemini API

Llama models

Local models (Ollama)

Azure OpenAI
This allows full flexibility based on cost, speed, and API preferences.

🛠️ 3. Auto-Fix Code Suggestions

The extension will soon be able to:

Suggest automatic code fixes

Apply small corrections directly to the file

Provide multiple fix options (like ESLint quick fixes)

📄 4. Inline Explanations

Instead of only using the side-panel Webview:

Hover over an error to instantly see AI explanation

Inline error messages with actionable fixes

Great for extremely fast debugging.

📡 5. Offline Error Explanations (No API Required)

Local model integration (via Ollama) will allow:

Error explanations without internet

Free usage without API key

Making the extension useful for everyone.

💡 6. Smart Code Snippet Extraction

More advanced snippet detection:

Capture surrounding lines for better AI context

Avoid incorrect snippet selection

Improve explanation accuracy

🧪 7. Test Case Generator (Optional AI Feature)

Based on the buggy code, the extension will:

Suggest unit tests

Highlight failing edge cases

Help developers improve coverage

👨‍💻 8. UI Enhancements

Plans include:

Light/Dark mode switching

More compact Webview layout

Syntax highlighting inside Webview

Smooth animations

📦 9. Publish to VS Code Marketplace

Once core features are stable:

Full packaging

Versioning

Public release to VS Code Extension Marketplace

Auto-update support

## 📦 Installation (Developer Mode)

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/screen-ai-helper.git
cd screen-ai-helper
