# HVAC Closer: The All-in-One HVAC Sales Tool

**HVAC Closer** is a browser-based in-home sales presentation tool built specifically for HVAC professionals. It streamlines the entire sales process — from system sizing and proposal generation to financing and signature capture — all in a single, self-contained HTML file.

Easily hostable on GitHub Pages or any static web server.

---

## 🔧 Features

- **Dynamic Proposal Generator**  
  Instantly build "Good, Better, Best" system packages with pricing.

- **Comprehensive Job Assessment**  
  Capture all essential info including:
  - Customer contact
  - Jobsite access conditions
  - Detailed notes

- **Multiple System Types Supported**
  - Furnace & AC  
  - Heat Pump & Air Handler  
  - Air Handler & AC  
  - Ductless Mini-Splits  
  - Boilers  
  - AC-only or Furnace-only installs

- **Manual J Load Calculator**  
  Quick or full mode to estimate tonnage needs.

- **Ductwork CFM Calculator**  
  Ensure existing ducts support system airflow requirements.

- **Custom Add-Ons & Rebates**  
  Easily attach accessories and incentives to any quote.

- **Photo Uploader**  
  Include jobsite images in the final proposal.

- **Digital Signature Pad**  
  Capture and store customer approval electronically.

- **Professional PDF Output**  
  Generates a clean, branded agreement with all project details.

---

## 🚀 How to Use

1. **Open `index.html`**  
   Run locally in any browser, or host on GitHub Pages.

2. **Complete Job Info**  
   Input customer name, job type, tonnage, labor hours, etc.

3. *(Optional)* Add accessories, rebates, and photos.

4. *(Optional)* Use built-in calculators (Manual J / Ductwork CFM).

5. **Generate Proposals**  
   Click `Build System Options`.

6. **Review with Customer**  
   Show all pricing tiers and let them choose.

7. **Select & Sign**  
   Click `Select This Option`, then collect signature.

8. **Export as PDF**  
   Click `Accept & Generate PDF` to download signed proposal.

---

## 🛠 How to Update Equipment Pricing

All pricing is managed in a JavaScript object inside `index.html`.

### Steps:

1. Open `index.html` in your code editor.  
2. Search for the variable `equipmentData`.

   ```js
   const equipmentData = {
     furnaces: [ ... ],
     ac: [ ... ],
     // etc.
   };
