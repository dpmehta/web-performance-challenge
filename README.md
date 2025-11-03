# 🚀 Performance, Accessibility & SEO Optimization — Web Performance Challenge

## 📝 Description

This focuses on **significantly improving the website’s overall performance, accessibility, and SEO** as part of the web performance challenge.  
Multiple front-end refactors were made to optimize resource loading, enhance semantic HTML, and improve user experience while maintaining compatibility across browsers.

---

## Deplyoed Site & Page Speed Results

- Deplyoed Site :  <a href="https://dpmehta.github.io/web-performance-challenge/"> Deplyoed Site </a>
- Page Speed Results :  <a href="https://pagespeed.web.dev/analysis/https-dpmehta-github-io-web-performance-challenge/ja1xhxsev7?form_factor=mobile"> Results </a>

## 🔧 Key Improvements

### 🖼️ Image Optimization
- Implemented **responsive images** using `srcset` and `sizes` attributes.
- Added **AVIF** and **WebP** sources with **JPEG fallbacks** for backward compatibility.
- Introduced **lazy loading (`loading="lazy"`)** for all media assets.
- Replaced hardcoded background images with proper responsive `<picture>` structures.
- Reduced layout shifts and bandwidth usage on mobile and desktop devices.

### ⚡ Performance Enhancements
- **Deferred non-critical CSS and JS**:
  - Added asynchronous CSS loading for mobile styles.
  - Deferred Swiper CSS/JS loading until window load.
- Removed **unused fonts**, **unnecessary scripts**, and **blocking resources**.
- Added **CSS minification** and a **reset stylesheet** for improved consistency.
- Implemented **lazy loading library (vanilla-lazyload)** to optimize content rendering.
- Removed **Adobe Target pre-hiding** and redundant code to streamline execution.
- Refactored cookie consent flow to **initialize ads and videos only after consent**, improving initial load performance and respecting user privacy.

### 🧱 Code & Structure Refactors
- Simplified **HTML structure** and removed unused styles/scripts.
- Eliminated **Vue.js dependency**, replacing it with lightweight vanilla JS implementation.
- Centralized **script initialization logic** inside event handlers for better control.
- Improved **semantic markup** and added **ARIA roles and labels** for accessibility compliance.

### 🌐 Accessibility & SEO
- Added accurate **`lang="en"`** attribute and improved meta configuration.
- Enhanced **alt text** for images to provide meaningful descriptions.
- Applied **ARIA roles and labels** (`banner`, `navigation`, `region`, `contentinfo`, etc.).
- Improved **document landmarks** for assistive technologies.
- Updated marquee structure for better accessibility and content targeting.
- Optimized metadata and ensured images and scripts load efficiently for SEO scoring improvements.

---

## File Structure

<img width="302" height="457" alt="Image" src="https://github.com/user-attachments/assets/82bc33a2-f9c1-4b82-8cb1-1a3a5263c573" />

---
                

## 📊 Results
After these optimizations, the website achieved **notable improvements** on [PageSpeed Insights](https://pagespeed.web.dev):
- **Performance:** Substantial increase due to deferred resources and responsive media.
- **Accessibility:** Improved due to semantic structure and ARIA enhancements.
- **SEO:** Better indexing signals through optimized HTML and meta practices.

---

## 📹 Demo Video 

Link : <a href="https://drive.google.com/file/d/1_t9kp07-BAtD2ISiUm9A10NNZ2bEwc9D/view?usp=drive_link"> Demo Video </a>

---

## ✅ Summary
This Solution delivers:
- Faster load times and reduced blocking scripts.
- Improved Lighthouse scores (Performance, Accessibility, SEO).
- Cleaner, modern, and maintainable code structure.

---


