# ✨ AI Summarizer Chrome Extension

A beautiful and powerful Chrome extension that uses Google's Gemini AI to generate intelligent summaries of web articles and news pages. Transform lengthy content into concise, digestible summaries with just one click!

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-brightgreen?style=for-the-badge&logo=google-chrome)
![Gemini AI](https://img.shields.io/badge/Powered%20by-Gemini%20AI-blue?style=for-the-badge&logo=google)
![Version](https://img.shields.io/badge/Version-1.0-orange?style=for-the-badge)

## 🚀 Features

- **🤖 AI-Powered Summaries**: Leverages Google's advanced Gemini AI model for accurate content summarization
- **🎯 Multiple Summary Types**: 
  - 📝 Brief Summary - Quick overview in a few sentences
  - 📖 Detailed Summary - Comprehensive analysis with key points
  - 🔸 Bullet Points - Easy-to-scan formatted list
- **🎨 Beautiful UI**: Modern glass morphism design with smooth animations
- **⚡ One-Click Operation**: Summarize any web page instantly
- **📋 Easy Copy**: Copy summaries to clipboard with one click
- **🔐 Secure**: API key stored locally in your browser
- **🌐 Universal**: Works on all websites and web pages

## 📸 Screenshots

### Popup Interface
![Popup Interface](https://via.placeholder.com/600x400/667eea/ffffff?text=Beautiful+Popup+Interface)

### Settings Page
![Settings Page](https://via.placeholder.com/600x400/764ba2/ffffff?text=Modern+Settings+Page)

## 🛠️ Installation

### Method 1: Chrome Web Store (Coming Soon)
1. Visit the Chrome Web Store
2. Search for "AI Summarizer"
3. Click "Add to Chrome"

### Method 2: Manual Installation (Developer Mode)
1. **Download the Extension**
   ```bash
   git clone https://github.com/prakharsingh-74/AI-summarizer-chrome-extension.git
   ```

2. **Open Chrome Extensions**
   - Navigate to `chrome://extensions/`
   - Enable "Developer mode" (toggle in top-right corner)

3. **Load the Extension**
   - Click "Load unpacked"
   - Select the downloaded extension folder
   - The extension will appear in your Chrome toolbar

## ⚙️ Setup

### 1. Get Your Gemini API Key
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Create a new API key
4. Copy the generated key

### 2. Configure the Extension
1. Click on the extension icon in your Chrome toolbar
2. Click on "Options" or right-click the extension icon → "Options"
3. Paste your Gemini API key in the settings
4. Click "Save Settings"

## 🎯 How to Use

1. **Navigate** to any article or news webpage
2. **Click** the AI Summarizer extension icon
3. **Choose** your preferred summary type:
   - Brief Summary
   - Detailed Summary  
   - Bullet Points
4. **Click** "Summarize This Page"
5. **Wait** for the AI to process the content
6. **Copy** the summary if needed

## 🔧 Technical Details

### Built With
- **Manifest V3** - Latest Chrome extension standard
- **Gemini AI API** - Google's advanced language model
- **Modern CSS** - Glass morphism design with gradients
- **Vanilla JavaScript** - Lightweight and fast

### File Structure
```
AI-summarizer-chrome-extension/
├── manifest.json          # Extension configuration
├── popup.html             # Main popup interface
├── popup.js               # Popup functionality
├── options.html           # Settings page
├── options.js             # Settings functionality
├── content.js             # Content script for page interaction
├── background.js          # Service worker
├── config.js              # Configuration file
├── icon.png               # Extension icon
└── README.md              # Documentation
```

### Permissions Used
- **`scripting`** - To inject content scripts
- **`activeTab`** - To access current tab content
- **`storage`** - To save API key and settings
- **`host_permissions`** - To work on all websites

## 🔒 Privacy & Security

- ✅ **Your API key is stored locally** in your browser storage
- ✅ **No data is sent to third parties** except Google's Gemini API
- ✅ **Page content is only processed** when you explicitly request a summary
- ✅ **No tracking or analytics** - your privacy is respected

## 🚧 Development

### Prerequisites
- Google Chrome browser
- Gemini API key from Google AI Studio
- Basic knowledge of Chrome extensions (for modifications)

### Local Development
1. Clone the repository
2. Make your changes
3. Load the extension in Developer Mode
4. Test your changes
5. Submit a pull request

## 📋 Roadmap

- [ ] 🌍 Support for multiple languages
- [ ] 📊 Summary analytics and insights
- [ ] 🎨 Customizable themes
- [ ] 💾 Save summaries history
- [ ] 🔗 Share summaries directly
- [ ] 📱 Mobile browser support

## ❓ FAQ

### Q: Is this extension free to use?
A: Yes! The extension is completely free. You only need a free Gemini API key from Google.

### Q: Does it work on all websites?
A: Yes, it works on any webpage with text content. However, it works best on articles and news pages.

### Q: Is my data safe?
A: Absolutely! Your API key is stored locally, and page content is only sent to Google's secure Gemini API for processing.

### Q: Can I use it offline?
A: No, an internet connection is required to communicate with the Gemini AI API.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Bug Reports

If you encounter any bugs or issues:
1. Check if the issue already exists in [Issues](https://github.com/prakharsingh-74/AI-summarizer-chrome-extension/issues)
2. If not, create a new issue with:
   - Detailed description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots (if applicable)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Prakhar Singh**
- GitHub: [@prakharsingh-74](https://github.com/prakharsingh-74)

## 🙏 Acknowledgments

- Google for providing the powerful Gemini AI API
- Chrome Extension community for inspiration and best practices
- All contributors and users who help improve this extension

## ⭐ Show Your Support

If you find this project helpful, please consider:
- ⭐ Starring this repository
- 🍴 Forking it to contribute
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 📢 Sharing it with others

---

<div align="center">

**Made with ❤️ by [Prakhar Singh](https://github.com/prakharsingh-74)**

[⬆ Back to Top](#-ai-summarizer-chrome-extension)

</div>
