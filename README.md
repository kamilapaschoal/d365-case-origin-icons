# 🧩 Customizing Case Origin Icons in Dynamics 365 Customer Service

In this guide, I'll show you how to **add new options to the Case Origin field** (`incident_caseorigincode`) in Dynamics 365 and display **custom SVG icons** in the views.

This feature improves user experience by adding visual cues directly in the grid.

---

## 📌 What You’ll Learn

- How to add new options to the global choice "Case Origin"
- How to name and upload SVG icons for those new options
- How Dynamics 365 uses Web Resources to map icons

---

## 🛠️ Steps to Add Icons for New Case Origin Options

### 1️⃣ Add new options to the Case Origin field

Navigate to the **Global Choice** field:  
`Case Origin` (`incident_caseorigincode`)

Add new options such as:
- `WhatsApp` (Value: `956250001`)
- `Chat` (Value: `956250002`)

✅ These values will define the filenames for the icons.

---

### 2️⃣ Identify how icon files are named

Search in **Solutions > Web Resources** using the keyword:
