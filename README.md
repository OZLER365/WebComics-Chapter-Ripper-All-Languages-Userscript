# WebComics Ripper

An automated Tampermonkey userscript designed to intercept and download high-quality chapter images from WebComicsApp directly into neatly organized local folders[cite: 12]. 

## ✨ Core Features

* **Network API Interception:** Hooks into the site's native XHR and Fetch requests to silently capture original image URLs directly from the JSON data, ensuring lossless extraction[cite: 12].
* **Smart Chapter Matching:** Cross-checks the URL's chapter ID with the intercepted data to guarantee you are downloading the current chapter, preventing accidental downloads of pre-loaded next chapters[cite: 12].
* **Sleek Floating UI:** Features a modern, non-intrusive floating panel in the bottom-right corner with live status indicators (Waiting, Ready, Downloading), progress bars, and toast notifications[cite: 12].
* **Native Folder Organization:** Utilizes `GM_download` to save images directly to your device (e.g., `Downloads/<Chapter_Title>/001.jpg`), completely bypassing the need for ZIP extraction[cite: 12].
* **SPA Navigation Support:** Automatically detects when you move to a new chapter without refreshing the page, resetting the tool to capture the next batch of images automatically[cite: 12].

## 🌐 Supported Languages

This script fully supports the WebComicsApp platform across the following languages: **English, Français, Português, Español, and Indonesia**[cite: 11].

## 🚀 Installation & Usage

1. **Prerequisite:** Install the **Tampermonkey** extension (highly recommended for `GM_download` compatibility)[cite: 11, 12].
2. **Install Script:** Add the userscript to your manager[cite: 12].
3. **Usage:** Open any chapter on WebComicsApp[cite: 12]. The floating panel will initially say "Waiting for pages…" and then switch to "Ready" once the images are successfully intercepted[cite: 12].
4. **Download:** Click the download button in the floating panel to automatically queue and save all pages into a named folder[cite: 12]. (If interception misses, the script includes a fallback button to directly fetch the API data[cite: 12]).

## ⚠️ Disclaimer

**This script is strictly for educational purposes.** Please support the original creators and platforms. Do not repost or redistribute the downloaded images[cite: 11].

## 🔗 Links, Feedback & Support

* **Greasyfork Scripts:** [ozler365's Profile](https://greasyfork.org/en/users/1553223-ozler365)[cite: 11]
* **GitHub Repositories:** [ozler-s-works-info](https://ozler365.github.io/ozler-s-works-info/#/repositories)[cite: 11]
* **Support the Developer:** Keep this script updated by leaving a small donation at [Buy Me a Coffee (ozler)](https://buymeacoffee.com/ozler)[cite: 11]

For queries, bug reports, or feature requests, please leave a review on Greasyfork or email **devjk6918@gmail.com**[cite: 11].
