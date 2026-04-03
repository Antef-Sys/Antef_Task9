# 🧺 Laundry Wallah

## 📌 Project Overview

Laundry Wallah is a responsive front-end web project that provides a modern user interface for a laundry service. It allows users to explore services and interact with a clean and simple layout.

---

## 🚀 Features

* Responsive design (Mobile, Tablet, Desktop)
* Navigation bar with menu options
* Sidebar menu using **CSS `:focus-within` pseudo-class**
* Clean UI using Flexbox
* Call-to-action button ("Book a Service today!")
* ✨ Interactive button hover animation

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (Flexbox + Media Queries, Transforms, Animations)
* No JavaScript used

---

## 🎯 Key Concepts Used

### 🔹 `:focus-within` Pseudo-Class

This project uses the `:focus-within` pseudo-class to toggle the sidebar menu without JavaScript.

```css
.men:focus-within .sidebar {
    transform: translateX(0);
}
```

---

### 🔹 Button Hover Animation

A 3D hover effect is applied to the main button using CSS transforms:

```css
.btn button:hover {
    transform: scale(1.2) rotate3d(-1, -1, -1, 20deg);
    transition: 1s;
}
```

👉 This creates:

* Zoom-in effect (scale)
* Slight 3D rotation
* Smooth animation

---

## 📱 Responsive Design

* **Desktop (>768px):**

  * Full navigation bar visible

* **Tablet (555px - 768px):**

  * Adjusted layout and font sizes

* **Mobile (<555px):**

  * Navbar links hidden
  * Sidebar (hamburger menu) used

---

## ▶️ How to Run the Project

1. Download or clone the repository
2. Open the project folder
3. Open `index.html` in your browser

---

## 📂 Project Structure

```
LaundryWallah/
│── index.html
│── style.css
│── images/
│── icons/
```

---

## 💡 Future Improvements

* Add JavaScript for better interaction
* Add login/signup functionality
* Connect with backend for real services
* Add more animations and transitions

---

## 👨‍💻 Author

**Antef**

---

## ⭐ Note

This project demonstrates how to build interactive UI using pure CSS, including pseudo-classes like `:focus-within` and advanced transform animations without JavaScript.
