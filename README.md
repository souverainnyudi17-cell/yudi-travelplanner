# 🌴 YUDI Travelplanner

Een interactieve reis-planning PWA met gedetailleerde dagplanningen, budgetoverzichten en checklists.

## ✨ Features

- 📅 **Dag-voor-dag planning** met tijdlijn en activiteiten
- 💰 **Budget tracker** met budget/comfort opties
- ✅ **Checklist** met localStorage opslag
- 🔐 **Password-protected reizen**
- 📱 **PWA** - installeerbaar op telefoon
- 🌙 **Offline support** via service worker

## 🗺️ Reizen

| Reis | Dagen | Budget | Status |
|------|-------|--------|--------|
| 🌴 Canarische Eilanden | 9 | €3.060 | Open |
| 🏔️ Montenegro | 9 | €2.440 | 🔒 Locked |
| 🎄 London Christmas | 4 | €1.200 | 🔒 Locked |

## 🚀 Deploy

```bash
# Vercel
vercel --prod

# Of upload naar elke statische hosting
```

## 📁 Structuur

```
├── index.html      # Homepage
├── tenerife.html   # Canarische Eilanden trip
├── montenegro.html # Montenegro trip  
├── london.html     # London Christmas trip
├── manifest.json   # PWA manifest
├── sw.js          # Service worker
└── icon-192.png   # App icon
```

## 🔐 Password

Locked trips: `02.05.2025`

---

Made with ❤️ by YUDI
