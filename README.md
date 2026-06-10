# 📱 Animated Sidebar Menu

A sleek, animated sidebar navigation menu built with pure **HTML** and **CSS** — no JavaScript required. Features a smooth slide-in effect triggered by a CSS checkbox hack.

---

## ✨ Features

- 🍔 Hamburger menu button to open the sidebar
- ✖️ Close button inside the sidebar
- 🎞️ Smooth slide-in/out animation using CSS transitions
- 🌫️ Glassmorphism-style sidebar (frosted glass effect)
- 🔗 Navigation links with hover effects
- 📣 Social media icons at the bottom
- 💡 Pure CSS toggle — zero JavaScript

---

## 🖥️ Live Preview

> Open `index.html` in your browser to view the project locally.

---

## 📁 Project Structure

```
Sidebar-Menu/
│
├── index.html        # Main HTML file
├── style.css         # All styling & animations
├── photo.jpg         # Background image
└── README.md         # Project documentation
```

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, transitions, checkbox hack |
| Font Awesome 6 | Menu & social icons |
| Google Fonts (Poppins) | Typography |

---

## ⚙️ How It Works

The sidebar toggle uses the **CSS Checkbox Hack** — no JavaScript needed:

```css
/* When checkbox is checked, slide the sidebar in */
#check:checked ~ .sidebar_menu {
  left: 0;
}
```

1. A hidden `<input type="checkbox">` is placed in the HTML
2. The hamburger icon (`btn_one`) is a `<label>` linked to the checkbox
3. When clicked, it checks/unchecks the checkbox
4. CSS sibling selectors (`~`) react to the checked state and animate the sidebar

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```

2. **Navigate into the folder**
   ```bash
   cd YOUR_REPO_NAME
   ```

3. **Add a background image**
   - Place any image named `photo.jpg` in the project folder
   - Or update the path in `style.css`:
     ```css
     background: url("your-image.jpg");
     ```

4. **Open in browser**
   - Double-click `index.html`, or use **Live Server** in VS Code

---

## 📸 Screenshots

> *(Add a screenshot here)*
>
> ```md
> ![Sidebar Preview](./screenshot.png)
> ```

---

## 👨‍💻 Author

**Ajay** — [@mrajay10](https://github.com/mrajay10)

---

## 📄 License

This project is for **educational purposes only**.