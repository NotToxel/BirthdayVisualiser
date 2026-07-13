# 🎂 BirthdayVisualiser

**Explore your contacts' birthdays through interactive timelines, statistics, and insights.**

[![Version](https://img.shields.io/badge/version-v1.2.5-6366f1)](https://github.com/NotToxel/BirthdayVisualiser)
[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen)](https://nottoxel.github.io/BirthdayVisualiser/)

🔗 **[Live Demo →](https://nottoxel.github.io/BirthdayVisualiser/)**

---

## 📸 Screenshots

<!-- Add screenshots here -->
*Screenshots coming soon*

---

## ✨ Features

- **🗓 Interactive Timeline** — Zoomable vis.js timeline showing every contact's birthday, with hover cards and click-to-detail
- **📅 Calendar View** — Monthly calendar with birthday density, contact photos, mouse wheel navigation, and a date selector with heatmap preview
- **📊 Rich Statistics** — Charts for birth months, decades, years, weekdays, seasons, zodiac signs, generations, and birthstones
- **☁️ Contact Cloud** — Animated hexagonal honeycomb bubble visualisation of all contacts
- **🔍 Smart Filters** — Filter by tags, months, and name search in real-time across all views
- **⏰ Upcoming Birthdays** — Countdown list with colour-scaled urgency indicators and busiest week KPI
- **👥 Same Birthday** — Discover which contacts share the same birthday
- **📋 Missing Data** — Identify contacts missing birthday information
- **🌙 Dark Mode** — Full dark/light theme toggle
- **📱 Mobile Responsive** — Optimised layouts with bottom navigation for mobile devices
- **🔒 100% Private** — All data processing happens entirely in your browser. No data is ever uploaded or stored on any server.

---

## 🚀 Getting Started

### Option 1: Try the Demo
Visit the [live demo](https://nottoxel.github.io/BirthdayVisualiser/) and click **"Try Demo"** to explore with sample data.

### Option 2: Use Your Own Contacts
1. Export your contacts as a **CSV** or **VCF (vCard)** file (see [Export Guides](#-how-to-export-your-contacts) below)
2. Visit [BirthdayVisualiser](https://nottoxel.github.io/BirthdayVisualiser/)
3. Drag and drop your file onto the upload area, or click to browse
4. Explore your birthday data across all the available views

---

## 📁 Supported File Formats

| Format | Extension | Description |
|--------|-----------|-------------|
| **CSV** | `.csv` | Comma-separated values — the standard export from Google Contacts |
| **VCF** | `.vcf`, `.vcard` | vCard 3.0/4.0 — the standard export from Apple Contacts and many other apps |

### CSV Column Detection
BirthdayVisualiser automatically detects common column headers:
- **Name**: `Name`, `First Name`, `Given Name`, `Last Name`, `Family Name`
- **Birthday**: `Birthday`, `Bday`, `Birth Date`, `Date of Birth`, `DOB`
- **Tags/Groups**: `Label`, `Group`, `Category`
- **Photo**: `Photo`, `Avatar`, `Picture`
- **Email/Phone**: Standard email and phone column variants

---

## 📤 How to Export Your Contacts

### Google Contacts (Desktop)
1. Go to [contacts.google.com](https://contacts.google.com)
2. Click **"Export"** in the left sidebar (or select specific contacts first)
3. Choose **"Google CSV"** format
4. Click **"Export"** to download

📖 [Official Google Support Article →](https://support.google.com/contacts/answer/7199294)

### Apple Contacts (Mac)
1. Open the **Contacts** app
2. Select the contacts you want to export (or select all with `⌘A`)
3. Go to **File → Export → Export vCard...**
4. Save the `.vcf` file

📖 [Official Apple Support Article →](https://support.apple.com/en-gb/guide/contacts/adrbk1457/mac)

### Apple Contacts (iPhone/iPad)
iOS doesn't provide a built-in CSV export. You have two options:
1. **Via iCloud**: Go to [icloud.com/contacts](https://www.icloud.com/contacts), select contacts, and export as vCard
2. **Via the Contacts app**: Share individual contacts as vCard files

### Outlook
1. Go to [outlook.live.com/people](https://outlook.live.com/people/)
2. Click **"Manage contacts"** → **"Export contacts"**
3. Choose CSV format and download

### Other Providers
Most contact management apps support exporting as CSV or vCard (VCF). Check your provider's help documentation for specific instructions.

---

## 🎮 Demo Mode

Click the **"Try Demo"** button on the landing page to load [example-contacts.csv](example-contacts.csv) — a sample dataset of 30 fictional contacts spanning different decades, tag groups, and birth months. This lets you explore all features without uploading your own data.

---

## 🔒 Privacy

**Your data never leaves your browser.** BirthdayVisualiser processes everything client-side using JavaScript. No contact data is uploaded to any server, stored in any database, or shared with any third party. The application works entirely offline after the initial page load.

---

## 🛠 Tech Stack

- **HTML/CSS/JavaScript** — Single-file application, no build step required
- **[vis.js](https://visjs.org/)** — Interactive timeline visualisation
- **[Chart.js](https://www.chartjs.org/)** — Statistical charts and graphs
- **[PapaParse](https://www.papaparse.com/)** — CSV parsing
- **[Font Awesome](https://fontawesome.com/)** — Icons
- **[Google Fonts](https://fonts.google.com/)** — Outfit + Inter typography
- **GitHub Pages** — Static hosting

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0** — see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [NotToxel](https://github.com/NotToxel)
