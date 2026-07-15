# 🪐 Solar System Eclipse Portal

> An interactive, responsive, and feature-rich educational web portal designed to make learning about the solar system and astronomical eclipses fun and engaging. Built with HTML5, CSS3, and Vanilla JavaScript, this portal includes user authentication, course registration, multimedia lessons, an interactive planet slideshow, dynamic quizzes, and progress tracking.

Live Website: **[https://jayadhanush871.github.io/solarsystem_eclipse_website/](https://jayadhanush871.github.io/solarsystem_eclipse_website/)**

---

## ✨ Features

### 🔐 1. Authentication & Security
- **Registration Flow:** Users can register an account with validation for usernames, emails (regex validation), passwords, parent details, phone numbers, and education levels.
- **Secure Access Control:** Password validation and session persistence utilizing **Cookies** and **LocalStorage**.
- **User Logout:** Clears cookies and resets the user session securely.

### 📚 2. Course Registration & Interactive Learning Hub
- **Dynamic Course Enrollment:** Register for specific modules, which unlocks targeted educational resources:
  1. **Solar System Basics**: Learn about the Sun, rocky planets, gas giants, and orbital mechanics. Features a dedicated background ambient sound player (`solar.mp3`).
  2. **Eclipses and Shadows**: Explore the science of shadows (Umbra, Penumbra, Antumbra), Solar eclipses ("Ring of Fire"), and Lunar eclipses. Includes HTML5 video animations, diagrams, and audio support.
  3. **Planets & Their Orbits**: Learn Kepler's Laws, orbital eccentricity, aphelion/perihelion, and axial tilts.
- **Interactive Planet Slideshow:** Auto-rotates through all 8 planets every 5 seconds, displaying real-time data on their structure, orbital period, type (rocky/gas/ice giants), and corresponding high-resolution visuals.

### 📝 3. Dynamic Assessments (Quizzes)
- **Course-Specific Quizzes:** A pool of custom, multiple-choice questions tailored to the enrolled course.
- **Real-Time Score Calculation:** Instantly calculates the score (e.g., out of 12) upon completion.
- **PASS/FAIL Feedback:** Shows immediate visual feedback and advice depending on the performance.
- **Answer Review:** Allows users to review their submitted answers against correct ones.

### 📊 4. Personalized Profile & Progress Tracking
- **Academic Marks Tracker:** Results of assessments are logged and persist across sessions via LocalStorage, showing scores for each completed course module.
- **Detailed User Profile:** Displays account details provided during registration.

### ✉️ 5. Feedback System
- Fully functional contact/feedback form integrated with **Formspree** for direct delivery of user messages to the support team.

---

## 🛠️ Built With

- **Frontend Core:** HTML5, CSS3 (Custom keyframe animations, glassmorphism filters, space background, responsive grids & flexbox).
- **Interactivity:** Vanilla ES6 JavaScript (handling DOM navigation, quiz logic state, local storage management, media controls, and slideshow loops).
- **State & Storage:** LocalStorage (for user profiles and courses) & Browser Cookies (for login sessions).
- **Forms Support:** Formspree API.

---

## 📁 Project Structure

```text
├── assets & media/
│   ├── earth.jpg / jupiter.jpg / mars.jpg ...     # Planetary imagery
│   ├── solar.mp3 / eclipse.mp3                   # Audio tracks
│   ├── solareclipse_video.mp4 / lunareclipse_video.mp4  # Explanatory videos
│   ├── solarsystem.jpg / space_background.jpg     # General background assets
│   └── slideshow1.jpg
├── index.html                                    # Main application & routing logic
├── totalcode_js.html                             # Reference code file
└── README.md                                     # Project documentation
```

---

## 🚀 How to Run Locally

Since this is a static single-page application, you can run it directly:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jayadhanush871/solarsystem_eclipse_website.git
   cd solarsystem_eclipse_website
   ```

2. **Run a local server:**
   - **With Python:**
     ```bash
     python -m http.server 8000
     ```
     Open `http://localhost:8000` in your web browser.
   - **With VS Code Live Server Extension:**
     Open the folder in VS Code, right-click `index.html`, and select **"Open with Live Server"**.

---

## 🌐 Publishing to GitHub Pages

To make it live under your custom URL:
1. Push all files to your GitHub repository.
2. Go to **Settings** > **Pages** inside the repository dashboard.
3. Select **Deploy from a branch** under the Source options.
4. Set the branch to **`main`** and folder to **`/ (root)`**, then click **Save**.

---

**Developed by:** J JAYA DHANUSH
*Building educational web portals with interactive designs.*
