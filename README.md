# An advanced chrome extension to make your youtube video experience on next level. 

## Home
![](/assets/home.png)

## Summary
![](/assets/summary.png)

## Transcript
![](/assets/transcript.png)

## Chat
![](/assets/chat.png)

## 🚀 Overview

Transform how you interact with YouTube videos using AI-powered summarization, transcript search, and intelligent video chat.

### ✨ Features

- 🎨 Modern, minimalist design
- 📱 Fully responsive layout
- 🚀 Built with Plasmo & React for lightning-fast performance
- 🎨 Tailwind CSS for styling
- 📦 Component-based architecture

## 🛠️ Tech Stack

- **Framework:** React & Plasmo
- **Language:** Typescript
- **Styling:** Tailwind CSS
- **Code Quality:** ESLint

## 🚀 Getting Started

### Installation

1. Clone the repository
```bash
git clone "git@github.com:'yourusername'/YoutubeLens-ChromeExtension.git"
```

2. Navigate to the project directory
```bash
cd YoutubeLens-ChromeExtension
```
2. Install dependencies
```bash
pnpm i -> pnpm dev

# or
npm run dev
```

Open your browser and load the appropriate development build. For example, if you are developing for the chrome browser, using manifest v3, use: `build/chrome-mv3-dev`.

You can start editing the popup by modifying `popup.tsx`. It should auto-update as you make changes. To add an options page, simply add a `options.tsx` file to the root of the project, with a react component default exported. Likewise to add a content page, add a `content.ts` file to the root of the project, importing some module and do some logic, then reload the extension on your browser.

For further guidance, [visit our Documentation](https://docs.plasmo.com/)

## Making production build

Run the following:

```bash
pnpm build
# or
npm run build
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.

## Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

Nihal Ahmad - nehalhmd14@gmail.com

Project Link: 

---

<div align="center">
  Made with ❤️ by [Nihal Ahmad]
</div>
