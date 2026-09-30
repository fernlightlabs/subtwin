# Subtwin Privacy Policy

Last updated: 2026-09-30

Subtwin is a browser extension that shows original and translated subtitles on YouTube.

**Subtwin does not collect, store on any server, sell or share any personal data.** It has no account, no analytics and no tracking.

What happens on your device:

- **Captions**: Subtwin reads the caption tracks that the YouTube player already loads, from youtube.com, inside your own browser session.
- **Translation**: translations come from YouTube's own caption translation, from human-made caption tracks of the video, or from Chrome's built-in on-device AI translator. On-device translation runs locally; the text is not sent anywhere by Subtwin.
- **Settings**: your preferences (translation language, size, style, on/off) are saved with Chrome's extension storage (`chrome.storage`), which Chrome may sync across your own signed-in browsers. A small local counter of how many videos you watched with Subtwin is kept on your device only, to show a one-time rating request.
- **Cache**: parsed subtitles are cached in the tab's session storage and are deleted when the tab closes.

Permissions: `storage` (save your settings) and access to `https://www.youtube.com/*` (show subtitles on YouTube). Subtwin runs on no other website.

Contact: open an issue at https://github.com/fernlightlabs/subtwin/issues
