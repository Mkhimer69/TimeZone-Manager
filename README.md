<h1 align="center">🕒 TimeZone Manager</h1>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.2.0-orange?style=flat">
  <img src="https://img.shields.io/badge/engine-Tampermonkey-00485B?style=flat">
  <img src="https://img.shields.io/badge/network-none-success?style=flat">
  <img src="https://img.shields.io/badge/theme--aware-Theme%20Studio-e6c876">
</p>

> **Force any website to render its times in *your* time zone.** A floating
> 🕒 icon gives every page a location + short-code picker — CST, EST, EGY,
> IST, JST… — and tells you which time zone is actually affecting the page
> right now. No accounts, no server, nothing leaves your browser.

## ✨ Features

| Area | What you get |
|---|---|
| 🌍 **Location + short code picker** | Choose *Central Time (US) — CST*, *Cairo — EGY*, *India — IST* and friends; the label always shows the location, then the familiar short |
| 🕑 **What's affecting this page?** | The panel's status box shows the zone currently rendering the page's times, its short code and a **live clock** in that zone |
| 🧬 **Real override, not display tricks** | Wraps `Intl.DateTimeFormat` itself before the page runs (`document-start`), so every timestamp the page formats — widgets, tables, e-mails previews — obeys your zone |
| 🎨 **Theme Studio aware** | Inherits the suite's theme: when Theme Studio changes palette, the icon, panel and toasts re-skin instantly (with matching dark defaults everywhere else) |
| 🫥 **Ctrl+Alt+D** | Hide/show the floating icon per-site — the chosen zone keeps working even while the icon is hidden |
| 🔔 **Quiet feedback** | Toasts instead of alerts for every save/clear, plus the shared system-notify hook for desktop notices where allowed |

## 📥 Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/)

📺 [Video guide](https://github.com/Mkhimer69/AWS-Toolkit/blob/main/screenshots/install-tampermonkey.mp4)

📺 [Install demo](https://github.com/Mkhimer69/AWS-Toolkit/blob/main/screenshots/install%20AWS%20toolkit.gif)

2. Install **TimeZone Manager** — no configuration needed
3. Open any site → click the 🕒 icon (bottom-right) → pick a zone
4. Refresh the page — done; timestamps everywhere now use your zone

## 🖥 Usage

- **Pick a zone** → saves immediately; a toast tells you a refresh applies it
- **Browser Default** clears the override — back to the site's own behavior
- **Ctrl+Alt+D** hides/shows the floating icon; the panel remembers per-site
- Zones that already picked their own zone in code (e.g. calendar widgets) are respected — the override only fills gaps

## 🔒 Privacy

Everything is on your machine. No network at all — no API,
no analytics, no sync.

---

<div align="center">

<b>🕒 TimeZone Manager</b><br><i>Your site, your timezone.</i><br><br>
**Fathy Mkhimer** · Lead Real-Time Analyst · [GitHub](https://github.com/Mkhimer69)

</div>
