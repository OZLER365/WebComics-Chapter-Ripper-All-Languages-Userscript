# WebComics Downloader

A custom userscript built to fetch high-resolution comic pages from the WebComicsApp platform and save them directly into organized folders on your computer.

## ✨ Main Capabilities

* **Background Request Capture:** Monitors network traffic (Fetch/XHR) to silently grab the original image source URLs from the site's data stream, guaranteeing top quality.
* **Accurate Episode Detection:** Verifies the current URL against the backend data to ensure you only download the chapter you are currently reading, preventing mix-ups with preloaded content.
* **Modern Interface:** Displays a clean, floating control panel on your screen that shows real-time progress, status updates, and interactive buttons.
* **Direct Directory Save:** Uses the browser's native download API to save files straight to your hard drive (e.g., `Downloads/Comic_Name/001.jpg`) without needing ZIP extraction.
* **Dynamic Page Load Handling:** Seamlessly resets and prepares for the next batch of images when you navigate to a new episode without refreshing the web page.

## 🌐 Supported Regional Versions

This tool works perfectly across multiple language versions of the site, including English, French, Portuguese, Spanish, and Indonesian.

## 🚀 How to Install and Use

1. **Requirements:** Make sure you have a userscript manager installed (Tampermonkey is strongly advised for proper file saving).
2. **Setup:** Add the code to your extension dashboard.
3. **Running the Tool:** Navigate to a comic episode. The floating menu will display a waiting status, then change to ready once the page data is captured.
4. **Saving Files:** Press the download button to queue the images and save them locally. (A fallback option is included if the automatic capture misses).

## ⚠️ Important Notice

**This project is provided for educational learning only.** Please respect comic creators and platforms. Do not upload or share the saved media elsewhere.

## 🔗 Resources and Contact

* **Script Profile:** [ozler365 on Greasyfork](https://greasyfork.org/en/users/1553223-ozler365)
* **GitHub Portfolio:** [ozler-s-works-info](https://ozler365.github.io/ozler-s-works-info/#/repositories)
* **Support the Project:** If you find this helpful, consider leaving a tip at [Buy Me a Coffee (ozler)](https://buymeacoffee.com/ozler)

For feedback or bug reports, please drop a review on Greasyfork or email **devjk6918@gmail.com**.
