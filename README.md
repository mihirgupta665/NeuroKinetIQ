# ⬡ NeuroKinetIQ — Real-Time AI Gym Coach

[![HTML5 Badge](https://img.shields.io/badge/Structure-HTML5-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3 Badge](https://img.shields.io/badge/Styling-CSS3-blue?style=for-the-badge&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Python Badge](https://img.shields.io/badge/Core_Engine-Python_3.12-yellow?style=for-the-badge&logo=python)](https://www.python.org/)
[![Streamlit Badge](https://img.shields.io/badge/Web_App-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit)](https://streamlit.io/)
[![MediaPipe Badge](https://img.shields.io/badge/Computer_Vision-MediaPipe-00C7B4?style=for-the-badge)](https://github.com/google/mediapipe)

A premium, high-fidelity responsive showcase landing page for **NeuroKinetIQ**, a state-of-the-art, computer vision-based real-time AI Gym Trainer. The application analyzes user skeletal landmarks, tracks exercise form parameters in real-time, counts repetitions, and provides auditory and visual correction feedback with sub-100ms latency.

🎥 **Live Application Demo**: [neurokinetiq-ai-realtime-gym-coach.streamlit.app](https://neurokinetiq-ai-realtime-gym-coach.streamlit.app/)  
🔗 **Showcase Webpage**: [neurokinetiq-landing-dashboard.vercel.app](https://neurokinetiq-landing-dashboard.vercel.app/)

---

## ✦ Key Features Demonstrated

- 📊 **Real-time Skeletal Pose Detection**: Leveraging client-side video processing to track core athletic skeletal landmarks.
- 🔊 **Instant Auditory Feedback**: Voice-over cues that trigger dynamically when joints deviate from optimal mathematical thresholds.
- 🔄 **Autonomous Repetition Counter**: Automated state-machines tracking set repetitions, durations, and sets completed.
- 📐 **Biomechanics Metrics Updation**: Joint angle telemetry calculations displayed dynamically.
- 💎 **Premium Landing Page Interface**: Dark mode aesthetics, fluid `16:9` aspect ratio media grids, custom keyframe floating animations, and responsive mobile alignment.

---

## 📂 Project Structure & Architecture

Below is the directory structure for the landing page project, designed cleanly to segregate media assets, typography assets, structures, and layout styling:

```text
LandingPage/
├── IMGs/                                 # Visual assets showing step-by-step user journey
│   ├── 1_Sign_up.png                     # Secure onboarding and authentication
│   ├── 2_Home_Page.png                    # Interactive exercise selector
│   ├── 3_Exercise_Reps_Sets_History.png  # Goal targets & configurations
│   ├── 4_Start_Progress.png              # Session initialization interface
│   ├── 5_Pose_Metrics_Updation.png       # Live joint telemetry & calculations
│   └── 6_Workout_Complete.png            # Session completion telemetry dashboard
├── fonts/                                # Custom typography assets
│   └── Averta.woff2                      # Premium geometric sans-serif body font
├── videos/                               # High-definition demo assets
│   └── NeuroKinetIQVideo.mp4             # Compressed mp4 showing live app telemetry
├── index.html                            # Semantic structure and responsive markup
├── style.css                             # Custom layout parameters, token system & keyframes
└── README.md                             # Professional developer overview (This file)
```

---

## 🛠️ Technology Stack Breakdown

### 🖥️ Showcase Interface (The Landing Page)
* **HTML5 Semantic Markup**: Leverages clean block structure (`<section>`, `<nav>`, `<footer >`) with accessibility ARIA guidelines.
* **Modern CSS3 Token System**: Built upon customizable CSS custom properties (`:root` tokens) for seamless color palettes, glow states, and typography.
* **Fluid Grids & Aspect-Ratios**: Utilizes CSS Grid layouts and modern `aspect-ratio: 16 / 9` structures, rendering screenshots and video media proportionally on all devices.
* **Micro-Animations**: Custom `@keyframes` (floating offsets, active pulse alerts, bouncing mouse scroll guides) to deliver an interactive, alive feel.

### 🧠 Core Coach Application (NeuroKinetIQ Streamlit App)
* **Python**: Back-end mathematical calculations.
* **OpenCV**: Computer vision frame-by-frame image parsing.
* **Google MediaPipe**: Machine learning pipeline for real-time body landmark extraction.
* **Streamlit Framework**: Low-friction web server interface hosting inputs, charts, and video feeds.

---

## ⚙️ How to Run Locally

To launch the landing page locally and guarantee that all local assets (custom fonts, video players) resolve smoothly without CORS blocks:

### Option A: Using Python (Simplest)
If you have Python installed on your local machine, open your Command Prompt inside the directory and execute:

```bash
python -c "import http.server, socketserver; PORT=8000; handler=http.server.SimpleHTTPRequestHandler; print('\n>>> Serving HTTP at http://localhost:8000/ <<<\n'); socketserver.TCPServer(('', PORT), handler).serve_forever()"
```

Open your browser and navigate to: **[http://localhost:8000](http://localhost:8000)**

---

### Option B: Using Node.js/NPM
If you prefer Node.js and want hot-reloading:

```bash
# Start a live development server immediately
npx live-server
```

---

### Option C: Production Deployment (Vercel)
This website is production-ready and optimized for deployment on **Vercel** with security and cache control rules defined in [vercel.json](file:///c:/Users/mihir/Desktop/LandingPage/vercel.json). 

Any push to the `master` branch of your connected GitHub repository will trigger an automatic production build and deployment.

---

## 🎨 Design Systems & Tokens

| Design Token | Value | Purpose |
| :--- | :--- | :--- |
| **Background Color** | `#0a0a0a` | Cinematic dark mode canvas |
| **Accent Theme** | `#f5a623` | Cybernetic Amber (primary buttons, highlights) |
| **Accent Glow** | `rgba(245,166,35,0.18)` | Ambient backdrops & card glow outlines |
| **Secondary Accent** | `#00d4ff` | Technical Cyan (gradient stops & secondary glows) |
| **Primary Typography** | `Averta, sans-serif` | Clean, modern geometric body sans-serif |
| **Display Headings** | `Instrument Serif, serif` | Sophisticated, italicized contrast headers |

---

## 👥 Connect & Inquire

Built with ❣️ by **Mihir Gupta**

* **LinkedIn**: [linkedin.com/in/mihir-gupta-980173299](https://www.linkedin.com/in/mihir-gupta-980173299/)
* **GitHub**: [github.com/mihirgupta665](https://github.com/mihirgupta665)
* **Email**: [mihirgupta665@gmail.com](mailto:mihirgupta665@gmail.com)
