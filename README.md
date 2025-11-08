# Mattmat’s Sari-Sari Store Inventory System

**Version:** `v3.2.1 (Drive Enabled)`  
**Release Date:** November 2025  
**Author:** James  
**License:** Personal / Open Source (choose your preference)

---

## Overview

Mattmat’s Inventory is a self-contained, offline-capable inventory and purchase list management system built entirely in **HTML** and **JavaScript**.

It’s designed for sari-sari store owners and small shopkeepers who need a simple, fast, and install-free inventory system that works both offline and online.  
Data is saved in your browser using **localStorage**, and optional **Google Drive integration** lets you back up or restore your data anytime.

---

## Google Drive Setup

To enable Drive Import/Export features:

1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Enable **Google Drive API**.
3. Create credentials:
   - **API Key** (restricted to your domain or `localhost`)
   - **OAuth 2.0 Client ID (Web Application)**
4. Open your `mattmat_inventory_v3_2_1_drive.html` file and replace the placeholders:
   ```js
   const GOOGLE_API_KEY = 'YOUR_API_KEY';
   const GOOGLE_CLIENT_ID = 'YOUR_CLIENT_ID.apps.googleusercontent.com';
   ```
5. Save and open the file from your authorized origin (for example, `http://localhost` or your GitHub Pages site).
6. Sign in when prompted to allow Google Drive file access.

---

## Installation and Usage (Non-Technical Guide)

### Option 1: Run Locally (Offline)

1. Download the file:
   ```
   mattmat_inventory_v3_2_1_drive.html
   ```
2. Double-click to open it in your web browser (Chrome recommended).
3. You can now:
   - Add, edit, and delete items
   - Manage categories
   - Create and print purchase lists
4. Your data is saved automatically. No installation or internet required.

---

### Option 2: Use with Google Drive

1. Host or open the file from your GitHub Pages or localhost.
2. Click **Export to Drive** to back up your data as a CSV file.
3. Click **Import from Drive** to restore your previous data anytime.

**Tip:** You can also use the **Export CSV / Import CSV** buttons for offline backups using Excel or Google Sheets.

---

## Version Roadmap

| Version | Summary |
|----------|----------|
| v3.0.0 | Base version with local storage and CSV import/export |
| v3.1.1 | Added Google Drive integration |
| v3.2.0 | Added Delete button and receipt-style print |
| v3.2.1 | Added Smart Search (barcode scanner auto-select) |
| v3.3.0+ | Planned: Configurable markup %, category summaries, and dashboard |

---

## Screenshots

*(Optional – you can add screenshots in a `screenshots` folder and link them here)*

```
/screenshots/dashboard.png
/screenshots/purchase_list.png
```

---

## Developer Notes

- Built using pure **HTML**, **CSS**, and **vanilla JavaScript** (no frameworks).
- Fully functional offline.
- Google Drive integration requires internet access and valid API credentials.
- Compatible with Chrome, Edge, Firefox, and Safari.
- Optimized for both desktop and tablet use.
- Perfect for small shops and sari-sari store owners who want a simple system that works anywhere.

---

## Credits

- **Developer:** James  
- **Project:** Mattmat’s Sari-Sari Store Inventory  
- **Assisted by:** ChatGPT (GPT-5 Build)  
- **Copyright:** © 2025 — All Rights Reserved

---

## Hosting on GitHub Pages

You can publish this app online for free using GitHub Pages:

1. Create a new GitHub repository (example: `mattmat-inventory`).
2. Upload:
   ```
   mattmat_inventory_v3_2_1_drive.html
   README.md
   ```
3. Go to **Settings → Pages → Build and deployment → Source → Deploy from branch**.
4. Under **Branch**, choose `main` and select **/(root)**.
5. Click **Save**.
6. After a few minutes, your live web app will be available at:
   ```
   https://your-username.github.io/mattmat-inventory/
   ```

---

## Final Notes

Congratulations!  
You now have a fully functional, offline-and-online hybrid sari-sari store inventory system that:

- Saves automatically  
- Works offline  
- Syncs with Google Drive  
- Supports barcode scanning  

All inside a single `.html` file.
