# 🌿 Nature Explorer - Project Overview

This project is a single-page, modern web interface built using **HTML** and **Tailwind CSS**. It showcases information about forests and animals with a stylish, responsive design.

---

## 📄 Page Structure

### 🔝 Header
- Contains the site title: **“Nature Explorer”**
- Navigation buttons for:
  - **Animals**
  - **Forests**
  - **About Us** (opens a modal)

### 🌄 Hero Section
- Title: “Explore the Wild”
- Subtitle: “Discover the beauty of animals and forests with immersive visuals and facts”
- Positioned under the navigation bar

### 🐾 Animals Section (`#animals`)
- A hidden section that becomes visible when the **Animals** tab is clicked
- Intended to hold cards/images and information about 5 animals
- Cards should be added inside the `<section id="animals">` grid layout

### 🌲 Forests Section (`#forests`)
- Another hidden section toggled by the **Forests** button
- Structured identically to the animals section
- Designed to display forest information and images in a card format

### 🧾 About Us Modal
- A hidden modal (`#aboutModal`) that appears on clicking **“About Us”**
- Contains descriptive text about the creators of the project

### 🔻 Footer
- Displays a copyright
- Contains a link to an Instagram profile

---

## 🧠 JavaScript Functions

- `showTab(tabId)`:
  - Toggles between `#animals` and `#forests` sections
- `toggle
