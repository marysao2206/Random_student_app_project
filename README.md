# 🎡 Ultimate Random Spinner Wheel (Flask + MySQL)

[![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3-lightgrey?style=flat-square&logo=flask)](https://flask.palletsprojects.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?style=flat-square&logo=mysql)](https://www.mysql.com/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A fully interactive **spinner wheel web app** built with Flask, MySQL, and TailwindCSS.  
Allows users to add text and image entries, spin a dynamic wheel, and save entries in a MySQL database. Perfect for games, giveaways, classrooms, or team activities. 🎉

---

## 🌟 Features

- ✅ Add **text entries** and **image entries**.  
- ✅ Persistent storage using **MySQL**.  
- ✅ **Shuffle**, **clear**, and **spin** the wheel.  
- ✅ **API endpoints** for entries and template management.  
- ✅ Responsive UI built with **TailwindCSS**.  
- ✅ Winner announcement with image or text.  
- ✅ Local storage fallback (optional) for entries if DB is unavailable.

---

## 📂 Project Structure
```
project-root/
├─ Satic/ # Static files (CSS, JS, images)
├─ Templates/ # HTML templates
│ ├─ index.html
│ ├─ group.html
│ └─ images.html
├─ app.py # Main Flask app
├─ requirements.txt # Python dependencies
└─ README.md
```
# Random Student App - Random Spinning Wheel

A web-based interactive **Random Spinning Wheel** application built with **HTML, CSS, JavaScript**, and **Tailwind CSS**, designed to randomly pick winners or group members. Entries are stored in **localStorage**, so they persist across page reloads.

---

## Features

- Add, remove, or clear entries (names/options).
- Randomly spin a visually animated wheel to select a winner.
- Shows the winning entry in a modal popup.
- Responsive design: works on desktops, tablets, and mobile devices.
- Colorful wheel slices with text labels for each entry.
- LocalStorage support to retain entries across sessions.
- Interactive pointer indicating the current winning segment.

---

## Screenshots

**Home / Spinner Page**
![Spinner Screenshot](path/to/screenshot.png)

**Winner Modal**
![Winner Modal Screenshot](path/to/screenshot2.png)

---

## Technologies Used

- **Frontend**
  - HTML5
  - CSS3 (custom styles + Tailwind CSS)
  - JavaScript (ES6+)
- **backend**
  - Database & MySQL
  - Phyton
- **Fonts**
  - Inter (Google Fonts)
- **Storage**
  - LocalStorage for persistent entries
- **Optional Framework**
  - Flask (if using with Python backend for routing)

---

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/random-student-app.git
   cd random-student-app
# 🎲 Random Group Generator

[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A **web app** to quickly generate random groups from a list of members. Ideal for classrooms, teams, or any activity that requires fair group distribution! 🎉

---

## 🌟 Features

- ✍️ **Add members**: Input names via textarea (one per line or comma-separated).  
- ❌ **Duplicate prevention**: Automatically avoids repeated names.  
- 📊 **Dynamic grouping**:  
  - Set number of groups, or  
  - Set max members per group (auto-calculation included).  
- 🎨 **Color-coded groups** with placeholder icons.  
- 💾 **Persistent storage** using LocalStorage.  
- 🖥️ **Responsive design** via TailwindCSS.  
- 🛠️ **Interactive controls**: Remove members, clear results, regenerate groups.  

---

## 🚀 Usage

1. Add members in the input box.  
2. Configure **Number of Groups** or **Max People per Group**.  
3. Click **START GROUPING** to see the results.  
4. Remove members individually or all at once if needed.  
5. Clear results without deleting members using **Clear Results**.

---

## 📸 Screenshots

*(Add your screenshots here for better visualization)*

---

## ⚙️ Tech Stack

- HTML5 & CSS3  
- JavaScript (ES6)  
- Database & MySQL 
- TailwindCSS  
- LocalStorage  

---

## 🌱 Future Enhancements

- ✅ Gender-based distribution  
- ✅ Pick group representatives  
- ✅ Drag-and-drop member ordering  
- ✅ Export groups to CSV  
- ✅ Animated group generation  

---


# 🎡 Ultimate Random Spinner Wheel

[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-blue?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A **fully interactive spinner wheel web app** to randomly pick a winner or option! Perfect for classrooms, games, giveaways, or team activities. Spin the wheel with names, images, or both! 🎉

---

## 🌟 Features

- ✍️ **Add Text Entries**: Names, prizes, or any option.  
- 🖼️ **Add Image Entries**: Upload files or paste image URLs.  
- 🔄 **Shuffle Options**: Randomize wheel entries instantly.  
- 🗑️ **Clear All Entries**: Reset the wheel quickly.  
- 🎨 **Dynamic Wheel Drawing**: Each option has a distinct slice color.  
- 🏆 **Winner Announcement**: Displays winner with text or image.  
- 💾 **Persistent Storage**: Saves entries using LocalStorage.  
- 📱 **Responsive Design**: Works on desktop and mobile.  
- ⚡ **Smooth Animations**: Realistic spin with easing and friction.  

---

## 🚀 Live Demo

*(Add your deployed live demo link here, e.g., GitHub Pages or your server)*  

---

## 📸 Screenshots

![Wheel Panel](https://placehold.co/600x400?text=Wheel+Panel)
![Entries Panel](https://placehold.co/600x400?text=Entries+Panel)
![Winner Announcement](https://placehold.co/600x400?text=Winner+Announcement)

---

## ⚙️ Tech Stack

- **HTML5 & CSS3**
- **JavaScript (ES6)**
- **Database $ MySQL**
- **TailwindCSS** (for modern styling)
- **Phosphor Icons** (for UI icons)
- **LocalStorage** (for saving entries persistently)
- **Canvas API** (for drawing the spinning wheel)

---

## 📝 Usage

1. **Add entries**  
   - Type a name in the "Add Name or Option" field and press **Enter** or click **+**.  
   - Or add images via file upload or URL.  

2. **Manage entries**  
   - Remove single entries with the ❌ button.  
   - Shuffle or clear all entries using the buttons below the list.  

3. **Spin the Wheel**  
   - Click **SPIN** and watch the wheel rotate.  
   - The winner will be displayed in the center with a card showing text or image.  

---

## 🌱 Future Enhancements

- 🎨 Customizable slice colors and fonts.  
- 🔔 Sound effects on spin or winner announcement.  
- 📤 Export results as CSV or image.  
- 🎁 Add multiple winners or weighted entries.  

---

## 🩵 Author

Sao Mary  
📚 Foundation by first Year Student @ Passerelles numeriques Cambodia💡 
