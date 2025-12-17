# ⚔️ Tribal Wars Command Center (Generator Rozkazów)

A lightweight, browser-based tool for **Tribal Wars (Plemiona)** players to manage and execute attack plans. This tool converts raw JSON data from planners into an interactive, trackable dashboard.

## ✨ Features

- 🕒 **Two View Modes:** Sort attacks chronologically or group them by source village.
- 📊 **Progress Tracking:** Visual progress bar and "mark as sent" functionality.
- 📋 **One-Click Copy:** Click any coordinates to copy them instantly to your clipboard.
- 🔗 **Direct Links:** Quick "Open" buttons that lead directly to the game's rally point.
- 💾 **Local Persistence:** Your plan and progress are saved in `localStorage`, so you won't lose data on page refresh.
- 🎨 **Visual Coding:** Different colors for Fakes, Offs, and Noblemen (Snobs).

---

## 🚀 How to use?

Follow these steps to load your plan:

1. **Get your data:** - Go to [plemiona-planer.pl](https://plemiona-planer.pl) and open your personal link.
   - Click on the **"Źródło"** (Source) tab.
   - Click **"Zastosuj Formatowanie stylistyczne"**.
   - Copy the entire content of the page (the JSON code).
2. **Launch the tool:**
   - Open your `Tribal_Wars_Planer.html` file in any web browser.
3. **Generate Panel:**
   - Paste the copied JSON into the text area.
   - Click **"GENERUJ PANEL"**.

---

## 🛠 Functionality Guide

| Action | Result |
| :--- | :--- |
| **OTWÓRZ** | Opens the specific attack command in Tribal Wars. |
| **✅ Checkbox** | Marks the attack as sent. |
| **Coordinate Click** | Automatically copies the village coordinates to your clipboard. |
| **Nowa rozpiska** | Clears all saved data and allows you to upload a new plan. |

> [!TIP]
> Since the data is cached using `localStorage`, you can close the browser and come back later; your progress will be exactly where you left it!

---

## 🛡️ Security & Privacy
This tool is **100% client-side**. 
- No data is sent to any server.
- No login credentials are required.
- Everything happens locally in your browser.

---
*Created for the Tribal Wars community.*
