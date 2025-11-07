# ⚠️ Power BI Message Bars  

**Date:** 2025-11-07  
**Version:** 1.0.0  

---

## 📝 Description  

The **Power BI Message Bars** are dynamic, contextual alert components that provide users with **real-time feedback** on report status, data thresholds, and applied filters.  
They enhance data storytelling and operational awareness by displaying success confirmations, warnings, and critical alerts directly within Power BI reports — no external explanations required.  

Beyond awareness, Message Bars **guide users toward action** by clearly indicating where performance issues, risks, or anomalies require attention.  
They adjust automatically based on **DAX-driven conditions**, updating color, text, and icons to reflect both performance status **and urgency of response**.  

![Preview](../../Images/Message%20Bars.png)  

---

## 🌐 Live Report  

Explore the live interactive version here:  
🔗 [**Open in Power BI Service**](https://app.powerbi.com/view?r=eyJrIjoiZWYzMTgwOWMtMGUyNy00MjhjLTgxMTUtMjU0YmFkYmE4NjZiIiwidCI6IjQxYmVjZTAxLTYyNGQtNGE4YS1hNzFmLWQ1ZTQ0MmY1MTFjMSJ9)  

**Prompt to use:**  
👉 *Go to Page 2 using the navigation option at the bottom for interactive versions.*

---

## 🎥 Demo Video  

https://github.com/user-attachments/assets/da3baf79-f560-4cd8-ad62-14c6cfccd99e  

---

## 📂 File List  

- `Power BI Message Bars.pbix` – Power BI Desktop file  
- `Icons.zip` – Set of icons used in the file (included for optional reuse; no updates or path changes required)  

---

## ⚡ Power BI Requirements  

- Power BI Desktop (October 2025 or later)  
- All visuals are **native to Power BI** — no custom visuals or add-ins needed  
- Uses standard DAX-based logic for conditional formatting  

---

## 🧭 How to Use  

1. Download `.pbix` and `Icons.zip`.  
2. Open `.pbix` in Power BI Desktop.  
3. The icons included are already embedded; no repointing is necessary.  
4. Adjust message logic using your own **KPI and threshold measures**.  
5. Place the message bars at the top of your report pages.  
6. Optionally link “Clear” buttons to slicer resets or bookmarks.  

---

## 🧩 Message Types  

| Type | Description | Color | Example Use |
|------|--------------|--------|--------------|
| **Filters Applied** | Indicates active filters affecting visible results. | Gray | Active slicers on the page. |
| **Success** | Confirms KPIs are meeting/exceeding targets. | Green | Performance above 95% of goal. |
| **Caution** | Warns of approaching performance decline. | Amber | Metric nearing lower threshold. |
| **Critical Issue** | Highlights severe underperformance or data issue. | Red | KPI far outside target range. |

---

## 🎨 Design Details  

- Rounded containers and soft borders.  
- Icons from the provided `Icons.zip` set — already embedded in the `.pbix` file.  
- Distinct background colors (Gray / Green / Amber / Red).  
- Light gradient canvas background for depth.  
- Optional interactive “Clear” button to reset context.  

---

## 📝 Notes  

- Designed for Power BI professionals focused on data clarity, decision guidance, and contextual insight.  
- Icons are provided for **optional reuse in other reports or design projects**.  
- Gradient background credit: [Image by juicy_fish on Freepik](https://www.freepik.com/free-vector/green-purple-gradient-background_43181516.htm)  

---

## ⭐ Support  

If you find this helpful, **star this repository** to stay updated.  

<p align="center">
  <a href="https://buymeacoffee.com/doccrs" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" height="50" width="210" />
  </a>
  <br>
  <sub>Support ongoing Power BI UX design templates and open community resources.</sub>
</p>

---
