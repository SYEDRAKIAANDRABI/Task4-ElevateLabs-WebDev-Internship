# Internship Task 4 - Mobile-Friendly Website

## 📌 Project Overview
This is my submission for Task 4 of my Web Development Internship.  
The goal was to take a desktop-style webpage and make it work properly on mobile devices using CSS Media Queries.

I built a simple portfolio/agency-style landing page and then applied responsive rules so it looks good on phones, tablets, and desktops.

## 🛠️ Tools Used
- **VS Code** – for writing the code
- **Chrome DevTools** – for testing responsiveness and debugging
- **HTML5 & CSS3** – no frameworks, just plain CSS

## 📱 What I Did to Make It Mobile-Friendly
Based on the hints given in the task, here’s what I changed:

1. **Added the viewport meta tag** – so the page scales correctly on mobile screens.
2. **Used relative units** – I switched from fixed `px` to `rem`, `%`, and `vw` for widths, font sizes, and spacing.
3. **Wrote media queries** – I added breakpoints at `1024px` (tablet), `768px` (mobile), and `480px` (small phones).
4. **Stacked columns vertically** – On mobile, the grids (services, portfolio, about section) change from side-by-side to single-column layouts.
5. **Made the navigation collapsible** – On desktop, the menu is horizontal. On mobile, it turns into a hamburger menu that slides in from the right.
6. **Scaled images and icons** – I made sure all images and illustrations shrink within their containers using `max-width: 100%`.
7. **Fixed overflow issues** – I added `overflow-x: hidden` to prevent any unwanted horizontal scrolling.

## 📂 Files Included
- `index.html` – the main webpage structure
- `style.css` – all the styling and responsive media queries

## 🧪 How to Test It Yourself
1. Download both files and put them in the same folder.
2. Open `index.html` in Google Chrome.
3. Open DevTools (`Ctrl + Shift + I` or `Cmd + Option + I`).
4. Click the device toolbar icon (phone/tablet icon) and select any mobile device (like iPhone 12 or Pixel 5).
5. Resize the window or rotate the device to see the layout change.

## ✅ Task Deliverables Checklist
- [x] Updated CSS with media queries
- [x] Works on mobile viewport (under 768px)
- [x] Columns stack vertically on small screens
- [x] Font sizes reduce on mobile
- [x] Navigation collapses into hamburger menu
- [x] No overflow or horizontal scrolling
- [x] Images scale properly

## 💡 What I Learned
- Media queries are actually not that scary once you start using them.
- It's better to design with a "mobile-first" mindset, but for this task I converted a desktop layout to mobile (desktop-first).
- Testing with Chrome DevTools saves a lot of time compared to refreshing on a real phone every time.
- Using `flexbox` and `grid` makes responsive layouts much easier than using floats or tables.

## 🔗 Live Demo
(If you uploaded it to GitHub Pages or a live server, paste the link here. Otherwise, just say "Run locally using the steps above.")

---

*Submitted by: [Your Name]*  
*Date: 07-07-2026*
