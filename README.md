# Chrome Extensions

Personal Chrome extensions — each lives in its own repo.

| Extension | Description | Repo |
|-----------|-------------|------|
| **h-newtab** | A calm new tab with essential shortcuts on an empty canvas | [chrome-h-newtab](https://github.com/hriosnl/chrome-h-newtab) |
| **Highlights** | Highlight text on webpages; saves highlights locally with notes | [chrome-highlights](https://github.com/hriosnl/chrome-highlights) |
| **Korean Reader** | Click Korean text in AI assistant replies to hear pronunciation | [chrome-korean-reader](https://github.com/hriosnl/chrome-korean-reader) |
| **Korean Saver** | Save Korean phrases + images for LLM → Anki workflows | [chrome-korean-saver](https://github.com/hriosnl/chrome-korean-saver) |
| **Quick Notes** | Fast scratch-pad notes with Markdown, auto-save, export/import | [chrome-quick-notes](https://github.com/hriosnl/chrome-quick-notes) |

## Install any extension

1. Clone the repo you want
2. Open `chrome://extensions` and enable **Developer mode**
3. Click **Load unpacked** and select the extension folder
4. For **Quick Notes**: run `npm install && npm run build` first, then load the `dist/` folder

## Local development

All extensions are developed locally under `~/Dev/Chrome Extensions/`. Each folder is an independent git repo with its own history.

## License

MIT (per extension repo)