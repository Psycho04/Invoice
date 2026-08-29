# Saudi Arabian Tax Invoice Template | نموذج فاتورة ضريبية سعودية

A professional, modern, and print-ready Saudi Arabian Tax Invoice (فاتورة ضريبية) template built using semantic HTML5, pure CSS3, and lightweight vanilla JavaScript. Fully compliant with Saudi ZATCA (FATOORA) standards and 15% VAT regulations.

Designed for **Fahs Alturba Company for Engineering Consultancy (شركة فحص التربة للإستشارات الهندسية - جسات / GSSAAT)**.

---

## 🌟 Key Features

- **Official Corporate Branding**: Integrates official high-resolution header and footer banners with branch information (Riyadh, Jeddah-Makkah, Madinah, Dammam) and ISO accreditations (ISO 14001, ISO 9001, ISO 45001, SAC).
- **ZATCA (FATOORA) Standard Compliance**:
  - 15-digit VAT Registration numbers for both Seller (`310458921400003`) and Buyer (`300984521400003`).
  - Standard Commercial Registration (CR) records.
  - Subtotal, Item-level Discounts, Taxable Amount, 15% VAT, and Grand Total.
  - **Dynamic ZATCA Phase 2 QR Code**: Generates Base64-encoded TLV (Tag-Length-Value) payload according to official ZATCA guidelines.
- **Bilingual & RTL Support**: Balanced Arabic and English dual labels side-by-side using Google Fonts (`Cairo` + `Inter`).
- **Tafqeet (Amount in Words)**: Automatic real-time conversion of grand total into written words in Arabic (*ريال سعودي*) and English (*Saudi Riyals*).
- **A4 Print & PDF Ready**: Strict `@media print` and `@page { size: A4 portrait; margin: 0; }` configuration for pixel-perfect printing and PDF generation with zero clutter.
- **Live In-Browser Editing**: Modify quantities, descriptions, discounts, or unit prices directly on the page with automatic calculation updates.

---

## 📁 Project Structure

```
Invoice/
├── Assets/
│   ├── Header.jpeg    # Official GSSAAT Header Banner
│   └── Footer.jpeg    # Official GSSAAT Footer Banner with Branch & ISO Details
├── index.html         # Standalone Invoice Template (HTML, CSS & JS)
└── README.md          # Project Documentation
```

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser:

1. **View & Edit**: Directly click and edit any editable fields (e.g., customer details, quantities, unit prices, discounts).
2. **Add/Delete Items**: Use the floating toolbar buttons to add new service items or remove existing ones.
3. **Print or Save as PDF**: Click the **Print / حفظ PDF** button or press `Ctrl + P` (Command + P on macOS) and choose **Save as PDF**.

---

## 📄 License

MIT License. Free to use and customize.
