# 💌 Interactive Valentine's Proposal App

An interactive, responsive single-file web app built with vanilla HTML, CSS, and JavaScript. It lets anyone create a personalized "Will you be my Valentine?" interactive card with custom messages, photos, and a playful interactive "No" button that grows the "Yes" button dynamically before triggering celebratory confetti!

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ Features

* **Dual-View Architecture:** Functions as both a **Builder** (to customize recipient, photo, prompts, and final messages) and a **Recipient View** (the interactive proposal card).
* **Flexible Personalization:** 
  * Custom recipient name and optional sender signature.
  * Image support via direct URL or local file upload (converted to data URLs for standalone use).
  * Editable opening lines, multi-step persuasive rejection prompts, and a "Yes" celebration message.
* **Playful Interaction:** Clicking "No" cycles through custom persuasion lines while progressively expanding the "Yes" button to gently encourage a positive response.
* **Celebration Effects:** Triggers falling animated confetti upon choosing "Yes".
* **Sharing Options:** Generates a shareable URL query string or packages everything into a **fully self-contained, downloadable HTML file** that works offline and can be shared via AirDrop, email, or messaging apps.

---

## 🚀 Quick Start

Since this application is entirely contained within a **single standalone HTML file**, running or sharing it is effortless:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)

 * Open the file:
   * Double-click index.html to open the builder interface directly in your web browser.
   * Fill out the fields, upload a photo, and click Create my link or Download HTML to share with your special someone!
🛠️ Tech Stack
 * HTML5 / CSS3: Mobile-first layout with clean styling, custom form controls, and CSS keyframe animations for falling confetti.
 * JavaScript (ES6+): Vanilla logic handling state serialization/deserialization via URL parameters (?d=), local file reading (FileReader), dynamic DOM building, and responsive event handling.
📄 License
This project is open-source and available under the MIT License. Feel free to use, customize, and share it to spread some love!

