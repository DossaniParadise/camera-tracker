# Camera Job Tracker

A real-time collaborative job tracking system with an interactive map for managing camera installation/repair jobs across multiple locations.

## 🚀 Quick Start

**The tracker is ready to use RIGHT NOW!** Just follow these steps:

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to https://github.com
2. Click "Sign up"
3. Follow the prompts (takes 2 minutes)

### Step 2: Upload This to GitHub
1. Log into GitHub
2. Click the "+" icon in the top right → "New repository"
3. Name it: `camera-tracker`
4. Make it **Public**
5. Click "Create repository"
6. On the next page, you'll see "upload an existing file" - click that
7. Upload the `index.html` file from this folder
8. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click "Settings" (top right)
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes
6. Your site will be live at: `https://YOUR-USERNAME.github.io/camera-tracker/`

## ✅ Features

- **Interactive Map**: All 49 locations plotted with color-coded markers
- **Job Statuses**: Not Started (gray), In Progress (orange), Completed (green)
- **Job Details**: Track Job ID, issue descriptions, and notes
- **Collaboration**: Export/Import data to share updates with your team
- **No Login Required**: Just share the URL
- **Works Offline**: Data saves in your browser
- **Mobile Friendly**: Works on phones and tablets

## 📱 How to Share Updates

Since this version uses browser storage, you and your technician share updates this way:

1. **After making changes**, click "Export Data" button (top right)
2. **Send the downloaded file** to your teammate (via email, text, etc.)
3. **They click "Import Data"** and upload the file
4. **Done!** They now have all your updates

This happens automatically once per day/week, or whenever you want to sync.

## 🔄 Want Real-Time Sync?

If you want INSTANT updates without import/export:
1. Set up Firebase (takes 5 minutes, completely free)
2. I can provide you with the Firebase version instead
3. Both of you will see changes instantly

## 💡 Tips

- Bookmark the GitHub Pages URL on both devices
- Export data before making major changes (backup)
- Use the notes field to tag each other: "@John can you check this?"
- Click locations in the sidebar to zoom to them on the map

## 🛠 Customization

The tracker is a single HTML file (`index.html`). You can:
- Open it in any text editor (Notepad works!)
- Change colors by editing the color variables at the top
- Add more locations by adding to the `locations` array
- Modify status options in the JavaScript

## ❓ Troubleshooting

**Map doesn't load:**
- Check your internet connection
- Make sure JavaScript is enabled in your browser

**Data not saving:**
- Make sure you're clicking the "Save" button in popups
- Check that browser storage isn't disabled
- Try exporting data as a backup

**Can't see teammate's changes:**
- This version requires import/export to share data
- For instant sync, ask for the Firebase version

## 📞 Need Help?

Contact me or check GitHub Issues if you run into problems!

---

Made with ❤️ for tracking camera jobs across Texas
