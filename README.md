# 🌌 Personal Portfolio - Tanakorn Kaewmai

> Modern personal profile page built with pure **HTML, CSS, and JavaScript**, featuring animated particle effects, floating geometric shapes, and social media icons with Font Awesome.

---

## 🧠 Overview

This project is a **single-page personal portfolio** designed to showcase a developer profile in an elegant, animated, and modern style.  
It uses **vanilla JavaScript** for particle animation and **CSS glassmorphism** for a clean, futuristic UI.

### ✨ Key Features

- 🎇 **Animated Particle Background** — smooth, colorful particles that move and react to the mouse.
- 🔺 **Floating Geometric Shapes** — animated shapes (circle, square, triangle) drifting in the background.
- 🧊 **Glassmorphism Card Design** — transparent blur card with soft shadows.
- 🧑‍💻 **Profile Section** — avatar, name, title, and skills tags.
- 🌐 **Social Media Icons** — using `<i>` tags from **Font Awesome** (no image files needed).
- 📱 **Responsive Design** — adapts beautifully to both desktop and mobile screens.

---

## 🧩 Tech Stack

| Type | Technology |
|------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |
| **Icons** | Font Awesome 6.5 |
| **Animation** | CSS Keyframes + Canvas API |
| **Design Style** | Glassmorphism + Neon Gradient |

---

## 🚀 How to Use

1. **Clone or download** this repository  
    ```bash
    git clone https://github.com/tanakorn911/portfolio.git

2. **Open the HTML file directly** 
    ```bash
    open index.html

3. **Optional – Edit your personal details**
    ```
    - Update your name, title, and avatar inside the <div class="profile-card">.
    - Replace your social links in the .social-links section.

4. **Folder Structure**
    ```
    project/
    │
    ├── images/
    │   └── profile.jpg          # Your profile picture
    │
    ├── index.html               # Main HTML file
    └── README.md                # This file

5. 🎨 Customization
    ``` You can easily customize the look: ```
    
    - Change background colors   
        ```css
        background: linear-gradient(135deg, #0a0a0a, #1a1a2e, #16213e);
    
    - Adjust particle density
        In the init() function:
        ```js
        for (let i = 0; i < 80; i++) { ... } // increase or decrease number of particles
    
    - Modify icon colors & hover effects
        ```css
        .social-btn:hover {
            color: #00d4ff;
            background: linear-gradient(135deg, #667eea, #764ba2);
        }

🧑‍🎨 Author
👨‍💻 Tanakorn Kaewmai |
Full Stack Developer
📧 tanakorn488@outlook.com
🌍 GitHub Profile [https://github.com/tanakorn911]


