<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/Logo_kliksheet_1.png" alt="KlikSheet Logo" height="72">
</p>

<h1 align="center">KlikSheet — Multi-Function Spreadsheet for Qlik Sense</h1>

<p align="center">
Enterprise-grade spreadsheet editing, writeback, collaboration, and budgeting
— built by <a href="https://www.envision.gr/en-us">Envision</a> &amp; <a href="https://applybi.com/Products/KlikSheet">ApplyBI</a> for Qlik Sense.
</p>

<p align="center">
  <a href="#">Made for Qlik Sense</a> •
  <a href="#">Writeback Enabled</a> •
  <a href="#">Enterprise Ready</a>
</p>

---

## Overview

**KlikSheet** embeds a full **Excel-like** environment inside **Qlik Sense**. It lets business users **enter, edit, validate, and write back** data (e.g., budgets, forecasts, corrections) that immediately flows into Qlik apps via governed reloads.

- 🔗 Official product page: https://applybi.com/Products/KlikSheet  
- 📘 Help Manual (with visuals): https://teddevsrv.biqcloud.com:4433/KlikSheetHelp

---

## Architecture (light diagram)

> For official diagrams, see the **Software Architecture** page in the manual:

<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/Aug-13-2025_13-44-33.png" alt="KlikSheet Architecture (Qlik ↔ KlikSheet ↔ Database)" width="760">
</p>
-->https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/SoftwareArchitecture.html

---
---

## Core Features

- 🧮 **Excel-like Spreadsheet**
  - Formatting, formulas, validation, pivot-style analysis, import/export (CSV/XLSX/TXT)
<p align="center"> <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/NewItem%2041.png" alt="KlikSheet Formulas Example" width="720"><br> <em>Formula support – Excel-style expressions within KlikSheet</em> </p> <p align="center"> <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/NewItem%2042.png" alt="KlikSheet Data Validation Example" width="720"><br> <em>Data validation – enforce correct entry values directly in cells</em> </p> <p align="center"> <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/NewItem%2038.png" alt="KlikSheet Insert Options" width="720"><br> <em>Insert options – quickly add rows, columns, and sections</em> </p>

- 🔄 **Writeback & Integration**
  - Persist edits via **REST** and **MSSQL**; trigger reloads to update Qlik visualizations  

  <p align="center">
   <img src="https://github.com/Fotian/Fotis/blob/main/WriteBackKliksheet-ezgif.com-resize.gif?raw=true"
     alt="KlikSheet Writeback Functionality" width="720" />
    <br />
    <em>Writeback example – live data entry synced back to Qlik Sense</em>
  </p>

- 👥 **Multi-User Modes**
  - **Shared (default)**
  - **Version Check (exclusive edit lock)**
  -  **Template-based personal workspaces**
- 📊 **Budgeting & Forecasting**
  - Spreadsheet templates, monthly breakdowns, YoY/variance, working days logic
 > For such use cases, see the **YouTube channel** page:
-->https://www.youtube.com/@applybi8437
    
- 🔒 **Governance & Versions**
  - Version history, auditability, controlled access
<p align="center"> <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/Versioning%20KlikSheet.gif" alt="KlikSheet Versioning and Governance Example" width="720"> <br><em>Version control in KlikSheet – compare, track, and restore changes</em> </p>
- ☁️ **Deployment**
  - Qlik **Cloud** and **On-Premise** compatible

---

## Quick Demo Use Cases (videos)

1. **Weekly Sales Report & Budget Tracking** – https://www.youtube.com/watch?v=csoPKIvcXNs  
2. **Collaborative Sales Input (real-time)** – https://youtu.be/6Y5eGXCtPPw
3. **Super-spreadsheet:A Multy-layer workspace)** – https://www.youtube.com/watch?v=0h18enlxYlk  
4. **Multi-User: Default Mode (Shared Editing)** – https://youtu.be/tpEu-vQYn04  
5. **Multi-User: Version Check Mode (Exclusive Edit Lock)** – https://youtu.be/QwMtlznHTxA  
6. **Multi-User: Template-Based Personal Workspaces (Multi-User Templates)** – https://youtu.be/9L9HJL_xClo  
7. **Writeback & Integration** – https://www.youtube.com/watch?v=Jc0HIBqcFrg  

More examples & screenshots:  
➡️ https://www.youtube.com/@applybi8437

---

## Installation

KlikSheet ships as a signed Qlik Sense extension.

1. Import the extension via QMC (on-prem) or Qlik Cloud hub.
2. Configure the **KlikSheet Backend (IIS)** and **MSSQL** connection.
3. Add the KlikSheet object to your sheet and connect to your app model.
4. (Optional) Enable multi-user mode, versioning, and writeback options.

📗 Full guide: https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Installation-Guide.html

---


## Documentation Index (handy links)

- **Ribbon Menu (features & options):**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Ribbon-Menu-Breakdown.html

- **Multi-User Functionality:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Multi-Userfunctionality.html

- **Use of Versions (Version Control & Drafts):**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Use-of-Versions.html

- **System Requirements:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/System-Requirements.html

- **Software Architecture:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Software-Architecture.html

- **Writeback & Reload Options (Three-Dots Menu):**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Three-dots-menu.html

- **Data Editing & Validation:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Does-Kliksheet-supports-Data-Editing-Validation.html

- **Excel Compatibility & Pivot Tables:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/What-is-KlikSheets-compatibility-with-Microsoft-Excel.html

- **Budget Drafting & Forecasting:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Can-KlikSheet-be-used-for-budget-drafting.html

- **Calculations & Formulas:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Calculations-within-KlikSheet.html

- **Reload Efficiency (Partial & Full):**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Is-Kliksheet-efficient-when-it-comes-to-the-need-to-reload-Qlik-apps.html

- **Upload External Excel Files:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Upload-external-Excel-spreadsheet-directly-into-Qlik-Sense.html

- **Manipulate Qlik Data Directly:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Manipulate-data-directly-into-Qlik-Sense-app.html

- **Paste Qlik Data into KlikSheet:**  
  https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/Paste-Qlik-data-into-KlikSheet.html



---

## Support

- ✉️ info@envision.gr  
- 🌐 Envision: https://www.envision.gr/en-us  
- 🌐 ApplyBI: https://applybi.com/Products/KlikSheet
- 🤖 KlikSheet Assistant bot: https://chatgpt.com/g/g-68becbb29010819185cf07d73bbe4b93-kliksheet-assistant

For feature confirmations or CUSTOM requests, please contact Envision/ApplyBI Support.

---

## License

KlikSheet is a **commercial extension for Qlik Sense**.  
Request a quote or demo: info@envision.gr

---

## Credits

Built by **Envision** & **ApplyBI**.  
Qlik® and Qlik Sense® are trademarks of QlikTech International AB.
