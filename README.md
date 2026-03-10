# TechThrive 2.0

> **Intra-College Hackathon | Organized by CodeX Club**  
> *Innovate. Integrate. Inspire.*

TechThrive 2.0 is an intra-college hackathon organized by the **CodeX Club** at Quantum University. This 7-hour intensive coding event challenges participants to develop impactful, technology-driven solutions under the theme: **"Smart Campus – Digitalizing Campus Life"**.

---

## 📋 Table of Contents

- [About the Event](#-about-the-event)
- [Theme](#-theme)
- [Problem Tracks](#-problem-tracks)
  - [Track A – Defined Problem Statements](#track-a--defined-problem-statements)
  - [Track B – Open Innovation](#track-b--open-innovation)
- [Website Features](#-website-features)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Running Locally](#-running-locally)
- [License](#-license)

---

## 🎯 About the Event

| Detail       | Info                              |
|--------------|-----------------------------------|
| **Event**    | TechThrive 2.0                    |
| **Organizer**| CodeX Club, Quantum University    |
| **Date**     | 02 December 2025                  |
| **Time**     | 9:00 AM – 4:00 PM (IST)           |
| **Venue**    | Shyamji Auditorium                |
| **Duration** | 7 Hours                           |

The objective of TechThrive 2.0 is to build practical, technology-driven solutions that solve real-world inefficiencies faced by students, faculty, and administration within the campus.

---

## 💡 Theme

**Smart Campus – Digitalizing Campus Life**

Teams are encouraged to identify pain points in campus operations and propose digital solutions that reduce manual effort, improve efficiency, and enhance the overall campus experience.

---

## 🗂️ Problem Tracks

### Track A – Defined Problem Statements

Participants can choose from 9 curated problem statements:

| # | Title | Focus Area |
|---|-------|------------|
| 1 | **Campus Event Hub** | Centralized dashboard for club events with calendar, filters, and one-click registration |
| 2 | **The "On-Duty" (OD) Automator** | Digital workflow to protect student attendance during hackathons & events |
| 3 | **The "Lost & Found" Digital Board** | Image-based digital lost & found feed with search and claim functionality |
| 4 | **Unified 360° Feedback & Grievance Portal** | Anonymous centralized complaint system for Hostel, Mess, Bus, Canteen, and more |
| 5 | **Smart Mess Waste Reduction System** | Meal confirmation platform to minimize food waste and enable NGO donations |
| 6 | **"Campus Genie" – RAG-based AI Assistant** | AI chatbot using Retrieval-Augmented Generation to answer queries from college documents |
| 7 | **Smart Academic Resource Sharer (AI-Enhanced)** | Peer-to-peer notes repository with AI-powered summaries and quizzes |
| 8 | **AI-Based Attendance System** | Face recognition with anti-proxy validation and real-time dashboard |
| 9 | **Blockchain Certificate Validator** | Blockchain-based system to issue and verify participation certificates |

### Track B – Open Innovation

Teams with a unique idea that fits the **Smart Campus** theme can propose their own problem statement, provided it:

- Defines a clear campus-related problem
- Uses technology (AI, Web, App, or Automation)
- Reduces manual effort or improves efficiency

---

## ✨ Website Features

The TechThrive 2.0 event website includes:

- **Animated Loader** with the CodeX Club logo
- **Sticky Navigation Bar** with smooth-scroll links
- **Hero Section** with a background image slideshow and live countdown timer
- **Problem Statements Page** with search and filter functionality (Track A / Track B)
- **Event Timeline** section
- **Winners Podium** with scroll-triggered animations
- **FAQ Section**
- **Registration Modal** linked to a Google Form
- **Responsive Design** optimized for desktop and mobile

---

## 📁 Project Structure

```
TechThrive-2/
├── assets/                  # Images and SVG assets
│   ├── logo.svg
│   ├── logo2.svg
│   ├── hero*.JPG            # Hero slideshow images
│   ├── Winner.JPG
│   ├── 1RunnerUp.JPG
│   └── 2Runnerup.JPG
├── index.html               # Main event website page
├── style.css                # Main stylesheet
├── script.js                # Core JS (countdown, slideshow, navigation, modals)
├── problem-statements.css   # Styles for the problem statements section
├── problem-statements.js    # JS for problem statement rendering & filtering
├── problem-data.json        # Structured data for all problem statements
├── LICENSE                  # GNU GPL v2 License
└── README.md                # This file
```

---

## 🛠️ Technologies Used

- **HTML5** – Semantic page structure
- **CSS3** – Custom styling, animations, and responsive layout
- **JavaScript (Vanilla)** – Countdown timer, slideshow, modals, filtering
- **Font Awesome 6** – Icons
- **Google Fonts** – Orbitron & Poppins typefaces
- **Google Analytics** – Traffic analytics (`gtag.js`)
- **Microsoft Clarity** – User behavior analytics

---

## 🚀 Running Locally

No build tools or dependencies are required. Simply open the project in a browser:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/QuCodeXClub/TechThrive-2.git
   cd TechThrive-2
   ```

2. **Open in a browser:**
   - Open `index.html` directly, **or**
   - Use a local development server for the best experience:
     ```bash
     # Using VS Code Live Server extension, or:
     npx serve .
     ```

3. The site will be available at `http://localhost:3000` (or your chosen port).

---

## 📄 License

This project is licensed under the **GNU General Public License v2.0**. See the [LICENSE](LICENSE) file for details.

---

<p align="center">Made with ❤️ by the <strong>CodeX Club</strong> | Quantum University</p>
