# 🏪 StallTrack — Stall Rent Management System

A mobile-friendly web app for managing stall rentals, tenant records, payments, utilities, and maintenance. Built as a Progressive Web App (PWA) — installable on any phone or browser.

---

## 🌐 Live App

👉 **[https://ShemMartin.github.io/stall_tracker/](https://ShemMartin.github.io/stall_tracker/)**

Default password: `admin1234` *(change this immediately in Settings after first login)*

---

## 📱 Features

- **6 Stalls** — track occupancy, rent (KSh 6,000 / KSh 6,500), and deposit (KSh 6,500 one-off)
- **Tenant Management** — assign tenants, store contact details, move-in dates, and rent due days
- **Tenant History** — when a tenant moves out their full record is archived, not deleted
- **Payment Recording** — M-Pesa, Cash, Bank Transfer with transaction reference numbers
- **WhatsApp Receipts** — generate and share payment receipts directly to tenants via WhatsApp
- **Utility Bills** — track water and electricity bills per stall
- **Maintenance Requests** — log and track repair issues with priority levels
- **Overdue Alerts** — dashboard flags stalls that haven't paid this month
- **Deposit Tracking** — separate from rent, shown clearly per tenant
- **Backup & Restore** — export all data as a JSON file, restore on any device
- **Firebase Database** — all data synced to Google Cloud, safe across devices
- **Password Protection** — secured with a password + security question
- **PWA** — installs on Android/iPhone home screen, works offline

---

## 🗂️ File Structure

```
stall_tracker/
├── index.html       # Main app (all HTML, CSS, JavaScript)
├── manifest.json    # PWA manifest (app name, icons, theme)
├── sw.js            # Service worker (offline support, caching)
├── icon-192.png     # App icon (192x192)
├── icon-512.png     # App icon (512x512)
└── README.md        # This file
```

---

## 🔧 How to Update the App

1. Download the latest `index.html` from Claude
2. Rename it to `index.html` if needed
3. Go to `github.com/ShemMartin/stall_tracker`
4. Click `index.html` → click the **pencil ✏️ edit icon**
5. Delete all content → paste the new code
6. Click **Commit changes**
7. Wait ~2 minutes → refresh the live URL

---

## 📲 How to Install on Phone

**Android (Chrome):**
1. Open the live URL in Chrome
2. Tap the 3-dot menu (⋮)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

**iPhone (Safari):**
1. Open the live URL in Safari
2. Tap the **Share button** (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

---

## 🔒 Security Setup (Do This First!)

1. Log in with default password `admin1234`
2. Go to ⚙️ **Settings → Set Security Question** — choose a question and set your answer
3. Go to **Settings → Change Password** — answer the question, then set a new password
4. Your new password syncs to Firebase and works on all devices instantly

---

## 💾 Backup Instructions

Your data is stored in Firebase (Google Cloud) and is safe even if you format your phone. However it's good practice to keep a local backup too:

1. Go to ⚙️ **Settings → Export Backup**
2. Save the downloaded `.json` file to **Google Drive**
3. Repeat weekly (the app will remind you after 7 days)

To restore: **Settings → Restore from Backup** → pick the `.json` file

---

## 🛠️ Built With

- Plain HTML, CSS, JavaScript (no frameworks)
- [Firebase Firestore](https://firebase.google.com) — cloud database
- Hosted on [GitHub Pages](https://pages.github.com) — free hosting
- Progressive Web App (PWA) — installable, works offline

---

## 📞 Support

Built for personal use. For any issues, update the app via Claude at [claude.ai](https://claude.ai).
