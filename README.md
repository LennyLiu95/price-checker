# 🧾 Product Price Checker

A lightweight tool to check product prices by uploading an `.xlsx` file and searching by keywords (first column only).

---

## ✨ Features

- 📁 Upload `.xlsx` file (via SheetJS)
- 🔍 Keyword-based search (matches first column only, typically product names)
- 🧾 Local notes saved in browser (`localStorage`)
- 📊 Clean, responsive display table
- 💡 Minimal, elegant UI

---

## 🚀 Live Demo

👉 [Click to Open](https://your-github-pages-link)  
> Replace with your GitHub Pages URL

---

## 🛠 How to Use

1. Prepare an `.xlsx` file with your product data.
2. Make sure the **first row is the header** and the **first column contains the product name or code**.
3. Upload the file using the "Choose File" button.
4. Enter keywords in the search box (supports multiple).
5. Results will match rows where all keywords appear in the **first column**.
6. Optionally, write notes in the Notes area and save locally.

---

## 📂 Example `.xlsx` File Format

| Product Name       | Price | Stock       |
|--------------------|-------|-------------|
| Apple iPhone 13    | 899   | In Stock    |
| Samsung Galaxy S22 | 799   | Out of Stock |

> ✅ Only the first column (`Product Name`) is used for keyword search.

---

## 🧰 Tech Stack

- HTML, CSS, JavaScript
- [SheetJS](https://sheetjs.com/) (for reading Excel files)
- `localStorage` (for saving notes)

---

## 🧪 Limitations

- Only `.xlsx` format is supported.
- Search applies to the **first column only**.
- File must have **headers in the first row**.

---

## 📜 License

MIT
