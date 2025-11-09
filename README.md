📌 YouTube Bookmark Chrome Extension

A Chrome extension that allows users to save, manage, and revisit important timestamps inside YouTube videos. Perfect for students, researchers, and content consumers who want quick access to key moments!

🚀 Features

✅ Bookmark the current timestamp inside any YouTube video

✅ Bookmarks persist using Chrome Storage

✅ Play saved bookmarks directly

✅ Delete bookmarks easily

✅ Sorted bookmarks for better readability

✅ Seamless integration into the YouTube player UI

✅ Popup interface to manage all saved timestamps

🛠️ Tech Stack

JavaScript

Chrome Extension API (Manifest V3)

Chrome Storage API

Background Service Worker

Content Scripts

DOM Manipulation

HTML, CSS

📂 Project Structure
📁 Youtube-Bookmark-Chrome-Extension
│── 📁 assets
│     ├── bookmark.png
│     ├── play.png
│     ├── delete.png
│     ├── save.png
│     └── ext-icon.png
│── background.js
│── contentScript.js
│── popup.html
│── popup.js
│── popup.css
│── utils.js
│── manifest.json
│── README.md

🔧 Installation

Clone this repository:

git clone https://github.com/ryuk887/Youtube-Bookmark-Chrome-Extention.git


Open Chrome and go to:

chrome://extensions/


Enable Developer Mode (top right)

Click Load unpacked

Select the project folder ✅

🎯 How to Use

Open any YouTube video

Click the bookmark icon added to the video controls

Open the extension popup to:

▶ Play a saved timestamp

🗑 Delete a bookmark

📌 View all saved moments of the video

🧠 Working Mechanism

contentScript.js injects a bookmark button in the YouTube player

background.js detects video changes & passes the video ID

Bookmarks are stored using chrome.storage.sync

Popup communicates with content scripts using chrome.tabs.sendMessage

🤝 Contributing

Feel free to submit issues or contribute by creating pull requests!

📄 License

This project is open-source and available under the MIT License

👤 Author

Ryuk
GitHub: https://github.com/ryuk887
