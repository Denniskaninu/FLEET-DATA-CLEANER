# Fleet Data Cleaner

Fleet Data Cleaner is a simple yet powerful web tool for processing and organizing fleet device data from Excel files. It helps you to quickly sort, categorize, and export device lists based on country and validity status, making fleet management and reporting much easier.

## Features

- **Excel File Support:** Easily upload `.xlsx` and `.xls` files containing your fleet data.
- **Automatic Categorization:** Devices are automatically sorted into Valid and Expired groups, and further classified by country: Kenya, Tanzania, or Uganda.
- **Instant Statistics:** View live counts of total, valid, expired devices, and per-country breakdown.
- **Clean Downloads:** Download categorized device lists as new Excel files for each country and status.
- **Processing Log:** See a detailed log of each step during the processing for transparency and troubleshooting.
- **Modern UI:** Fast, mobile-friendly interface built with TailwindCSS and FontAwesome.

## How It Works

1. **Upload File:** Drag & drop your Excel file or click to browse.
2. **Process Devices:** Click "Process Devices" to start automatic sorting and cleaning.
3. **Review Output:** Instantly see categorized files and download them as needed.
4. **Check Stats:** Monitor device totals and country breakdowns in real time.

## Example Workflow

1. Prepare your device list in Excel, ensuring the columns include "Device" and "Remain(Day)".
2. Upload the file via the web UI.
3. Click `Process Devices`.
4. Download the results:
    - Kenya_Valid_DEVICES.xlsx
    - Kenya_Expired_DEVICES.xlsx
    - Tanzania_Valid_DEVICES.xlsx
    - Tanzania_Expired_DEVICES.xlsx
    - Uganda_Valid_DEVICES.xlsx
    - Uganda_Expired_DEVICES.xlsx

## Technologies

- HTML, CSS (TailwindCSS)
- JavaScript (uses [SheetJS/xlsx](https://github.com/SheetJS/sheetjs) for Excel parsing)
- No backend/server required — all processing is done in your browser!

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Start cleaning your fleet data!

## License

This project is licensed under the MIT License.

---

*Fleet Data Cleaner saves time for fleet managers and data analysts. If you find it useful, please star the repo and share feedback!*
