# 🎓 Exam Clock

A clean, high-contrast digital clock designed specifically for exam halls and classrooms. This tool helps students keep track of time without the distraction of ticking seconds or small digits.

## ✨ Features
- **Rounded Time Display:** Updates only at specific intervals (1, 2, 5, 10, 12, or 15 minutes) to help students focus on milestones rather than passing seconds.
- **Landscape View:** Optimized for projectors with exam details on one side and a massive clock on the other.
- **Bilingual Support:** Full RTL (Right-to-Left) support for Hebrew and LTR for English.
- **25% Extra Time Calculator:** Automatically calculates and sets extra time as 25% of exam duration, rounded up to the nearest 5 minutes.
- **Shareable Links:** Setup page generates URL parameters that can be bookmarked or shared with pre-configured exam times.
- **Minimalist Design:** No database, no tracking, just a simple single-session tool.
- **Smart Setup:** Configure Start, End, and Extra Time using a clean Material-themed time picker.

## 🚀 How to Use
1. Open the app in any modern browser.
2. Select your language (ENG/עבר).
3. Set your Exam Start and End times.
4. Either manually set Extra Time or click **25%** to auto-calculate it.
5. Choose your preferred time increment (e.g., the clock updates every 5 minutes).
6. Click **Start Exam Clock**.
7. Share the display page URL to save or reuse the same configuration.

## 🤖 Built with AI
This project was designed and coded through a collaborative session with **T3 Chat**, powered by the **Claude Sonnet 4.5** model. The AI assisted in:
- Architecting the dual-language RTL/LTR layout.
- Implementing the custom time-rounding logic.
- Refining the high-visibility classroom UI.
- Creating URL parameter-based navigation between setup and display pages.
- Developing the 25% extra time calculation feature.

## 🛠️ Built With
- [Vue.js 3](https://vuejs.org/) (via CDN)
- [Flatpickr](https://flatpickr.js.org/) (Material Blue Theme)
- Custom CSS with Flexbox/Grid for high visibility

## 📁 Project Structure
- `index.html` / `index-he.html` - Setup pages (English/Hebrew)
- `display.html` / `display-he.html` - Clock display pages (English/Hebrew)
- `style.css` - Unified stylesheet for all pages
