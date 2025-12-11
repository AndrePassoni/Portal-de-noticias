# 📰 News Portal

Welcome to the **News Portal** repository! This is a landing page for a technology-focused news portal, developed to practice modern HTML and CSS concepts, including CSS Grid and responsive design.

![Project Preview](./assets/images/Image%2001.png)
*(Note: You can replace this image path with a real screenshot of your finished project)*

## 💻 About the Project

The goal of this project was to build a responsive, semantic, and modern layout for a news website. The portal features articles on Robotics, Virtual Reality, Artificial Intelligence, and other emerging technologies.

Key features of the layout include:
* **Semantic HTML** structure for better accessibility and SEO.
* **CSS Grid Layout**: Complex page structuring using named grid areas (`featured`, `weekly`, `ai`, `aside`).
* **Dark Mode** aesthetic with high-contrast colors.
* **Modular CSS** architecture for scalability.

## 🛠 Technologies Used

The project was developed using the following technologies:

* **HTML5**: For structure and content semantics.
* **CSS3**:
    * **CSS Grid**: Used for the main layout system.
    * **Flexbox**: Used for alignment of internal components (headers, cards).
    * **CSS Variables**: For consistent theming (colors, fonts).
    * **@import**: To organize styles into modules (global, header, sections, utility).

## 📂 Project Structure

The file organization follows a modular logic to facilitate maintenance:

```text
Portal-de-noticias/
├── assets/          # Images and icons used in the project
├── styles/          # CSS files
│   ├── global.css   # CSS Variables, resets, and body styles
│   ├── header.css   # Specific styles for the navigation header
│   ├── index.css    # Main entry point that imports all other CSS files
│   ├── sections.css # Styles for specific grid areas (Featured, Weekly, AI)
│   └── utility.css  # Utility classes (e.g., .text-2xl, .grid)
└── index.html       # Main HTML structure

## 🚀 How to Run

1.  Clone this repository:
    ```bash
    git clone [https://github.com/AndrePassoni/Portal-de-noticias.git](https://github.com/AndrePassoni/Portal-de-noticias.git)
    ```
2.  Navigate to the project folder.
3.  Open the `index.html` file in your preferred browser.

## 🎨 Design

The design features a dark interface inspired by modern tech aesthetics:
* **Typography**: "Archivo" (via Google Fonts).
* **Colors**: Dark blue background tones with bright blue accents (`--brand-color-light`).

---

### 📝 License

This project is for educational purposes. Feel free to use it for study and practice!

Developed with 💙 by [André Passoni](https://github.com/AndrePassoni)