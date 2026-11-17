# Personal Portfolio Website

A sleek, responsive, and modern dark-themed developer portfolio crafted with semantic **HTML5**, **CSS3**, and vanilla **JavaScript**.

Built by **Hanmanth Poojary**, Computer Science student at **Newton School of Technology**.

---

## 🚀 Features

- **Modern Dark Theme**: Deep dark backgrounds (`#0a0e17`), glassmorphic translucent cards (`backdrop-filter: blur(...)`), ambient gradient glows, and neon cyan / indigo accents.
- **Sticky Navigation Bar**: Fixed at the top with glassmorphic blur, brand identity, navigation links with active scroll indicator, and mobile responsive hamburger drawer.
- **Hero Section**:
  - Greeting & animated status badge: *"Student @ Newton School of Technology"*.
  - Name (*Hanmanth Poojary*) and professional title.
  - Interactive profile card featuring an avatar frame, live JSON status badge, and tech stack tags.
  - Quick action buttons (*View Projects*, *Contact Me*) and social media links (GitHub, LinkedIn, Email).
- **About Me Section**:
  - Detailed background story highlighting coursework and engineering mindset at Newton School of Technology.
  - Core philosophy highlights (Hands-on learning, Modern design, Problem-solving).
  - Quick-info cards for College, Location, Goal, and Interests.
- **Education Section**:
  - Highlighted card for **Newton School of Technology** (B.Tech in Computer Science & Artificial Intelligence).
- **Skills & Technologies**:
  - Categorized into *Frontend Development*, *Languages & Core CS*, and *Tools & Workflows* with animated progress bars.
- **Featured Projects**:
  - Project cards featuring mockups, tags, descriptions, and demo/GitHub links.
- **Contact & Footer**:
  - Working form UI, contact methods, and social links.

---

## 📁 File Structure

```text
├── index.html       # Semantic HTML5 markup
├── style.css        # Modern dark theme styles & responsive queries
├── script.js        # Navbar scroll effect, active link spy, mobile menu toggle
└── README.md        # Documentation and customization guide
```

---

## 💻 How to View the Portfolio

### Option 1: Direct in Browser
Double-click on [index.html](file:///Users/hanmanthpoojary/folder_11/index.html) or open it with any web browser (Chrome, Safari, Edge, Firefox).

### Option 2: Local HTTP Server
Run the following command in your terminal:
```bash
python3 -m http.server 8000
```
Then visit [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🛠️ Customization Guide

1. **Update Name or Bio**: Open [index.html](file:///Users/hanmanthpoojary/folder_11/index.html) and search for `Hanmanth` to update your name or title.
2. **Social Links**: Replace the `href` values in the `.hero-socials` and `.contact-social-row` sections with your actual GitHub, LinkedIn, or Twitter URLs.
3. **Email**: Update `your.email@example.com` with your real email address.
4. **Projects**: Add your own project descriptions and links under the `<section id="projects">` block.
