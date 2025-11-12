# HTML5 Canvas Day & Night Scene

A visually appealing **day-to-night animation** built using **HTML5 Canvas** and **JavaScript**. The scene features a **moving sun**, **transitioning sky colors**, a **moon at night**, clouds, trees, a house, and animated scenery.

---

## Live Demo

Try it live in your browser:  
[🌐 View Live Demo](https://your-live-demo-link.com)

---

## Demo Video

Watch the animation in action:  
[🎥 Demo Video](https://github.com/user-attachments/assets/5974b7c9-ce52-4c71-af53-be2513f45873)

---

## Screenshots

**Daytime (Sun moving from left to right):**  
<img src="https://github.com/user-attachments/assets/a349bb17-8527-4da1-b1ab-346c1204c5a9" alt="Day Scene" width="800" height="450">

**Sky turns grey near sunset:**  
<img src="https://github.com/user-attachments/assets/b396b093-6b9a-44a5-9594-fdde4ed6e248" alt="Evening Scene" width="800" height="450">

**Nighttime with Moon:**  
<img src="https://github.com/user-attachments/assets/143f3eed-d61e-48e3-bbd2-ee16b9245c5e" alt="Night Scene" width="800" height="450">

---

## Features

* **Sun Movement:** Sun moves horizontally from the left tree to the right tree.
* **Sky Transition:** Bright → Grey → Dark as the day progresses.
* **Moon Appearance:** Moon appears after sunset.
* **Animated Clouds:** Clouds move smoothly across the sky.
* **Scenery Elements:** Includes trees, a house, and text.
* **Smooth Animation:** Implemented using `requestAnimationFrame`.

---

## Technologies Used

* **HTML5**
* **CSS3** for canvas styling
* **JavaScript (ES6)** for drawing and animation

---

## How It Works

1. **Canvas Setup:** A `<canvas>` element is used for rendering the scene.
2. **Draw Functions:** Functions draw the sun, moon, clouds, trees, and house.
3. **Sky Color Logic:** JavaScript calculates the sky color based on a `time` variable:
   * **Day:** Bright blue
   * **Transition:** Grey
   * **Night:** Dark blue
4. **Sun & Moon Movement:**
   * Sun moves horizontally from left to right.
   * Moon appears after sunset.
5. **Animation Loop:** Uses `requestAnimationFrame` for smooth continuous animation.

---

## How to Run

1. Clone or download the repository.
2. Open `index.html` in a modern web browser.
3. Watch the animation in real-time.

---

## Customization

* **Change Sun/Moon Path:** Modify the X/Y positions in the `animate()` function.
* **Adjust Sky Colors:** Edit `getSkyColor()` to use different RGB/HEX values.
* **Add More Scenery:** Create new draw functions for additional elements.

---

## License

This project is open-source and free to use for personal and educational purposes.
