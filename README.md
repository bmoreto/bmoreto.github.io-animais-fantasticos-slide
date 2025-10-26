# 🎞️ Animais Fantásticos – Slide Component

This repository contains **only the slide component** developed for the project **“Animais Fantásticos”**, originally created during the **Complete JavaScript ES6 Course** by [Origamid](https://www.origamid.com/).


## 🚀 About the Component

The **slide** is a fully custom-built JavaScript module designed to create smooth and interactive carousel navigation.  
It was developed entirely in **JavaScript (ES6+)**, using modern programming practices without any external libraries or frameworks.

You can see the slide in action on the final website here:  
🔗 [View the full project](https://bmoreto.github.io/bmoreto.github.io-animais-fantasticos/)

## 🧩 How It Was Built

The component was created using **object-oriented programming (OOP)**, structured into two main classes:

- **`Slide`** → Handles movement, transitions, and drag interactions (mouse and touch).  
- **`SlideNav`** → Extends `Slide` to add navigation controls (arrows and pagination bullets).

---

## ⚙️ Features and Techniques

- **DOM manipulation** using `querySelector` and `addEventListener`  
- **Mouse and touch events** (`mousedown`, `mouseup`, `touchstart`, `touchend`) for drag support  
- **CSS transitions** with `transform: translate3d` for smooth animations  
- **Responsive behavior** — recalculates layout on window resize  
- **Modular JavaScript (ES6)** using `export` and `import` syntax  
- **Custom debounce function** to optimize performance  
- **Custom events** (`changeEvent`) for reactive navigation updates  
- **Inheritance** (`extends`) for better code reuse and organization  

---

## 🧠 Technical Summary

- Built with **JavaScript (ES6+)**  
- No external libraries or frameworks  
- Modular and reusable code structure  
- Fully responsive and optimized for performance  
- Focused on interactivity, smooth animations, and clean code architecture  

---

## 📦 Files

- `slide.js` → Main component logic (movement, transitions, resize)  
- `debounce.js` → Utility function for event optimization  
- `slide-nav.js` → Navigation controls (arrows and pagination)

---

## 🎯 Purpose

The goal of this component is to demonstrate how complex and fluid UI interactions can be built using **pure JavaScript**, while maintaining clean, scalable, and modular code.

---

### 📝 License
This component was developed for **educational purposes** as part of my learning journey in the **Origamid – Complete JavaScript ES6 Course**.
