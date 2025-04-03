# ✈️ Flight Boarding Interface

This is a simple, interactive web-based UI for tracking the progress of a flight boarding process. It includes visual indicators for different stages (Deplaning, Cleaning, Boarding), a real-time clock, and navigation buttons to move through the boarding stages.

---

## 🔧 Features

- 🕒 Real-time clock display
- 📦 Grid layout with three flight process stages:
  - Deplaning
  - Cleaning
  - Boarding
- ➡️ Navigation buttons to highlight current step
- 🔁 Reset functionality with alert after the final step
- 🎨 Clean, responsive styling with Material Icons

---

## 🚀 How It Works

1. When the page loads, the current time is shown.
2. Clicking the right arrow highlights one cube at a time.
3. After reaching the last cube, a popup appears ("Restarting"), and the cycle resets.

---
## 🛠️ Requirements

- Python with Flask (if serving dynamically)
- Images for each flight stage (in `static/images`)
- Internet connection for Material Icons (Google Fonts)

---

## 🖼️ File Structure

---

## 📦 How to Run

1. Make sure your project folder follows the structure above.
2. If using Flask, start your server with:

```bash
python app.py

