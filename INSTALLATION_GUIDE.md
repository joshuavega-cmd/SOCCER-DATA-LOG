# Soccer Tagging PWA - Installation Guide

## 📦 What You'll Need

Your PWA consists of 5 files:
1. `tagging_pad.html` - Main app
2. `manifest.json` - App metadata
3. `service-worker.js` - Offline functionality
4. `icon-192.png` - Small icon
5. `icon-512.png` - Large icon

## 🎨 Step 1: Create Icons

1. Open `icon-generator.html` in your browser
2. Right-click the first canvas → "Save Image As..." → save as `icon-192.png`
3. Right-click the second canvas → "Save Image As..." → save as `icon-512.png`

OR use any 192x192 and 512x512 PNG images you prefer!

## 🌐 Step 2: Host Your PWA

### Option A: GitHub Pages (Recommended)

1. Go to github.com and create free account
2. Click "New Repository"
3. Name it: `soccer-tagging-app`
4. Make it Public
5. Click "uploading an existing file"
6. Drag all 5 files into the upload area:
   - tagging_pad.html
   - manifest.json
   - service-worker.js
   - icon-192.png
   - icon-512.png
7. Click "Commit changes"
8. Go to Settings → Pages
9. Under "Source" select "Deploy from a branch"
10. Select "main" branch
11. Click Save
12. Wait 2-3 minutes
13. Your app URL will be: `https://yourusername.github.io/soccer-tagging-app/tagging_pad.html`

### Option B: Netlify Drop

1. Go to app.netlify.com
2. Create free account
3. Drag all 5 files into Netlify Drop zone
4. Get instant URL like: `https://your-site.netlify.app/tagging_pad.html`

## 📱 Step 3: Install on iPad

### Method 1: Safari Add to Home Screen

1. Open your app URL in Safari on iPad
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Edit the name if you want (e.g., "Game Tagging")
5. Tap "Add"
6. App icon appears on your home screen!

### Method 2: Install Button (Android/Chrome)

1. Open your app URL
2. Look for "📱 Install App" button in bottom-right
3. Tap it and follow prompts
4. App installs like a native app!

## ✨ PWA Features

✅ **Works Offline** - Once loaded, works without internet
✅ **Auto-Saves** - Your data is saved automatically
✅ **Persistent** - Reload and your data is still there
✅ **Fast** - Loads instantly after first visit
✅ **Standalone** - Runs in full-screen (no browser UI)

## 💾 Data Management

**Where is data stored?**
- Locally on your device in browser storage
- NOT in the cloud
- Specific to each device

**Export your data:**
- Always export to Excel/CSV after each game
- Data only exists on the device you're using

**Clear data:**
- Use "Clear All Data" button in app
- Or clear browser data for the site

## 🔄 Updating the App

**To update:**
1. Upload new `tagging_pad.html` to GitHub/Netlify
2. On your iPad, close and reopen the app
3. May need to wait 24 hours for cache to clear
4. Or clear Safari cache for your site

## 🆘 Troubleshooting

**App won't install on iPad:**
- Must use Safari (not Chrome)
- Make sure all 5 files are in same folder online
- Check browser console for errors

**Install button doesn't appear:**
- Some browsers don't support install prompts
- Use Safari "Add to Home Screen" instead

**Data disappeared:**
- Did you clear browser data?
- Are you on a different device?
- Use Incognito/Private mode? (data doesn't save there)

**App won't work offline:**
- Visit app once while online first
- Service Worker needs to cache files
- Check that service-worker.js loaded correctly

## 🎯 Pro Tips

1. **Landscape Mode**: App is optimized for landscape on iPad
2. **Fullscreen**: Works best when installed as PWA
3. **Export Regularly**: Always export data after games
4. **Bookmark URL**: Keep URL handy for other devices
5. **Share with Team**: Give assistants the URL too!

## 📊 What Gets Saved

- All tagged events
- Game details (date, opponent, score, competition)
- Timestamp when you last used it

## 🔐 Privacy

- All data stays on your device
- Nothing is uploaded to any server
- No tracking or analytics
- Completely private

## 📧 Need Help?

If something isn't working, check:
1. Are all 5 files uploaded?
2. Are they in the same directory?
3. Did you use exact filenames?
4. Are you using Safari on iPad?

---

Made with ⚽ for soccer coaches!
