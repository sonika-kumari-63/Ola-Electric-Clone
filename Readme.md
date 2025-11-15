# Ola Electric Clone - README

A fully responsive **Ola Electric Landing Page Clone** built using **HTML and CSS**. This project replicates the structure and UI elements of the official Ola Electric website, including scooters, motorcycles, EMI sections, service cards, global EV vision banners, and more.

## Project Overview

This project is a front-end-only clone of the Ola Electric homepage. It contains:
* Navigation bar
* Hero banner with CTA button
* Scooter product cards (S1 Portfolio)
* Electric motorcycle section
* Service center section
* EMI (Installment Calculator) info section
* New generation platform images
* Global EV hub banner
* Footer section

This clone helps users learn **webpage structuring, UI styling, responsive layouts, and component-based design.**

## Technologies Used

### **1. HTML5**
Used for content structure:
* Semantic sections
* Hero image
* Product cards
* Footer and CTA buttons

### **2. CSS3**
Used for styling and responsiveness:
* Flexbox layouts
* Hover animations
* Fixed navigation bar
* Shadows and spacing
* Media queries for mobile



##  Folder Structure


Ola-Electric-Clone/
*index.html          
*style.css           
*images/            
    hero.jpg
    scooter1.png
    roadster.png
    service-img.png
   ...more images


> **Note:** Replace the placeholder image names with actual image file names that you used.

---

## 📄 File Explanation

### ✔️ **index.html**

Your HTML file contains:

#### **1. Navbar**

* Fixed at the top
* Black theme
* Contains logo and navigation links

#### **2. Hero Section**

* Fullscreen background image
* Large heading & subheading
* "Book Now" CTA button

#### **3. Scooter Portfolio (3rd Gen S1 Models)**

Three scooter cards:

* S1 Pro+
* S1 Pro
* S1 X+

Each card includes:

* Image
* Short description
* Pricing details
* Explore and Buy buttons

#### **4. Motorcycle Section**

Three models:

* Roadster X
* Roadster X+
* Roadster

With hover animations and CTA buttons.

#### **5. Service Center Section**

Three service cards:

* 1000+ Centers
* AI Powered Service
* Quick Service Guarantee

#### **6. EMI Calculator Section**

* Details about interest rate, tenure, processing fee
* "Calculate EMI" button

#### **7. New Gen-3 Platform Section**

Large full-screen images showcasing new scooter technologies.

#### **8. Global EV Hub Banner**

Large typography with global EV hub message.

#### **9. Footer**

* Black theme footer with © 2025 message

---

## 🎨 CSS (style.css) Breakdown

Your CSS file includes:

### **1. Global Styles**

* Reset margins, padding
* Base font-family
* Smooth scrolling

### **2. Navbar Styling**

* Fixed position
* Black background
* Flexbox layout
* Hover effects on nav items

### **3. Hero Section**

* Fullscreen image
* Overlayed text
* Responsive text scale

### **4. Product Cards (Scooters & Motorcycles)**

* Flexbox layout
* Box-shadow and hover lift effect
* Button styles and hover states

### **5. Service Section Cards**

* Large image
* Rounded edges
* Clean box layout

### **6. EMI Section**

* Light blue background
* Grid-based feature boxes
* CTA button

### **7. New-Gen / Global Sections**

* Full-width banners
* Centered text
* Mobile-fit images

### **8. Footer**

* Minimal dark footer

### **9. Media Queries**

Breakpoints for:

* 768px (tablet)
* 500px (mobile)
* 400px (small devices)

These ensure responsiveness for product cards, navbar, sections, etc.

---

## 📱 Responsive Behavior

### **Tablet (768px)**

* Hero text shrinks
* Navbar spacing reduces

### **Mobile (500px)**

* Scooter cards stack vertically
* Motorcycle section vertical
* Service cards stack
* EMI features become vertical

### **Small Mobile (400px)**

* Navbar switches layout
* Padding adjustments

---

## ⭐ Key Features

* ✔ Modern UI with clean layout
* ✔ Hover animations
* ✔ Fully responsive on all screen sizes
* ✔ Multi-section homepage just like Ola Electric
* ✔ Smooth scrolling

---

## 🚀 How to Run the Project

1. Download/clone the folder.
2. Place all images into an **images** folder.
3. Open `index.html` in your browser.
4. No installations required.

---

## 🔧 Customization Guide

### **Change Hero Text**

Edit inside:

```html
<div class="hero-text">
```

### **Add More Scooters or Bikes**

Duplicate a card:

```html
<div class="scooter-card">...</div>
```

### **Change Colors**

Modify variables in CSS:

```css
background-color: #000;
```

### **Adjust Responsiveness**

Modify media queries at the bottom of `style.css`.

---

## ⚠️ Known Improvements

* Navbar on smaller screens can be converted to a hamburger menu.
* Buttons can use consistent classes.
* Some sections contain repeated image styling → can be optimized.
* Add JavaScript for EMI calculation and navbar toggle.

---

## 📌 Future Enhancements

* Add animations using AOS library
* JavaScript-based interactive EMI calculator
* Dark mode support
* Add backend for user login / booking
* Convert project to React version

---

## 🏁 Final Notes

This project successfully recreates the Ola Electric homepage using only **HTML and CSS**. It is perfect for learning front-end development, building your portfolio, and understanding complex UI layouts.

If you'd like, I can also help you:

* Create a GitHub repository for this
* Add JavaScript functionality
* Improve responsiveness even more
* Create a React/Next.js version of this site
