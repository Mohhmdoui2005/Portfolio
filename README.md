# Hamdaoui Mohamed — Personal Portfolio

Welcome to the repository for my personal portfolio website! This project is a modern, dynamic, and highly interactive single-page application built to showcase my diverse skill set spanning Materials Engineering, Video Editing, DevOps, Cybersecurity, and Linux Administration.

## 🌟 Live Preview
*(Add a link to your hosted portfolio here once deployed, e.g., GitHub Pages, Vercel, or Netlify)*

## ✨ Features

- **Custom Magnetic Cursor**: A sleek custom cursor with magnetic snapping and scaling effects on interactive elements.
- **3D Tilt Cards**: A smooth, perspective-based 3D tilt effect applied to project and profile cards that follows mouse movement.
- **Dynamic Backgrounds**: An animated, glowing mesh gradient background utilizing `mix-blend-screen` and CSS animations to create a breathing environment.
- **Bento Grid Layout**: A modern asymmetrical grid system for the "Experience & Projects" section, optimizing space and visual hierarchy.
- **Animated Typography**:
  - Name cycling animation changing between "Moh", "Mohamed Hamdaoui", and "ELHAMDA".
  - Scroll-triggered text reveal animations using the `IntersectionObserver` API.

## 🛠️ Tech Stack

This project is lightweight and entirely frontend-focused, designed without the need for complex build tools or heavy JavaScript frameworks.

- **HTML5**: Semantic and accessible document structure.
- **Tailwind CSS**: Utility-first CSS framework (loaded via CDN for simplicity) for rapid styling and responsive design.
- **Vanilla JavaScript**: Used for custom interactions (cursor tracking, 3D tilt math, animated text cycling, and intersection observers) without heavy dependencies.
- **Iconify**: Open-source icons integrated seamlessly.
- **Fonts**: A premium typography blend using *Satoshi*, *Inter*, and *JetBrains Mono*.

## 🚀 Getting Started

To run this project locally, you simply need a basic web server to bypass CORS restrictions for certain assets (if applicable) and view the site properly.

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd portfolio2
   ```

2. **Run a local server:**
   If you have Node.js installed, you can use `http-server`:
   ```bash
   npx http-server . -p 3030
   ```
   Alternatively, you can use Python's built-in server:
   ```bash
   python3 -m http.server 3030
   ```

3. **View the site:**
   Open your browser and navigate to `http://localhost:3030`.

## 📁 Project Structure

```text
├── index.html            # Main application file containing all structure, styling, and logic
├── IMG_3751.jpg          # Profile photograph
├── icons8-m-key-96.png   # Website favicon
└── README.md             # Project documentation
```

## 📬 Contact

- **Email**: [mohamed.hamdaoui@g.enp.edu.dz](mailto:mohamed.hamdaoui@g.enp.edu.dz)
- **LinkedIn**: [HAMDAOUI Mohamed](https://www.linkedin.com/in/your-linkedin-profile) *(Update with your actual link)*
- **Location**: Algiers, Algeria
