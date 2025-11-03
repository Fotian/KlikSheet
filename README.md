<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/Logo_kliksheet_1.png" alt="KlikSheet Logo" height="72">
</p>

<h1 align="center">KlikSheet — Multi-Function Spreadsheet for Qlik Sense</h1>

<p align="center">
Enterprise-grade spreadsheet editing, writeback, collaboration, and budgeting
— built by <a href="https://www.envision.gr/en-us">Envision</a> &amp; <a href="https://applybi.com/Products/KlikSheet">ApplyBI</a> for Qlik Sense.
</p>

<p align="center">
  <a href="https://www.qlik.com/us/products/qlik-sense">Made for Qlik Sense</a> •
  <a href="https://www.youtube.com/watch?v=hYER2nGKctM">Writeback Enabled</a> •
  <a href="https://applybi.com/products/kliksheet">Enterprise Ready</a>
</p>

---

## Overview

**KlikSheet** embeds a full **Excel-like** environment inside **Qlik Sense**. It lets business users **enter, edit, validate, and write back** data (e.g., budgets, forecasts, corrections) that immediately flows into Qlik apps via governed reloads.

- 🔗 [Official product page](https://applybi.com/Products/KlikSheet)  
- 📘 [Help Manual (with visuals)](https://teddevsrv.biqcloud.com:4433/KlikSheetHelp)

---

## Architecture (light diagram)

> For official diagrams, see the [Software Architecture page](https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/SoftwareArchitecture.html) in the manual.

<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/Aug-13-2025_13-44-33.png" alt="KlikSheet Architecture (Qlik ↔ KlikSheet ↔ Database)" width="760">
</p>

---

## Core Features

- 🧮 **Excel-like Spreadsheet**
  - Formatting, formulas, validation, pivot-style analysis, import/export (CSV/XLSX/TXT)

<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/NewItem%2041.png" alt="KlikSheet Formulas Example" width="720"><br>
  <em>Formula support – Excel-style expressions within KlikSheet</em>
</p>

<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/NewItem%2042.png" alt="KlikSheet Data Validation Example" width="720"><br>
  <em>Data validation – enforce correct entry values directly in cells</em>
</p>

<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/NewItem%2038.png" alt="KlikSheet Insert Options" width="720"><br>
  <em>Insert options – quickly add rows, columns, and sections</em>
</p>

- 🔄 **Writeback & Integration**
  - Persist edits via **REST** and **MSSQL**; trigger reloads to update Qlik visualizations  

  <p align="center">
    <img src="https://github.com/Fotian/partial-reload.gif/blob/main/WriteBackKliksheet-ezgif.com-resize.gif?raw=true"
         alt="KlikSheet Writeback Functionality" width="720" />
    <br />
    <em>Writeback example – live data entry synced back to Qlik Sense</em>
  </p>

- 👥 **Multi-User Modes**
  - **Shared (default)**
  - **Version Check (exclusive edit lock)**
  - **Template-based personal workspaces**
- 📊 **Budgeting & Forecasting**
  - Spreadsheet templates, monthly breakdowns, YoY/variance, working days logic  
  > For such use cases, see the [ApplyBI YouTube channel](https://www.youtube.com/@applybi8437).

- 🔒 **Governance & Versions**
  - Version history, auditability, controlled access

<p align="center">
  <img src="https://teddevsrv.biqcloud.com:4433/KlikSheetHelp/lib/Versioning%20KlikSheet.gif" alt="KlikSheet Versioning and Governance Example" width="720">
  <br><em>Version control in KlikSheet – compare, track, and restore changes</em>
</p>

- ☁️ **Deployment**
  - Qlik **Cloud** and **On-Premise** compatible

---

## Quick Demo Use Cases (videos)

1. [Weekly Sales Report & Budget Tracking](https://www.youtube.com/watch?v=csoPKIvcXNs)  
2. [Collaborative Sales Input (real-time)](https://youtu.be/6Y5eGXCtPPw)  
3. [Super-spreadsheet: A Multi-layer Workspace](https://www.youtube.com/watch?v=0h18enlxYlk)  
4. [Multi-User: Default Mode (Shared Editing)](https://youtu.be/tpEu-vQYn04)  
5. [Multi-User: Version Check Mode (Exclusive Edit Lock)](https://youtu.be/QwMtlznHTxA)  
6. [Multi-User: Template-Based Personal Workspaces](https://youtu.be/9L9HJL_xClo)  
7. [Writeback & Integration](https://www.youtube.com/watch?v=Jc0HIBqcFrg)

More examples & screenshots:  
➡️
