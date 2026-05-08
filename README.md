# AutoCare AI — Car Damage Assessment PWA

A Progressive Web App (PWA) that can be installed on any phone directly from the browser.

## Features
- 📸 Upload photos of car damage (camera or gallery)
- 🤖 AI-style damage analysis (collision, paint, dent, glass, frame, bumper)
- 📍 GPS location or manual city entry
- 🏆 Top-matched repair shops ranked by expertise & distance
- 🚐 Free tow service if vehicle is not drivable (paid by service center)
- 📅 Schedule pickup / drop-off
- ✅ Booking confirmation with associate contact
- 📤 Share booking details via native share sheet
- 📱 Fully installable as a home-screen app (iOS & Android)

---

## Deploy to GitHub Pages (free)

1. Create a GitHub account at https://github.com if you don't have one
2. Click **New Repository** → name it `autocare-app` → set to **Public** → Create
3. Upload all files (drag & drop in the browser, or use git):
   ```
   autocare-app/
   ├── index.html
   ├── manifest.json
   ├── sw.js
   └── icons/
       └── icon.svg
   ```
4. Go to **Settings → Pages → Source → main branch → / (root)** → Save
5. Your app will be live at: `https://YOUR-USERNAME.github.io/autocare-app/`

---

## Install on Phone

### Android (Chrome)
- Visit the URL in Chrome
- A banner will appear: **"Add AutoCare AI to Home Screen"** — tap Install
- Or tap ⋮ menu → **Add to Home Screen**

### iPhone / iPad (Safari)
- Visit the URL in Safari
- Tap the **Share** button ⬆
- Scroll down and tap **"Add to Home Screen"**
- Tap **Add** — the app appears on your home screen like a native app

---

## Local Testing

```bash
# If you have Python installed:
cd autocare-app
python -m http.server 8080
# Then open http://localhost:8080 in your browser
```

Or install the VS Code **Live Server** extension and right-click `index.html` → Open with Live Server.
