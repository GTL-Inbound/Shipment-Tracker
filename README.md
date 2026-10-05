# Carrier Performance Dashboard

Interactive tracking dashboard for Global Transportation & Logistics (GTL) inbound supplier freight operations.

## 🔗 Access

**Dashboard URL**: `https://<org-name>.github.io/carrier-dashboard/`

No login required — just open the link in any browser.

## 📊 What This Dashboard Does

-   **Shipment Tracker** — View, search, sort, and filter all inbound shipments by status, carrier, origin/destination, and date
    
-   **Performance Analytics** — Carrier on-time performance, cost metrics, and trend charts
    
-   **Data Upload** — Drag and drop an updated `.xlsx` export from the Global IB Supplier Freight Tracker to refresh the dashboard
    
-   **Export** — Download filtered views as Excel, copy tables, or export charts as PDF
    

## 📁 How to Update the Data

1.  Open the dashboard URL
    
2.  Click **"Load Data"** or drag your `.xlsx` file onto the upload area
    
3.  The dashboard processes everything in your browser — no data is sent to any server
    

> **Note:** Uploaded data is session-only. Each user loads their own copy. Refreshing the page clears the data.

## 🛠️ How to Update the Dashboard Itself

If you need to change the dashboard layout, charts, or functionality:

1.  You'll need a [GitHub account](https://github.com/signup) (free) and access to this repo
    
2.  Navigate to `index.html` in this repo
    
3.  Click the ✏️ pencil icon to edit, or upload a replacement file via **Add file → Upload files**
    
4.  Commit your changes — the live site auto-updates within ~60 seconds
    

## 👥 Team Access

<table style="min-width: 75px;"><colgroup><col style="min-width: 25px;"><col style="min-width: 25px;"><col style="min-width: 25px;"></colgroup><tbody><tr><th colspan="1" rowspan="1"><p>Role</p></th><th colspan="1" rowspan="1"><p>What You Can Do</p></th><th colspan="1" rowspan="1"><p>GitHub Account Needed?</p></th></tr><tr><td colspan="1" rowspan="1"><p><strong>Viewer</strong></p></td><td colspan="1" rowspan="1"><p>Open the URL, upload data, use the dashboard</p></td><td colspan="1" rowspan="1"><p>No</p></td></tr><tr><td colspan="1" rowspan="1"><p><strong>Editor</strong></p></td><td colspan="1" rowspan="1"><p>Update the dashboard HTML file</p></td><td colspan="1" rowspan="1"><p>Yes — ask the repo owner for access</p></td></tr></tbody></table>

## 📋 Data Format

The dashboard expects an `.xlsx` file with the standard **Global IB Supplier Freight Tracker** format, including these columns:

<table style="min-width: 50px;"><colgroup><col style="min-width: 25px;"><col style="min-width: 25px;"></colgroup><tbody><tr><th colspan="1" rowspan="1"><p>Column</p></th><th colspan="1" rowspan="1"><p>Description</p></th></tr><tr><td colspan="1" rowspan="1"><p>PROGRAM</p></td><td colspan="1" rowspan="1"><p>Inbound / Outbound</p></td></tr><tr><td colspan="1" rowspan="1"><p>PROJECT TYPE</p></td><td colspan="1" rowspan="1"><p>Vendor to Site, Vendor to RAD, etc.</p></td></tr><tr><td colspan="1" rowspan="1"><p>ORIGIN WHID</p></td><td colspan="1" rowspan="1"><p>Supplier / origin warehouse</p></td></tr><tr><td colspan="1" rowspan="1"><p>DEST WHID</p></td><td colspan="1" rowspan="1"><p>Destination site code</p></td></tr><tr><td colspan="1" rowspan="1"><p>PICKUP DATE</p></td><td colspan="1" rowspan="1"><p>Scheduled pickup date</p></td></tr><tr><td colspan="1" rowspan="1"><p>DLV DATE</p></td><td colspan="1" rowspan="1"><p>Actual delivery date</p></td></tr><tr><td colspan="1" rowspan="1"><p>OT P/U?</p></td><td colspan="1" rowspan="1"><p>On-time pickup (Yes/No)</p></td></tr><tr><td colspan="1" rowspan="1"><p>OT Delv?</p></td><td colspan="1" rowspan="1"><p>On-time delivery (Yes/No)</p></td></tr><tr><td colspan="1" rowspan="1"><p>CARRIER</p></td><td colspan="1" rowspan="1"><p>Carrier name</p></td></tr><tr><td colspan="1" rowspan="1"><p>SERVICE COST</p></td><td colspan="1" rowspan="1"><p>Freight cost</p></td></tr><tr><td colspan="1" rowspan="1"><p>UNITS / PALLETS</p></td><td colspan="1" rowspan="1"><p>Volume metrics</p></td></tr></tbody></table>

## ⚠️ Privacy Note

This is a **public** GitHub Pages site — anyone with the URL can view the dashboard interface. However, no shipment data is stored on the server. Data only exists in the user's browser session while they have the page open.

## 📬 Questions?

Contact the GTL Inbound Operations team.
