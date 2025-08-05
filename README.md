#🧠 WordPress AI Chatbot (OpenRouter-Powered)

A modern, fully customizable AI chatbot widget for WordPress, built as a single HTML file. This chatbot supports LLMs via [OpenRouter.ai](https://openrouter.ai), and is designed to be easy to use, embed, and configure within any WordPress site using the Code Snippets plugin or theme editor.

# 📷 UI Previews

| Theme  | Preview |
|--------|---------|
| Green  | Green Chatbot UI <img width="1920" height="1080" alt="Chatbt-green" src="https://github.com/user-attachments/assets/c5cd6278-2aaa-41ee-a54f-ecf6065d7cbf" />
| Blue   | Blue Chatbot UI <img width="1920" height="1080" alt="Chatbot-blue" src="https://github.com/user-attachments/assets/077fb394-8696-4f22-bf26-5e1013be0bc0" />


---


✨ Features

- 🧠 Powered by any OpenRouter-compatible LLM
- 🪄 Built-in system prompt customization
- 🔄 Memory for conversation ( Ai can remember user replies)
- 📱  improved mobile responsive
- 🎨 Two color themes: **Blue** and **Green**
- 📄 Supports file/image uploads
- 💡 Zero JavaScript conflicts (WordPress-safe)
- 🧩 Easily embeddable with a single HTML snippet

---



## 🚀 How to Use in WordPress

1. Install the [Code Snippets](https://wordpress.org/plugins/code-snippets/) plugin** (or use your theme's custom HTML block).
2. Open the chatbot `.html` file** (either green or blue version) in VS Code or any editor.
3. Copy the entire code and **paste it into a new HTML snippet** in WordPress.
4. Save and activate the snippet.
5. costomize the system prompt to fit your wnat 

---

## 🔧 Configuration

In the HTML file, locate the `WP_CHATBOT_CONFIG` section inside the JavaScript code:

```js
const WP_CHATBOT_CONFIG = {
  OPENROUTER_API_KEY: "YOUR_OPENROUTER_KEY_HERE", // 🔑 Replace this
  MODEL_NAME: "google/gemma-3-27b-it:free",        // ✅ Use any supported OpenRouter model
  SYSTEM_PROMPT: `Customize your assistant's tone, knowledge, and personality here.`,
}
```

--------------------------------------------------------------

📜 License

- This project is open-source under the MIT License.

--------------------------------------------------------------

🤝 Contributions

- Feel free to open issues, suggest features, or submit pull requests. Let’s build smarter web experiences together!



  ...

