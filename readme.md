
# 🖼️ Image Slider – Day 25 of 30 Days of JavaScript

An interactive **Image Slider** built with **HTML**, **CSS**, and **JavaScript**. This project allows users to navigate through a collection of images using previous and next buttons with smooth transitions.

---

## ✨ Features

* ✅ Slide navigation with **Previous** and **Next** buttons
* 🌀 Smooth fade-in animation between slides
* 🖥️ Responsive design for different screen sizes
* 🧩 Built with pure JavaScript – no libraries or frameworks

---



## 🌐 Live Demo

🔗 [View Live Project](https://qasim-rokeeb.github.io/Image-Slider) 
---

## 🧱 Built With

* **HTML5** – Structured slide elements and buttons
* **CSS3** – Styling, transitions, media queries
* **JavaScript** – Slide state handling and DOM manipulation

---

## 📁 Project Structure

```bash
Image-Slider/
├── index.html         # HTML structure of the slider
├── style.css          # Styles and responsive design
├── script.js          # Slide navigation logic
├── img/               # Folder containing slide images
│   ├── slide1.jpg
│   ├── slide2.jpg
│   └── ...
└── README.md          # Project documentation
```

---

## ⚙️ How It Works

1. Only one `.slide` has the `.show` class at a time.
2. Clicking the `Next` button:

   * Removes `.show` from the current slide
   * Adds `.show` to the next slide, or loops to the first if at the end
3. Clicking the `Prev` button:

   * Moves backward through the slides, or loops to the last if at the beginning

```js
nextBtn.addEventListener("click", function() {
  // logic to go to the next slide
});

prevBtn.addEventListener("click", function() {
  // logic to go to the previous slide
});
```

---

## 🧠 What I Learned

* DOM selection and event handling
* Dynamically updating classes to control visibility
* Creating a looped slider without external dependencies
* Using `@keyframes` for simple animations

---

## 📅 Challenge

This is **Day 25** of my **30 Days of JavaScript** challenge.
Follow my journey and explore other projects:

📲 [@qasimrokeeb](https://x.com/qasimrokeeb)

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

