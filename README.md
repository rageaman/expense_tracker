# Expense Tracker

<p align="center">
  A simple and clean browser-based expense tracker for recording, managing, saving, importing and exporting daily expenses.
</p>

<p align="center">
  <a href="https://rageaman.github.io/expense_tracker/">
    <img src="https://img.shields.io/badge/%F0%9F%8C%90%20LIVE%20DEMO-181717?style=for-the-badge&labelColor=181717" alt="Live Demo">
  </a>
</p>

---

## 💸 About

Expense Tracker is a lightweight browser-based application for keeping daily expense records organized.

Add expenses with name, amount, date, category and optional quantity/details, manage saved entries, calculate totals, export records to PDF, and save or import your data as JSON files.

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 📊 Expense Management

- Add and update expense entries
- Edit and delete existing expenses
- Move expenses up or down in the list
- Track name, amount, date and category
- Add optional quantity/details
- Calculate amount × quantity when enabled
- Display the overall expense total

</td>
<td width="50%" valign="top">

### 💾 Save & Import

- Save expense data as a JSON file
- Import previously saved JSON data
- Replace current data or add imported data
- Drag & Drop JSON import when the list is empty
- Preserves PDF header and title settings in saved data

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### 📄 PDF Export

- Download expense records as a PDF
- Enable or disable PDF columns
- Rename PDF column headers
- Customize the PDF title
- Reset PDF headers to their defaults
- PDF export becomes available when expenses exist

</td>
<td width="50%" valign="top">

### 🎨 Interface & Theme

- Clean and minimal interface
- Responsive desktop and mobile layout
- Light, dark and system theme modes
- Touch-friendly controls
- Simple modal settings for import, PDF headers and theme

</td>
</tr>
</table>

---

## 🛠️ Built With

<table>
<tr>
<td align="center" width="100%"><strong>HTML5 + Tailwind CSS + JavaScript</strong><br>Complete application contained in a single <code>index.html</code> file</td>
</tr>
</table>

### 📦 External Libraries

- Tailwind CSS via CDN
- jsPDF via CDN
- jsPDF AutoTable via CDN

---

## 📁 Project Structure

```text
expense_tracker/
├── index.html
└── README.md
```

| File | Description |
|------|-------------|
| `index.html` | Complete expense tracker — interface, styling, functionality and integrations |
| `README.md` | Project documentation |

---

## 🚀 Run Locally

No build tools or package installation are required.

```bash
git clone https://github.com/rageaman/expense_tracker.git
cd expense_tracker
```

Then open `index.html` directly in your browser.

For a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

> An internet connection is required for the CDN-hosted Tailwind CSS and PDF libraries to load.

---

## 📱 Responsive Design

The expense tracker is designed to work across desktop and mobile screen sizes with a simple, touch-friendly interface.

---

## 🤝 Contributing

Contributions, suggestions and improvements are welcome.

---

## ⭐ Support

<p align="center">
  <a href="https://github.com/rageaman/expense_tracker">
    <img src="https://img.shields.io/badge/%E2%98%85%20STAR%20THIS%20REPOSITORY-6e40c9?style=for-the-badge&labelColor=24292f&logo=github&logoColor=white" alt="Star this repository">
  </a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/%E2%99%A5%20MADE%20WITH%20LOVE%20BY-RAGEAMAN-24292f?style=for-the-badge" alt="Made with love by RageAman">
</p>
