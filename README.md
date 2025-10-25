# 🌌 The Largest Galaxies: An Astronomical Gallery

A dark-themed, responsive web page designed to showcase information and fascinating curiosities about the largest galaxies in the universe. It features a modern, clean grid layout for presenting astronomical data.

---

## ✨ Features

✅ **Dark Mode Aesthetic:** A visually appealing dark theme (`#121214` background) ideal for presenting space-related content.
✅ **Grid Layout:** Uses **CSS Grid** for an organized, three-column card layout on desktop screens.
✅ **Clean Typography:** Leverages the **Mulish** font for all text, ensuring high readability.
✅ **Thematic Design:** Uses a cool blue color (`#02799d`) for the main heading to match the astronomical theme.
✅ **Informational Cards:** Each galaxy is presented in a distinct card with an image, title, and detailed description.

---

## 🛠️ Technologies Used

The project is built using fundamental web technologies:

* **HTML5:** Semantic structure for the header and the main content gallery.
* **CSS3:** Custom styling for the dark theme, grid layout, card styling, and typography.
* **Google Fonts:** Integration of the **Mulish** font for a clean, modern look.

---

## 🎨 Design & Layout

### Color Palette

| Element | Color/Value | Description |
| :--- | :--- | :--- |
| **Background** | `#121214` | Main dark background for the body. |
| **Main Heading** | `#02799d` | Cool blue accent color for the main title. |
| **Sub-Heading** | `#e1e1e6` | Light color for the sub-heading and card titles. |
| **Card Background** | `#202024` | Slightly lighter dark background for the content cards. |
| **Card Border** | `#323238` | Subtle border color for card separation. |
| **Card Paragraph Text**| `#c4c4cc` | Light gray color for the description text. |

### Structure & Components

* **Layout:** The entire page is centered on the screen and padded generously (`72px 104px`) to provide focus on the content.
* **Header:** Contains the main title (`h1: The largest galaxies`) and a sub-title (`p: And curiosities about them`).
* **Gallery (`main`):** Uses a **CSS Grid** defined as `grid-template-columns: repeat(3, 366px)` to enforce a fixed, visually balanced three-column layout.
* **Cards (`.card`):** Each card has a slightly rounded border (`border-radius: 8px`), a border, and uses `overflow: hidden` to ensure the image fits perfectly within the container's rounded corners.

---

## 📂 Content Highlights (Galaxies)

The gallery provides information on six massive galaxies, including:

* **IC 1101:** The largest galaxy in the universe, over 1.04 billion light-years from Earth.
* **Phoenix Cluster:** One of the most massive groups of galaxies, located approximately 5.7 billion light-years away.
* **NGC 262:** One of the largest spiral galaxies known, with a diameter of about 1.3 million light-years.
* **NGC 4889 ("Coma B"):** A supergiant elliptical galaxy discovered by Frederick William Herschel I.
* **NGC 4874 ("Coma A"):** A smooth, ball-shaped galaxy surrounded by a stellar circle.
* **A2261-BCG:** An elliptical galaxy discovered by the Hubble Space Telescope, one million light-years across.

---

## ⚙️ How to Run

1.  Clone or download this repository.
2.  Ensure the `index.html`, `style.css`, and the necessary image assets (placeholders like `assets/01.svg` through `assets/06.svg`) are present.
3.  Open `index.html` in your web browser.

---

## ✅ Live Demo

Click here to view (https://galaxies-cards.netlify.app)
